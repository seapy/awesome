# iOS 글 모음

## 일반

- [When to drop iOS 8](https://medium.com/@peter.lafferty/when-to-drop-ios-8-b2bd1edd3e91#.fvkpkgghh)
  - 다음버전 iOS를 지원중단할때 좋은 자료가 될듯. 글쓴이는 iOS 8의 경우 iOS 10 발표하고 다음해 1월 예상

## 마케팅

- [푸시 알림이 앱 리텐션에 미치는 영향](https://www.appannie.com/kr/insights/mobile-strategy/can-push-notifications-really-help-app-retention/)
- [iOS의 앱 이름 변경으로 ASO 전략을 재정비해야 하는 퍼블리셔들](https://www.appannie.com/kr/insights/aso-app-store-optimization/ios-app-name-changes-push-publishers-refine-aso-tactics/)
- [키워드 전략 최적화를 통해서 ASO 개선하기](https://www.appannie.com/kr/insights/aso-app-store-optimization/how-to-improve-your-aso-app-store-optimization-by-maximizing-your-keyword-strategy/)

## 디자인

- [너희들은 그렇게 햄버거 메뉴를 좋아하는 건가?(일본어)](http://qiita.com/usagimaru/items/930de80062bdae880630)
  - 햄버거 메뉴는 까야 제맛인가보다. 실제 사용자들이 잘 인지하는지도 의문. 그냥 기능은 많은데 넣기 좋게 해주는게 아닌가 싶다

## 개발

- [Secondary Views in Interface Builder's Storyboards](http://blog.curtisherbert.com/secondary-views/)
  - IB나 스토리보드에서 Scene View? 였나 그거. Custom View로 빼자니 너무 한거 같고 하나에 다 넣자니 복잡할때 유용할듯.
- [Adding Playgrounds to your Xcode Project](https://medium.com/@LogMaestro/adding-playgrounds-to-your-xcode-project-79d5ea0c7087#.dafgcmp5w)
  - Xcode 프로젝트에 Playground 적용하기. 잘 되는것도 같고 아닌것도 같고. 복잡하긴 하다.
- [https://medium.com/ios-os-x-development/7-things-you-must-absolutely-do-before-writing-an-ios-app-a8bacf710c57#.t5kzsr2bt](7 Things you must absolutely do before writing an iOS app)
  - 초기 설정 및 구조 잡는데 도움이 되는 글
- [Hipster Swift](http://krakendev.io/blog/hipster-swift)
  - swift 에서 잘 안쓰는것 같은것들에 대해 설명. noescape 에 대한 설명이 유용했다
- [Upgrade your TableViews with Loading State](https://thatthinginswift.com/upgrade-tableview-loading-state/)
  - 테이블뷰의 데이터 로딩 상태를 enum 이용해서 간단하게 구현
  - [비슷한 글 Enum-Driven View Controllers](http://www.splinter.com.au/2016/01/03/enum-driven-viewcontrollers/)
- [Creating and Distributing iOS Frameworks](https://www.raywenderlich.com/126365/ios-frameworks-tutorial)
  - 프레임워크로 소스를 재활용하는 방법 소개. pod로 안만들고 그냥 나눠서 사용할때도 괜찮은 방법일듯
- [How Not to Crash #1](http://blog.supertop.co/post/152615019837/how-not-to-crash-1)
  - 크래시 리포트 보는것, 크래시 조심할것 등

## Swift 빌드 타임 관련

- [Profiling your Swift compilation times](http://irace.me/swift-profiling)
  - 빌드 타임이 느려질때 확인하는 방법. Xcode 빌드 확인창에서 보는거라 코드가 많고 프레임워크가 많으면 보기 힘들다
- [BuildTimeAnalyzer-for-Xcode](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode)
  - 빌드 타임을 알 수 있게 해주는 플러그인. Xcode 8에서는 동작하지 않으므로 직접 빌드 해야됨
- [Regarding Swift build time optimizations](https://medium.com/@RobertGummesson/regarding-swift-build-time-optimizations-fc92cdd91e31#.8izoid4we)
  - 빌드 시간을 느리게 만드는 코딩에 대한 이야기. nil 체크, 배열 더하기, 삼항 연산자등이 있다. 그렇지만 안쓸수 없는것들...
