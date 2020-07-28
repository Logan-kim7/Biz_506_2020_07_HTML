

























### index.html
* 일반적으로 홈페이지, 웹페이지라고 부르는 Browser를 통해서
접근하는 프로젝트에서 제일먼저 만나게 되는 파일
* index page, Landing page, paking page 등으로 부른다.
* 시작페이지 라는 용어가 알맞는 말이 된다.
* http://naver.com/ 라고 Browser 주소창에 입력을 하면
http://wwww.naver.com/index.html 이라고 입력한 것과 같다.
http://wwww.naver.com:80/index.html 이 완전한 주소이다.



#### http: Hyper Text Transfer Protocol
* HTML(Hyper Text Markup Lang.)로 만든 문서파일(정보)을 인터넷을
통해서 주고받을 때 사용하는 보편적인 프로토콜
* 모든 내용을 평문(암호화 되지 않은)으로 주고받는다.
* 사용자에 web Browser를 통해서 서버에 요청(request)를 수행하면
서버는 사용자의 요청을 분석하여 여러가지 처리를 수행한 후 
그 결과를 HTML 방식의 코드로 만들어서 응답(Response)하는 구조로 만들어진 프로토콜이다.
* 인터넷 서비스 중에서 www(World Wide Web)환경에서 사용되는 보편적인 프로토콜이다.

#### https: Hyper Text Transfer Protocol Secure Socket Layer
* http 프로토콜에 암호화 기능을 추가하여 Request, Response 되는 정보를 
암호화하여 전송한다.
* https를 프로토콜로 사용하게 되면, 로그인, 회원가입시 입력한 정보가 암호화 되어
  어느정도 보안상 안전을 보장한다.
* 최근 모 포털에서 http 프로토콜을 사용하다가 중간에 개인정보가 탈취되는 사고가 난 뒤로, 많은 웹서비스에서 https를 
  기본으로 사용하는 추세이다.



  #### 인터넷에서 PORT 개념
  * 한개의 IP 주소를 가진 서버, 클라이언트(PC)는 1:1 연결만을 지원하는 체계이다.
  * 하지만 인터넷을 통해서 사용할수 없는 서비스는 그 종류가 매우 다양하여
    1개의 IP에서 1개의 서비스만을 사용하는 것은 매우 낭비가 된다.
  * OSI 7계층 에서  3번쨰 층인 네트워크 계층에서는 1개의 IP로 1개의 연결을 허용하도록 하고
  * 4번쨰 계층인 전송계층에서는 Port라는 개념을 사용하여, 여러가지 서비스를 1개의 IP주소에서 사용할수 있도록 만들어 놓은 개념


  * TCP/IP 프로토콜은 OSI 7 계층에서 3Layer와 Later4를 사용하는 인터넷 프로토콜 규격이다.
  