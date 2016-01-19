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

## 재미 있는 애니메이션

- [UIViewXXYBoom](https://github.com/xxycode/UIViewXXYBoom)
  - 뷰가 재미있게 없어지는 애니메이션 ~
  - ![UIViewXXYBoom](https://github.com/seapy/awesome/raw/master/iOS/assets/UIViewXXYBoom.gif)
- [EasyAnimation](https://github.com/icanzilb/EasyAnimation)
  - 애니메이션 코드를 짧고 간단하게 만들수 있다

## UIViewController

- [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip)
  - 좌우 스와이프로 여러개의 뷰 컨트롤러를 사용할 수 있다. 다양한 스타일 지원

## UITableView

- [Shoyu](https://github.com/yukiasai/Shoyu)
  - UITableView 섹션이나 타입이 여러개일때 귀찮은 분기 코드를 줄여준다. [qiita 글](http://qiita.com/yukiasai/items/50c296599d30dd8de046)
- [SwiftRefresher](https://github.com/morizotter/SwiftRefresher)
  - UIRefreshControl을 대체. 테이블뷰 상단에 당겨서 새로고침을 해준다. 이거 iOS 기본거가 약간 이상해서 고려해볼만 할듯

## UILabel

- [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel)
  - UILabel에 텍스트를 변경할때 재미있게 변경된다. UILabel에 확장은 아니고 상속받아서 구현한거
  - ![LTMorphingLabel](https://github.com/seapy/awesome/raw/master/iOS/assets/LTMorphingLabel.gif)
- [ActiveLabel](https://github.com/optonaut/ActiveLabel.swift)
  - Label에 해쉬태그, 멘션, URL 링크가 동작하도록 한다. 그냥 쓰기는 괜찮을텐데 sizefit이나 높이 구하는데 오류 없는지 확인이 필요. 직접 높이 계산하는데서 쓸수 있을지
  
## Navigation

- [RainbowNavigation](https://github.com/DanisFabric/RainbowNavigation)
  - UINavigationBar를 좀더 이쁘게 표현. 완성도가 괜찮아 보인다. 
  - ![RainbowNavigation](https://github.com/seapy/awesome/raw/master/iOS/assets/RainbowNavigation.gif)

## String

- [BonMot](https://github.com/Raizlabs/BonMot)
  - attributed string 을 만들기 편하게 해준다. 
- [Regex](https://github.com/sharplet/Regex)
  - swift 정규식 매칭 쉽게

## AutoLayout

- [SnapKit](https://github.com/SnapKit/SnapKit)
  - 오토 레이아웃을 DSL로 쉽게 설정
- [Cartography](https://github.com/robb/Cartography)
  - - 오토 레이아웃을 쉽게 설정

## ActionSheet

- [XLActionController](https://github.com/xmartlabs/XLActionController)
  - 커스텀 ActionSheet

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
- [SwiftyUserDefaults](https://github.com/radex/SwiftyUserDefaults)
  - NSUserDefaults를 쉽게 쓰게 하는 라이브러리. 비슷한것들이 많긴 한데 swift 에서는 이거인듯?
- [PermissionScope](https://github.com/nickoneill/PermissionScope)
  - OS에 사용자 권한이 필요한 경우 사용자에게 현황과 권한을 얻는것을 관리
- [R.swift](https://github.com/mac-cain13/R.swift) 
  - swift 에서 리소스를 안드로이드처럼 코드로 관리할 수 있다.

## 이미지 편집

- [Adobe Creative SDK for ios](http://qiita.com/koitaro/items/e99500cd05adda6fb756)
  - 이미지 필터, 이미지 자르기, 방향전환, 문자입력 등을 쉽게 해주는 라이브러리. Adobe에 앱을 등록하고 키를 발급 받아야 한다. 제한이 어디까지인지는 모르겠음

## 지역화

- [Hordor](https://github.com/Aufree/Hodor)
  - 어플리케이션의 언어별 설정을 앱 안에서 변경 가능한 라이브러리. 위챗이 이런식인가보다.
- [Laurine](https://github.com/JiriTrecak/Laurine)
  - 지역화 파일을 만들고 나서 문자열 관리하기 귀찮은데 이거는 문자열이 아니라 코드로 사용할 수 있다. 자동완성도 되고 오타의 위험도 없고 좋다!

## 신기한거

- [KKVerticalText](https://github.com/anthony1618/KKVerticalText)
  - 세로쓰기가 되는 라이브러리. 신기하다. iOS 8만 지원된다고 적혀있음

## 개발도구

- [Rainbow](https://github.com/onevcat/Rainbow)
  - swift 결과창에 텍스트에 색상을 표현
- [SwiftLint](https://github.com/realm/SwiftLint)
  - github swift style을 기준으로 CLI, Xcode에서 스타일을 맞췄는지 확인
- [Crayons](https://github.com/Sephiroth87/Crayons)
  - 코드에서 만들 색상을 IB 색상표에서도 볼수 있어서 좋긴 한데 사용법이 친절하지가 않아서 아직 이해를 못함 ㅜㅜ
- [SwiftGen](https://github.com/AliSoftware/SwiftGen)
  - 지역화 파일, UIImage, Storyboard 등을 자동으로 enum으로 만들어 줘서 코드 자동완성도 돕고 그런거
- [VWInstantRun](https://github.com/wangshengjia/VWInstantRun)
  - Xocde 에서 현재 선택한 부분을 플레바로 실행해준다. 마치 플레이 그라운드 처럼. 외부 라이브러리 까지 로딩되는지는 모르겠는데 되기만 하면 대박일듯. 플레이그라운드 연결하는거 엄청 복잡해서 이런게 필요했음
