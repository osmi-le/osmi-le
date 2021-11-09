
### 권미소
email - kwonms614@gmail.com    

__관심 분야(공부중)__   
>ios(swift) 및 애플 생태계   
>스프링 프레임워크   
>객체 지향 프로그래밍   
   
## 목차
### 프로젝트
- 졸업후   
2020.08 ~ 2021.06 (주)지에스티   
스마트 팩토리 구축   
IDE : Visual Studio(.NET, Dev Express)   
DATABASE : SMMS(SQL Server Management Studio)   
C#, MS-SQL, git으로 형상관리   

- 졸업전
### [Android/JAVA] Wakey Wakey
<img width="200" alt="image" src="https://user-images.githubusercontent.com/52863709/132721921-d5cfdc62-74e9-4e3f-bf7b-d788d100ff00.png">
<img width="200" alt="image" src="https://user-images.githubusercontent.com/52863709/132722107-48fc00d8-b5e9-4067-8227-a820af00735f.jpeg">
   
>3학년 2학기 팀 프로젝트   
>IDE : Android Studio   
>DATABASE : MySQL   
>java로 개발, phpMyAdmin, MySQL로 데이터베이스 
>소스 :   
>아침에 일어나기 어려운 사람을 위한 알람 안드로이드 어플리케이션  
- 실제로 아침에 일어나기 어려운 사람으로써 내가 원하는 기능을 직접 제안하고 만들었습니다. 여러가지 방식으로 알람을 끄고, 알람을 끈 후에 날씨나 일정 앱을 각각 실행해야 하는 번거로움이 있어서 알람이 꺼지면 날씨와 구글 캘린더에 저장된 일정 등을 확인 하고 내 기분과 오늘의 한마디 등을 입력하고 볼 수 있게 만들었습니다. 
phpAdmin을 이용한 mySQL 데이터베이스 연동과 php, GPS모듈, Asynktask를 사용해 날씨 API, 구글 캘린더 API, 차트 라이브러리 등 다양한 기능을 구현할 수 있는 프로젝트였습니다.   
   
- 여러가지 알람 기능 : NFC(카드 인식 후 알람 꺼짐), 자이로 센서(흔들어서 알람 해제), 버튼 터치
- 알람이 꺼진 후에 연동된 구글 캘린더로 일정 표시, 날씨 표시
- 수면 시간 체크 및 기분 체크, 차트로 기분 통계 보여주기   
   
### [Java/JSP] 웹 메일 시스템 유지보수
>4학년 1학기 팀 프로젝트  
>JSP로 만들어진 웹메일 시스템의 기능 추가 및 수정    
>IDE : Eclipse   
>DATABASE : MySQL   
>Java, JSP, (HTML, CSS, Java Script)    
>소스 : https://github.com/rodvkf72/WebMailSystem
- 실제로 현업에서 많이 진행할 유지보수 작업을 미리 진행해보며, 실제 웹 메일 시스템에서 사용자가 필요하고 불편하다고 느낄 것들이 어떤 것이 있는지와 프로그램에서 보안, 성능적으로 요구되는 것들에 대해 생각하며 진행하는 프로젝트였습니다.    
   
- 정적 분석 도구(yasca, SonarQube)를 사용하여 코드의 결함 및 보안문제 체크 후 수정   
- 로그인 시 아이디, 비밀번호의 암호화(SHA-256 알고리즘), 비밀번호 조건 검사   
- 트리거를 이용한 비밀번호를 변경한지 3개월이 경과하면 비밀번호 변경 요청   
- 첨부파일 용량이 큰 경우 쓰레드를 사용한 속도 개선  
- 기존의 파일을 이용한 방식에서 mysql을 이용한 데이터베이스 관리로 변경   
- 세션 만료 404, 500 error 등의 에러페이지 생성
- 완전화 유지보수 작업을 내게 쓰기 기능, 회원가입 기능, 임시보관함 기능, 리스트 페이징 기능 등 추가
- 코드 리팩토링 작업(System.out.println을 로그로 변경, jsp 파일에서의 자바 소스코드 삭제, 스크립틀릿의 사용 최소화 등)   
   
----------------
### [PL-SQL/ProC]
>3학년 2학기 데이터베이스 팀 프로젝트   
>IDE : Visual Studio   
>DATABASE : Oracle(SQL Developer), PL-SQL   
>소스 : https://github.com/yongjjang/Service-Center-System  
- 디버깅이 어려운 ProC라이브러리를 사용하여 어려웠지만 PL/SQL 에 대한 이해도를 높일수 있었습니다. 프로그램의 데이터베이스르 처음부터 설계해 나가며 프로그램의 기능에 따른 데이터베이스 변경 등을 경험할 있었습니다.   
   
- 가상의 전자제품 서비스센터의 데이터베이스를 ERD작성, 테이블 설계 및 명세서 작성, 시나리오 작성
- 서비스센터 직원의 고객 관리, 수리내역 기록, 영수증 출력을 목적을 한 ProC 프로그램   
   
-----------------
### [JAVA] 낚시왕 어드벤처
>3학년 1학기 팀 프로젝트    
>GoF 디자인 패턴을 5개 활용한 텍스트 어드벤처 프로그램   
>IDE : Netbeans   
>JAVA    
- 디자인 패턴 중에 유명한 GoF의 디자인 패턴들을 내가 만들 프로그램의 어떤 기능, 어떤 곳에 적용하여 효율적이고 더 객체지향적인 프로그램을 만들 수 있는지 고민하는 시간이 되었습니다.        
   
- 스테이트 패턴(state pattern)   
  날씨 변화에 맞는 위험 경보 출력   
- 스트레티지 패턴(strategy pattern)   
  미끼를 사용하는 기능을 인터페이스로 구현해 런타임 시에 선택할수 있는 기능   
- 데코레이터 패턴(decorator pattern)   
  사용하는 미끼에 따른 지불 금액과 낚시 능력치 변경 기능    
- 팩토리 메소드 패턴(factory method pattern)   
  낚시터 장소마다 잡히는 물고기의 종류가 변경되는 기능   
- 템플릿 메소드(template method pattern)   
  잡은 물고기로 요리하는 기능. 생선 요리라느 공통적인 부분은 추상화하고, 만드는 법 알고리즘을 추창 메소드로 선언
