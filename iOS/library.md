# iOS 라이브러리 정리

## 알림 UI

- [Whisper](https://github.com/hyperoslo/Whisper)
  - 앱이 실행중 알림을 표시. iOS 기본 알림, 상태바 대체, 네비게이션바 하단 3개의 스타일 제공
  - 메시지를 큐에 넣었다가 순차적으로 표시하지는 않는듯 하다
  - ![whisper](https://github.com/seapy/awesome/raw/master/iOS/assets/whisper.png)
- [JLToast](https://github.com/devxoul/JLToast)
  - 안드로이드 스타일의 Toast 표시
  - 메시지 큐 지원!
  - 하단에 표시되는데 키보드가 올라와 있는경우에 대한 처리가 되는지 궁금
  - ![JLToast](https://github.com/seapy/awesome/raw/master/iOS/assets/jltoast.png)

## 채팅

- [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController)
- [SOMessaging](https://github.com/SocialObjects-Software/SOMessaging)
- [SimpleChat](https://github.com/LoganWright/SimpleChat)
- [RealtimeChat](https://github.com/relatedcode/RealtimeChat)
  - iOS 기본 메시지 스타일
- [Chatto](https://github.com/badoo/Chatto)
- [SwiftParseChat](https://github.com/huyouare/SwiftParseChat)

직접 만들때 도움이 될만한것

- [SPHChatCollectionView](https://github.com/sibahota059/SPHChatCollectionView)
- [FlatChatBubble](https://github.com/sibahota059/FlatChatBubble)
- [whatsapp-ios](https://github.com/rcmcastro/whatsapp-ios)
- [helpstack](https://github.com/happyfoxinc/helpstack)


## 폼

- [Eureka](https://github.com/xmartlabs/Eureka)
  - XLForm의 Swift 버전. 폼을 만들때 쉽게 만들 수 있다.

## 차트

- [ios-charts](https://github.com/danielgindi/ios-charts)
  - iOS 에서 차트를 그릴수 있다. MPAndroidChart 를 따라가는듯

## Non UI 유틸리티

- [AppVersionMonitor](https://github.com/muukii/AppVersionMonitor)
  - 앱 문자열을 가져오고 버전 비교를 할 수 있다.
  - 비슷한 역할을 하는 [SemanticVersioning](https://github.com/AlexanderNey/SemanticVersioning)
- [KeyboardObserver](https://github.com/morizotter/KeyboardObserver)
  - 키보드 보임/안보인 이벤트를 쉽게 처리 할 수 있다
  - [SingleLineKeyboardResize](https://github.com/haaakon/SingleLineKeyboardResize)
    - 이건 한줄로 scrollView, tableView의 insets을 조정해주니 좋긴 한데 다른것도 같이 바꿔야되면 애매함
  - [UnderKeyboard](https://github.com/marketplacer/UnderKeyboard)
    - 뷰의 크기를 바꾸는거라 다른것들에 비해 별로지만 쓸데가 있을듯
  - [DDKeyboardObserver](https://github.com/openboy2012/DDKeyboardObserver)
    - 사용방법이 마음에 든다. 다음에 이런식으로 사용하면 될듯
