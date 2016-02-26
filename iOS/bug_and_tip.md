# 버그 & 팁

애플이 고쳐주지 않는 버그로 인해 고생하는 개발자들 ㅜㅜ 또 버그는 아니더라도 꼼수들 모음

## Xcode

- 맥의 모든 CPU 자원을 사용해 빌드 속도를 높이자
  - Fastlane 에서 적용하려면 Gymfile에 다음과 같이 추가
    - `xcargs "IDEBuildOperationMaxNumberOfConcurrentCompileTasks=`sysctl -n hw.ncpu``
  - 실제 효과를 확인하려고 activity indicator로 봤을때 xcode에서는 효과를 못봤는데 fastlane으로 beta 빌드할때 보니 CPU를 모두 사용
    - <img src="https://github.com/seapy/awesome/raw/master/iOS/assets/xcode_multi_core.png" alt="alt text" height="100px">
    - 시작부분에 4개만 살짝 올라온 부분은 설정 적용전에 fastlane으로 alpha 빌드 했을때. 설정후 fastlane alpha 빌드하니 모든 CPU 사용
    - 실제 시간은 측정안해봤는데 별로 안빨라진것 같기도 하지만 CPU 로드가 다르니 빨라졌을거라고 예상
  - 이거 보면 iOS 개발자는 CPU 클럭 높고 갯수 많은거 쓸수록 시간단축 효과가 있을듯 ㅋㅋㅋ 맥프로 쓰면 어떨까 궁금 
  - [Xcode에서 병렬 빌드하는 방법](http://qiita.com/asuuma/items/8c34f12ac99bcd81870c)
  - [AlexDenisov tweet](https://twitter.com/1101_debian/status/675305084855668738)
  - [For your interest: command-line xcodebuild does not build concurrently #985](https://github.com/fastlane/fastlane/issues/985)

## UITextView

- 텍스트를 변경해도 이전 텍스트의 링크가 남아 있는 버그
  - 아래 방법으로 꼼수를 쓰면 된다. [링크](http://stackoverflow.com/a/25994821/397457)
```
textView.text = nil
textView.text = "​\u{200B}\(newText)"
```
- 텍스트에 링크같은건 터치가능하게 하고 싶지만 선택하는건 원치 않는경우
  - iOS 8.4에서는 되지만 9에서는 안되는 방법 [링크](http://stackoverflow.com/a/27264999/397457)

## NSNotificationCenter

- iOS 9 부터는 unregister 하지 않아도 된다. 알아서 된다고 @_@ [iOS 9 릴리즈노트](https://developer.apple.com/library/mac/releasenotes/Foundation/RN-Foundation/index.html#10_11NotificationCenter), [이걸 다시 상기시켜준 고마운 트윗](https://twitter.com/sandofsky/status/681740795511177216)

## Playground

- Playground 에서 alamofire 사용
```swift
import XCPlayground
XCPlaygroundPage.currentPage.needsIndefiniteExecution = true // playground 에서 비동기 작업 실행을 위해

import Alamofire
Alamofire.request(.GET, "https://httpbin.org/get", parameters: ["foo": "bar"])
    .responseJSON { response in
        debugPrint(response.result)
        XCPlaygroundPage.currentPage.finishExecution() // 비동기 실행이 끝나고 나서 호출해야 한다. 안그러면 계속 돌고 있음
    }
```

## UINavigationBar

- 투명하게 하기
  - 배경에 투명 이미지를 뚜는 방식으로 할수는 있다. [링크](http://stackoverflow.com/questions/2315862/make-uinavigationbar-transparent). 문제는 이게 글로벌로 적용되기 때문에 적용되는 화면을 나가는 시점과 다시 실행 했던 시점같은것들을 잘 체크해야지 안그러면 앱 전체의 네비바가 망가질수 있음


## 애니메이션

- 애니메이션 효과
  - 버튼 텍스트나 색상 바꿀때 그냥 바로 변경하지 않고 효과를 쉽게 줄 수 있다.
  - https://littlebitesofcocoa.com/193-uiview-transition-basics
```
func flip() {
  flipped = !flipped

  UIView.transitionWithView(
    button,
    duration: 0.3,
    options: .TransitionFlipFromTop,
    animations: {
      self.button.setTitle(self.flipped ? "👎🏻" : "👍🏻", forState: .Normal)
    },
    completion: nil
  )
}
```
