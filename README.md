# iOS_Traning
 From [JeaSungLEE/iOSInterviewquestions](https://github.com/JeaSungLEE/iOSInterviewquestions)

# Required
아래 내용들은 최대한 많이 공부해놓는것이 좋습니다 📝

+ 면접시기가 wwdc이후 (7월~11월)이라면 해당년도 wwdc세션들을 봐 두시면 매우매우매우 좋습니다.

[Apple All Videos](https://developer.apple.com/videos/all-videos/)

## iOS
|면접 질문|이슈링크|
|--|--|
|Bounds 와 Frame 의 차이점을 설명하시오.|[#1](../../issues/1)|
|실제 디바이스가 없을 경우 개발 환경에서 할 수 있는 것과 없는 것을 설명하시오.|[#2](../../issues/2)|
|앱이 foreground에 있을 때와 background에 있을 때 어떤 제약사항이 있나요?|[#3](../../issues/3)|
|상태 변화에 따라 다른 동작을 처리하기 위한 앱델리게이트 메서드들을 설명하시오.|[#4](../../issues/4)|
|scene delegate에 대해 설명하시오.|[#5](../../issues/5)|
|앱이 In-Active 상태가 되는 시나리오를 설명하시오|[#6](../../issues/6)|
|NSOperationQueue 와 GCD Queue 의 차이점을 설명하시오|[#7](../../issues/7)|
|GCD API 동작 방식과 필요성에 대해 설명하시오|[#8](../../issues/8)|
|자신만의 Custom View를 만들려면 어떻게 해야하는지 설명하시오|[#9](../../issues/9)|
|iOS 앱을 만들고, User Interface를 구성하는 데 필수적인 프레임워크 이름은 무엇인가?|[#10](../../issues/10)|
|Foundation Kit은 무엇이고 포함되어 있는 클래스들은 어떤 것이 있는지 설명하시오.|[#13](../../issues/13)|
|Delegate란 무언인가 설명하고, retain 되는지 안되는지 그 이유를 함께 설명하시오.|[#14](../../issues/14)|
|NotificationCenter 동작 방식과 활용 방안에 대해 설명하시오.|[#15](../../issues/15)|
|UIKit 클래스들을 다룰 때 꼭 처리해야하는 애플리케이션 쓰레드 이름은 무엇인가?|[#16](../../issues/16)|
|TableView를 동작 방식과 화면에 Cell을 출력하기 위해 최소한 구현해야 하는 DataSource 메서드를 설명하시오.|[#17](../../issues/17)|
|하나의 View Controller 코드에서 여러 TableView Controller 역할을 해야 할 경우 어떻게 구분해서 구현해야 하는지 설명하시오.|[#18](../../issues/18)|
|App Bundle의 구조와 역할에 대해 설명하시오.|[#19](../../issues/19)|
|View 객체에 대해 설명하시오.|[link]()|
|UIView 에서 Layer 객체는 무엇이고 어떤 역할을 담당하는지 설명하시오.|[link]()|
|UIWindow 객체의 역할은 무엇인가?|[link]()|
|UINavigationController 의 역할이 무엇인지 설명하시오.|[link]()|
|모든 View Controller 객체의 상위 클래스는 무엇이고 그 역할은 무엇인가?|[link]()|
|앱이 시작할 때 main.c 에 있는 UIApplicationMain 함수에 의해서 생성되는 객체는 무엇인가?|[link]()|
|UIApplication 객체의 컨트롤러 역할은 어디에 구현해야 하는가?|[link]()|
|앱의 콘텐츠나 데이터 자체를 저장/보관하는 특별한 객체를 무엇이라고 하는가?|[link]()|
|앱 화면의 콘텐츠를 표시하는 로직과 관리를 담당하는 객체를 무엇이라고 하는가?|[link]()|
|Swift의 클로저와 Objective-C의 블록은 어떤 차이가 있는가?|[link]()|
|App의 Not running, Inactive, Active, Background, Suspended에 대해 설명하시오.|[link]()|
|App thinning에 대해서 설명하시오.|[link]()|
|Global DispatchQueue 의 Qos 에는 어떤 종류가 있는지, 각각 어떤 의미인지 설명하시오.|[link]()|

## Autolayout

|면접 질문|링크|
|--|--|
|오토레이아웃을 코드로 작성하는 방법은 무엇인가? (3가지)|[#20](../../issues/20)|
|hugging, resistance에 대해서 설명하시오.|[#21](../../issues/21)|
|Intrinsic Size에 대해서 설명하시오.|[#28](../../issues/28)|
|스토리보드를 이용했을때의 장단점을 설명하시오.|[#29](../../issues/29)|
|Safearea에 대해서 설명하시오.|[link]()|
|Left Constraint 와 Leading Constraint 의 차이점을 설명하시오.|[link]()|

## Swift

|면접 질문|링크|
|--|--|
|Optional 이란 무엇인지 설명하시오.|[#22](../../issues/22)|
|Fast Enumeration 이란 무엇인지 설명하시오. |[#23](../../issues/23)|
|Struct 가 무엇이고 어떻게 사용하는지 설명하시오.|[#24](../../issues/24)|
|instance 메서드와 class 메서드의 차이점을 설명하시오.|[#25](../../issues/25)|
|Delegate 패턴을 활용하는 경우를 예를 들어 설명하시오.|[#30](../../issues/30)|
|Singleton 패턴을 활용하는 경우를 예를 들어 설명하시오.|[#31](../../issues/31)|
|KVO 동작 방식에 대해 설명하시오.|[link]()|
|Delegates와 Notification 방식의 차이점에 대해 설명하시오.|[link]()|
|멀티 쓰레드로 동작하는 앱을 작성하고 싶을 때 고려할 수 있는 방식들을 설명하시오.|[link]()|
|MVC 구조에 대해 블록 그림을 그리고, 각 역할과 흐름을 설명하시오.|[link]()|
|프로토콜이란 무엇인지 설명하시오.|[link]()|
|Hashable이 무엇이고, Equatable을 왜 상속해야 하는지 설명하시오.|[link]()|
|mutating 키워드에 대해 설명하시오.|[link]()|
|탈출 클로저에 대하여 설명하시오.|[link]()|
|Extension에 대해 설명하시오.|[link]()|
|접근 제어자의 종류엔 어떤게 있는지 설명하시오|[link]()|
|defer란 무엇인지 설명하시오.|[link]()|
|defer가 호출되는 순서는 어떻게 되고, defer가 호출되지 않는 경우를 설명하시오.|[link]()|

## ARC

|면접 질문|링크|
|--|--|
|ARC란 무엇인지 설명하시오.|[link]()|
|Retain Count 방식에 대해 설명하시오.|[link]()|
|Strong 과 Weak 참조 방식에 대해 설명하시오.|[link]()|
|ARC 대신 Manual Reference Count 방식으로 구현할 때 꼭 사용해야 하는 메서드들을 쓰고 역할을 설명하시오.|[link]()|
|retain 과 assign 의 차이점을 설명하시오.|[link]()|
|순환 참조에 대하여 설명하시오.|[link]()|
|강한 순환 참조 (Strong Reference Cycle) 는 어떤 경우에 발생하는지 설명하시오.|[link]()|
|특정 객체를 autorelease 하기 위해 필요한 사항과 과정을 설명하시오.|[link]()|
|Autorelease Pool을 사용해야 하는 상황을 두 가지 이상 예로 들어 설명하시오. |[link]()|
|다음 코드를 실행하면 어떤 일이 발생할까 추측해서 설명하시오. <br/> Ball *ball = [[[[Ball alloc] init] autorelease] autorelease]; |[link]()|


## Functional Programming

|면접 질문|링크|
|--|--|
|함수형 프로그래밍이 무엇인지 설명하시오.|[link]()|
|고차 함수가 무엇인지 설명하시오.|[link]()|
|Swift Standard Library의 map, filter, reduce, compactMap, flatMap에 대하여 설명하시오.|[link]()|

# Optional
아래부터는 추가로 공부를 하면 좋을 내용들입니다.

Objective-c나 rx는 회사, 팀마다 사용하는곳이 차이가있고 신입이나 주니어기준으로 필수라고 여겨지지않기에 옵셔널에 추가하였습니다.

<details>
<summary>고급</summary>
<div markdown="1">
 
## Advanced

|면접 질문|링크|
|--|--|
|NSCoder 클래스는 어떤 상황에서 어떻게 써야 하는지 설명하시오.|[link]()|
|Responder Chain 구조에 대해 설명하고, First Responder 역할에 대해 설명하시오.|[link]()|
|NSObject부터 UIButton 까지 상속 과정의 계층과 역할을 설명하시오.|[link]()|
|shallow copy와 deep copy의 차이점을 설명하시오.|[link]()|
|Push Notification 방식에 대해 설명하시오.|[link]()|
|Foundation 과 Core Foundation 프레임워크의 차이점을 설명하시오.|[link]()|
|NSURLConnection 에서 사용하는 Delegate 메서드들에 대해 설명하시오.|[link]()|
|Synchronous 방식과 Asynchronous 방식으로 URL Connection을 처리할 경우의 장단점을 비교하시오.|[link]()|
|Plist 파일 구조와 Plist 파일에 저장된 데이터를 다루기 적합한 클래스를 설명하시오.|[link]()|
|Core Data와 Sqlite 같은 데이터 베이스의 차이점을 설명하시오.|[link]()|
|JSON 데이터를 처리하는 방식과 파서, 객체 변환 방식에 대해 설명하시오.|[link]()|
|XML Parser를 사용하려면 어떻게 해야 하는지 설명하시오.|[link]()|
|웹 서버와 HTTP 연결을 사용해서 데이터를 주거나 받으려면 사용해야 하는 클래스와 동작을 설명하시오.|[link]()|
|DOM 방식과 SAX 방식 XML Parser의 차이점을 설명하고 iOS XML Parser는 어떤 방식인지 설명하시오.|[link]()|
|In-App Purchase Product type 을 설명하시오.|[link]()|

## Architecture

|면접 질문|링크|
|--|--|
|MVVM, MVC, Ribs, VIP 등 자신이 알고있는 아키텍쳐를 설명하시오.|[link]()|
|의존성 주입에 대하여 설명하시오.|[link]()|

## Rx

|면접 질문|링크|
|--|--|
|Reactive Programming이 무엇인지 설명하시오.|[link]()|
|RxSwift에서 Hot Observable과 Cold Observable의 차이를 설명하시오.|[link]()|

</div>
</details>
