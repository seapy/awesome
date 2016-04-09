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
  - 이유는 모르겠는데 swift 기반 프로젝트에서 안뜸. obj-c는 안해봐서 모름
  - ![JLToast](https://github.com/seapy/awesome/raw/master/iOS/assets/jltoast.png)
- [toast](https://github.com/scalessec/toast)
  - 안드로이드 스타일 toast
- [EZTextSpace](https://github.com/goktugyil/EZTextSpace)
  - 알림은 아니지만 게임처럼 하단에 박스형태로 표시해주는거 재밌다

## 채팅

- [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController)
- [SOMessaging](https://github.com/SocialObjects-Software/SOMessaging)
- [SimpleChat](https://github.com/LoganWright/SimpleChat)
- [RealtimeChat](https://github.com/relatedcode/RealtimeChat)
  - iOS 기본 메시지 스타일
- [Chatto](https://github.com/badoo/Chatto)
- [SwiftParseChat](https://github.com/huyouare/SwiftParseChat)
- [TSWeChat](https://github.com/hilen/TSWeChat)
  - WeChat을 swift로 구현한 샘플

직접 만들때 도움이 될만한것

- [SPHChatCollectionView](https://github.com/sibahota059/SPHChatCollectionView)
- [FlatChatBubble](https://github.com/sibahota059/FlatChatBubble)
- [whatsapp-ios](https://github.com/rcmcastro/whatsapp-ios)
- [helpstack](https://github.com/happyfoxinc/helpstack)


## 폼

- [Eureka](https://github.com/xmartlabs/Eureka)
  - XLForm의 Swift 버전. 폼을 만들때 쉽게 만들 수 있다.

## 화면전환 효과

- [TransitionTreasury](https://github.com/DianQK/TransitionTreasury)
  - 화면 전환할때 효과를 쉽게 사용할 수 있고 정의할 수 있다고 한다. 이거 필요한 경우 가끔 있었는데 ㅜㅜ 

## 차트

- [ios-charts](https://github.com/danielgindi/ios-charts)
  - iOS 에서 차트를 그릴수 있다. MPAndroidChart 를 따라가는듯

## 재미 있는 애니메이션

- [UIViewXXYBoom](https://github.com/xxycode/UIViewXXYBoom)
  - 뷰가 재미있게 없어지는 애니메이션 ~
  - ![UIViewXXYBoom](https://github.com/seapy/awesome/raw/master/iOS/assets/UIViewXXYBoom.gif)
- [EasyAnimation](https://github.com/icanzilb/EasyAnimation)
  - 애니메이션 코드를 짧고 간단하게 만들수 있다
- [SAConfettiView](https://github.com/sudeepag/SAConfettiView)
  - 화면에 꽃가루가 내린다
- [NumberMorphView](https://github.com/me-abhinav/NumberMorphView)
  - 비행기 기다릴때 처럼 숫자가 접히면서 바뀐다
- [JDAnimationKit](https://github.com/JellyDevelopment/JDAnimationKit)
  - 애니메이션을 쉽게 처리하게 하는 라이브러리. facebook pop 라이브러리 기반. anchor point만 잘 적용되는거면 괜찮을듯... 

## Loader

- [FillableLoaders](https://github.com/poolqf/FillableLoaders)
  - 로더들 별로 안좋아 하지만 이건 괜찮을듯. 기다리는게 심심하지 않게... 

## 디자인 라이브러리

- [Material](https://github.com/CosmicMind/Material)
  - Material 디자인에 많이 나오는 UI들 구현한 라이브러리

## UIViewController

- [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip)
  - 좌우 스와이프로 여러개의 뷰 컨트롤러를 사용할 수 있다. 다양한 스타일 지원
- [STLBGVideo](https://github.com/StoneLeon/STLBGVideo)
  - UIViewController 뒤에 비디오를 재생시킨다
- [TabPageViewController](https://github.com/EndouMari/TabPageViewController)
  - 안드로이드 스타일 상단 탭. 무제한 스크롤도 지원

## TabBar

- [ESTabBarController](https://github.com/ezescaruli/ESTabBarController)

## UITableView

- [Shoyu](https://github.com/yukiasai/Shoyu)
  - UITableView 섹션이나 타입이 여러개일때 귀찮은 분기 코드를 줄여준다. [qiita 글](http://qiita.com/yukiasai/items/50c296599d30dd8de046)
  - Enable Bitcode가 활성화 되있어야 된다. 활성화 되어 있지 않은 경우 앱스토어에 빌드 올리면 거기서만 실패함.
- [SwiftRefresher](https://github.com/morizotter/SwiftRefresher)
  - UIRefreshControl을 대체. 테이블뷰 상단에 당겨서 새로고침을 해준다. 이거 iOS 기본거가 약간 이상해서 고려해볼만 할듯

## UICollectionView

- [StickyCollectionView](https://github.com/matbeich/StickyCollectionView)
  - 컬렉션뷰인데 카드처럼 쌓이면서 덮어지는 방식

## UIScrollView

- [TLYShyNavBar](https://github.com/telly/TLYShyNavBar)
  - 스크롤 하면 네비게이션바가 사라진다. [GTScrollNavigationBar](https://github.com/luugiathuy/GTScrollNavigationBar)도, [RainbowNavigation](https://github.com/DanisFabric/RainbowNavigation), [LTNavigationBar](https://github.com/ltebean/LTNavigationBar)

## UILabel

- [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel)
  - UILabel에 텍스트를 변경할때 재미있게 변경된다. UILabel에 확장은 아니고 상속받아서 구현한거
  - ![LTMorphingLabel](https://github.com/seapy/awesome/raw/master/iOS/assets/LTMorphingLabel.gif)
- [ActiveLabel](https://github.com/optonaut/ActiveLabel.swift)
  - Label에 해쉬태그, 멘션, URL 링크가 동작하도록 한다. 그냥 쓰기는 괜찮을텐데 sizefit이나 높이 구하는데 오류 없는지 확인이 필요. 직접 높이 계산하는데서 쓸수 있을지
  
## UIButton

- [RNLoadingButton-Swift](https://github.com/souzainf3/RNLoadingButton-Swift)
  - 버튼 눌렀을때 로딩이 표시... 이런거 자주 써먹을데 있을듯

## UITextView

- [PlaceholderTextViewDemo](https://github.com/DigitalLeaves/PlaceholderTextViewDemo)
  - IB에서도 오류 없이 잘된다. border 설정도 되고 좋음. cocoapods 지원안하는게 아쉽긴 한데 간단하니까 좋다
- [MBAutoGrowingTextView](https://github.com/MatejBalantic/MBAutoGrowingTextView)
  - 줄이 늘어남에 따라 자동으로 커지는 textview
- [NextGrowingTextView](https://github.com/muukii/NextGrowingTextView)
  - 줄이 늘어남에 따라 자동으로 커지는 textview

## UITextField

- [UITextField-Shake](https://github.com/andreamazz/UITextField-Shake)
  - UITextField가 좌우로 흔들리는 애니메이션. 비번같은거 잘못 입력했을때 사용하기 좋겠다

## MenuItem

- [MenuItemKit](https://github.com/cxa/MenuItemKit)
  - 메뉴 아이템에 이미지를 사용할수 있게 하고 block 지원

## Navigation

- [RainbowNavigation](https://github.com/DanisFabric/RainbowNavigation)
  - UINavigationBar를 좀더 이쁘게 표현. 완성도가 괜찮아 보인다. 
  - ![RainbowNavigation](https://github.com/seapy/awesome/raw/master/iOS/assets/RainbowNavigation.gif)

## String

- [BonMot](https://github.com/Raizlabs/BonMot)
  - attributed string 을 만들기 편하게 해준다. 
- [Regex](https://github.com/sharplet/Regex)
  - swift 정규식 매칭 쉽게
- [SwiftString](https://github.com/amayne/SwiftString)
  - 자주 쓰는 문자열 다루는 메소드 모음. trim, capitalize..
- [JNaturalKorean](https://github.com/trillione/JNaturalKorean)
  - 한국어 조사를 알맞게 표시

## AutoLayout

- [SnapKit](https://github.com/SnapKit/SnapKit)
  - 오토 레이아웃을 DSL로 쉽게 설정
- [Cartography](https://github.com/robb/Cartography)
  - - 오토 레이아웃을 쉽게 설정

## ActionSheet

- [XLActionController](https://github.com/xmartlabs/XLActionController)
  - 커스텀 ActionSheet

## UIStackView

- [TZStackView](https://github.com/tomvanzummeren/TZStackView), [OAStackView](https://github.com/oarrabi/OAStackView)
  - iOS 7,8 에서도 UIStackView 같은걸 사용할수 있게 

## UIColor

- [Hue](https://github.com/hyperoslo/Hue)
  - 색상 헬퍼. 그라데이션 색상 쉽게 해주거나

## 제스쳐, 이벤트

- [Tactile](https://github.com/delba/Tactile)
  - UIView, UIControl에 제스쳐를 쉽게 매핑

## 권한 관리

- [PermissionScope](https://github.com/nickoneill/PermissionScope)
  - OS에 사용자 권한이 필요한 경우 사용자에게 현황과 권한을 얻는것을 관리
- [Permission](https://github.com/delba/Permission)
  - 권한 체크. 최초에는 시스템 팝업, 거절한 이후에는 설정으로 가라는 팝업. 과도하지 않아서 좋네. 항상 구현하던건데

## 이미지 보기

- [JTSImageViewController](https://github.com/jaredsinclair/JTSImageViewController)
  - 이미지를 확대/축소 가능하게 하고 쉽게 닫을때 쓰는거

## 사운드

- [JSQSystemSoundPlayer](https://github.com/jessesquires/JSQSystemSoundPlayer)
  - 소리 재생하는걸 쉽게 해준다. 짧은 효과음에 사용

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
- [R.swift](https://github.com/mac-cain13/R.swift) 
  - swift 에서 리소스를 안드로이드처럼 코드로 관리할 수 있다.
- [SwiftDate](https://github.com/malcommac/SwiftDate)
  - NSDate의 부족한점을 커버해준다. 비슷한걸로 DateTools
- [Scale](https://github.com/onmyway133/Scale)
  - swift로 만들어진 단위 변환 라이브러리. 그런데 4.days 이런식으로도 쓸수 있다 유용!
- [VersionTrackerSwift](https://github.com/tbaranes/VersionTrackerSwift)
  - 해당 버전에서 처음으로 실행되었는지등을 확인하는 라이브러리

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

## 스플래쉬 화면

- [SKSplashView](https://github.com/sachinkesiraju/SKSplashView)
- [CBZSplashView](https://github.com/callumboddy/CBZSplashView)
- [LaunchScreenViewController](https://github.com/k06a/LaunchScreenViewController)
- http://iosdevtips.co/post/88481653818/twitter-ios-app-bird-zoom-animation
  - 심플하게 구현하는것에 대한 설명. 모든 화면에 항상 노출되므로 괜찮은 방법

## 앱 사용 설명 / 가이드 / Walkthrough / 튜토리얼

- [Gecco](https://github.com/yukiasai/Gecco)
  - 앱 사용방법을 화면에 포인트를 찍어가며 알려주는거
- [AlertOnboarding](https://github.com/PhilippeBoisney/AlertOnboarding)
  - 팝업 형태로 뜨는거라 평소에 사용자에게 노출하기 좋을듯
- [EAIntroView](https://github.com/ealeksandrov/EAIntroView)
  - 엡 시작시 스크롤 하면서 설명 보여주는 것 
- [Presentation](https://github.com/hyperoslo/Presentation)
  - 앱 시작시 스크롤 하면서 설명 보여주는 건데 애니메이션 및 parallax 스크롤 지원. 단점은 그냥 한방향으로 흘러가 버리는 애니메이션만 지원한다는거?
- [RazzleDazzle](https://github.com/IFTTT/RazzleDazzle)
  - 앱 시작시 스크롤 하면서 설명 보여주는거. 미리 지정된 애니메이션이 있어서 사용하기 간단할듯?

## 키보드

- [MMNumberKeyboard](https://github.com/matmartinez/MMNumberKeyboard)
  - iOS 기본 숫자패드는 소수점을 입력 못하는데 이건 가능! 아이폰/아이패드 지원

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
- Swift 스타일 검사
  - [SwiftLint](https://github.com/realm/SwiftLint), [tailor](https://github.com/sleekbyte/tailor)
    - SwiftLint가 더 인기 있는것 같지만 tailor도 괜찮을듯? 둘다 brew로 설치하고 xcode 에 쉘스크립트로 등록하거나 별도로 실행하는 방식. swiftlint는 fastlane 액션이 있음! 
- [Knuff](https://github.com/KnuffApp/Knuff)
  - 맥에서 APNS(애플 푸쉬) 보내는 테스트 할때 유용한 앱
- [ThisCouldBeUsButYouPlaying](https://github.com/neonichu/ThisCouldBeUsButYouPlaying)
  - cocoapod 플러그인, pod 프로젝트를 포함한 상태의 플레이 그라운드를 만들어준다. 간단하게 cocoapod 사용법 확인하거나 할때 완전 유용할듯
- [GoOutside](https://github.com/dbgrandi/GoOutside)
  - 최근 빌드 시간을 알려준다. 빌드 예상시간을 알수 있어서 좋네. 이름도 좋고
- [Cichlid](https://github.com/dealforest/Cichlid)
  - Xcode의 Drived Data를 자동으로 정리. Clean 할때 자동으로 해준다! 이건 좋네. fastlane 에서 clean 할때는 동작 안하겠지만. 대부분 Xcode 문제 발생하면 Clean 하는거 생각하면 괜찮은 동작
- [watchdog](https://www.cerebralgardens.com/watchdog)
  - Xcode의 Drived Data를 자동 및 수동으로 삭제. 별도 앱이라 설치가 편함. 마지막 업데이트가 너무 오래전이고 유료인건 아쉬움
