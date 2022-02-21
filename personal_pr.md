## 개인 PR 관련

### 자기 소개
- 1분 자기소개
    - 안녕하십니까! 저는 Robotics Software Engineer, Backend 분야에 지원한 이채영입니다. 저의 별명은 진미채 입니다. 진짜 미리 미리 준비하는 채영이, 라는 뜻으로 항상 무엇이든 최상의 결과를 얻기위해 계획하고 노력하는 모습에서 친구들이 만들어준 것입니다. 
- 자신의 차별점 및 강점
    - 저의 장점은 끊임없
- 자신이 왜 적합한 사람인가?
- 왜 우리 회사를 지원
- 성격의 장단점

### 이력서
<details>
<summary>Django</summary>
    - 구현을 위한 기본 틀을 제공해준다. model, view, template MVT 아키텍쳐를 가지고 있다.
</details>

<details>
<summary>Flask</summary>
    - 간단한 구조 제공하여 외부 library 사용이 필요하다.
</details>

<details>  
<summary>Node.js</summary>
    </br>
    <p>회원 비밀번호는 어떻게 저장(bcypt)</p>
        <p> - post 메서드로 request 바디에 사용자가 입력한 아이디와 비밀번호가 들어오면 bcypt로 암호화하여 mysql에 저장했습니다.</p>
    </br>
    <p>bcrypt 사용 이유</p>
        <p>- blowfish를 기반으로 hashing 알고리즘을 구현하기 때문에 SHA 알고리즘에 비해 상대적으로 연산 속도가 느려 레인보우 테이블 생성을 방지하는데 효과적이기 때문입니다</p>
    </br>
    <p> 암호화 </p>
    <p>- pbkdf2 </p>
    <p>- bcrypt </p>
    <p>- scypt </p>
    </br>
    - 클라이언트 브라우저 외부에서 웹 애플리케이션을 실행하기 위한 오픈소스 크로스 플랫폼 Javascript 런타임 환경 및 라이브러리이다. 
    </br>
    - npm 은 node.js가 모든 패키지의 모듈을 관리하는 node package manager의 약자이다.
    </br>
    - 참고 : https://nara.dev/til/note/nodejs-interview-preparing.html#_7-node-js%E1%84%82%E1%85%B3%E1%86%AB-%E1%84%8B%E1%85%A5%E1%84%83%E1%85%B5%E1%84%89%E1%85%A5-%E1%84%80%E1%85%A1%E1%84%8C%E1%85%A1%E1%86%BC-%E1%84%8C%E1%85%A1%E1%84%8C%E1%85%AE-%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%83%E1%85%AC%E1%84%82%E1%85%A1
</details>

<details>
<summary>React</summary>
</br>
<p> UI를 효과적으로 구축하기 위해 사용하는 자바스크립트 기반의 라이브러리이다. </p>
특징
<p>- 선언적이다: 대화형 UI를 작성하기가 유리하다. 데이터가 변경되었을 때 효율적으로 렌더링을 수행할 수 있도록 함.</p>
<p>- 컴포넌트 기반이다.: 캡슐화된 컨포넌트가 상태를 관리하고 UI를 효과적으로 구성할 수 있음.</p>
</details>

#### RDBMS 의 세 가지 종류 sqlite, mysql, postgres
<details>
<summary>sqlite</summary>
<p>- 낮은 메모리 환경에서도 이식성, 안정성, 강력한 성능으로 잘 알려진 독립형 파일 기반의 오픈소스 RDBMS입니다.</p>
</details>

<details>
<summary>mysql</summary>
<p>- MySQL은 Oracle Corporation에서 개발 및 배포하는 오픈 소스 DBMS입니다.</p>
</details>

<details>
<summary>postgresql</summary>
<p>- 오픈 소스 객체-관계형 데이터베이스 시스템(ORDBMS) 또는 객체 관계형 데이터베이스이다. </p>
<p>커맨드 사용법</p>
<p>- DB 들어가기: `psql -U kong`</p>
<p>- 테이블 조회: `SELECT * FROM PG_TABLES;`</p>
<p>- 테이블 데이터 조회: `SELECT * FROM services;`</p>
<p>- 나가기: `\q`</p>
<p>- 유저 조회: **`\du`**</p>
<p>- Data 디렉토리 확인: ``show data_directory;`</p>
</details>

<details>
<summary>kubernetes</summary>
<p>한 서버는 Master로 쓰고 다른 서버들은 하나 혹은 여러 개의 Node들이 연결이 연결이 된다. 그리고 이것들을 묶어 한 Cluster(클러스터)가 된다. - Master: 전반적인 기능들을 제어하는 역할이다. - Node: 자원을 제공한다. 만약 클러스터 내의 자원을 늘리고 싶다면 Node들을 늘리면 된다.</p>
<p>컨네이터는 컨테이너 이미지를 만들 수 있는데 그 이미지에는 한 서비스와 한서비스를 돌아가는데 필요한 라이브러리들이 들어있어 한 Container에서 컨테이너 이미지에 라이브러리가 있기 때문에 안정적으로 돌아 갈 수 있다.</p>
</details>

#### 로드밸런서
- 둘 혹은 셋 이상의 중앙처리장치 혹은 저장장치와 같은 컴퓨터 자원들에게 작업을 나누는 것을 의미합니다.

<details>
<summary>nginx</summary>
<p>- 웹서버로 비동기 방식으로 개발되어 가볍고 빠른 것으로 유명한 오픈소스 어플리케이션입니다. 트래픽이 많은 웹 사이트를 위해 네트워크 확장성을 주목적으로 설계한 경량 HTTP 서버로, 리버스 프록시로 활용가능합니다.</p>

```
#add test part
server {
	server_name		localhost;
	listen			6081; #포ㅡ 설정
	listen			192.168.75.149:6081; # haproxy를 받기 위해


	# OCP ocp4 v4.6.17 API Proxy
	location /vnc_auto.html {
		proxy_pass http://192.168.63.100:6080 #해당 url로 넘김.
		proxy_set_header X-Real-IP $remote_addr; 
        
        proxy_http_version 1.1;
		proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
		proxy_set_header Host $http_host;
		proxy_set_header Sec-WebSocket-Protocol $arg_protocol;
		proxy_set_header Upgrade $http_upgrade;
		proxy_set_header Connection $connection_upgrade;
		proxy_set_header Authorization "Bearer $arg_access_token";
		proxy_set_header Origin "*";
	}

}
```
</details>

<details>
<summary>ha proxy</summary>
<p>- L4, L7 과 같은 하드웨어 로드밸런서를 대체하기 위한 오픈소스 소프트웨어로 Reverse Proxy 를 기반으로 로드밸런싱하는 TCP와 HTTP 기반 어플리케이션위해 사용 됩니다</p>

```
frontend api_gateway
    bind *:8881
    acl PATH_aa path_beg -i /aa #접두어가 /aa이면 PATH_aa의 경우로
    acl PATH_bb path_beg -i /bb
    use_backend be_aa if PATH_aa # PATH_aa 이면 be_aa 할당
    use_backend be_bb if PATH_bb
	default_backend be_etc

backend be_aa
    server server1 host.docker.internal:9991 check #server  server2 192.168.60.161:80 check

backend be_bb
    server server1 host.docker.internal:9992 check

backend be_etc
    server server1 host.docker.internal:9993 check
```
</details>

<details>
<summary>kong ingress controller</summary>
<p>- MSA 구성을 가속화하는 오픈 소스 API Gateway입니다</P>
<p>- 컨트롤 플레인 : 배포는 컨트롤러를 실행하는 포드와 DB를 구성할 수 있는 kong 컨테이너로 구성
데이터 플레인: DB에서 로드하는 구성을 기반으로 하는 트래픽을 프록시 할 수 있는 단일 kong 컨테이너를 실행하는 포드로 구성
데이터베이스: kong의 구성을 저장하고 클러스터의 모든 kong 포드 의 변경 사항을 전파하는데 사용.</p>

</details>

<details>
<summary>MSA란?</summary>
<p>- 마이크로 서비스 아키텍처(Micro Service Architecture)의 약자로 단일 프로그램을 각 컴포넌트 별로 나누어 작은 서비스의 조합으로 구축하는 방법</P>
<p>- 각 컴포넌트는 서비스 형태로 구현되고 API를 이용하여 타 서비스와 통신하게 됩니다. 각 서비스는 독립된 서버로 타 컴포넌트와 의존성이 없기 때문에 독립된 배포를 하게 됩니다.</p>
- 각 서비스가 다른 서버에 분리 배포되어있기 때문에 서버 URL이 각기 다를 수 밖에 없습니다.API Gateway는 API 서버 앞 단에서 모든 API 서버들의 End-Point를 단일화하여 묶어주는 역할을 합니다. 라우팅, 로드밸런싱, 인증 역할 등등 여러 역할을 수행합니다.
</details>

<details>
<summary>logstash</summary>
<p>- 다양한 소스로부터 데이터를 수집하고 곧바로 전환하여 원하는 대상에 전송할 수 있도록 하는 경량의 오픈 소스 서버측 데이터 처리 파이프라인입니다.</P>
</details>

<details>
<summary>Axure</summary>
<p>- 애플리케이션, 웹사이트, 모바일앱 등을 제작하기 위해 필요한 정적인 와이어프레임, 인터랙티브한 프로토타입, 플로우 차트, 문서를 만들 때 사용하는 데스크톱 애플리케이션입니다.</P>
</details>

#### UML은 Unified Modeling Language의 약자로 시스템을 모델로 표현해주는 대표적인 모델링 언어입니다. 이것은 구조다이어그램과 행위 다이어그램으로 나누어집니다.

<details>
<summary>클래스 다이어그램</summary>
<p>- 시간에 따라 변하지 않는 시스템의 정적인 면을 보여주는 대표적인 UML 구조 다이어그램으로 시스템을 구성하는 클래스들 사이의 관계를 표현합니다.</P>
<p>- 접근제어자 리스트, 속성, 메서드인 클래스(동일한 속성과 행위를 수행하는 객체의 집합) </P>
</details>

<details>
<summary> deployment 다이어그램</summary>
<p>- 시스템의 소프트웨어와 하드웨어 컴포넌트 간 관계 및 처리의 물리적 분배를 표시합니다. 구현 단계(phase) 중에 준비하는 다이어그램으로 분산 시스템에서 노드의 물리적 배열, 각 노드에 저장되는 아티팩트 및 아티팩트가 구현하는 컴포넌트와 기타 요소를 표시합니다.</P>
<p>- 노드는 시스템의 런타임 환경을 지원하는 기타 장치 뿐 아니라, 컴퓨터, 센서 및 프린터와 같은 하드웨어 장치를 표시합니다. 통신 경로와 배치 관계는 시스템의 연결을 모델링합니다.</P>
</details>

<details>
<summary>use case 다이어그램</summary>
<p>- 시스템과 사용자의 상호작용을 다이어그램으로 표현한 것으로 사용자의 관점에서 시스템의 서비스 혹은 기능 및 그와 관련한 외부 요소를 보여주는 다이어그램입니다.</P>
<p>- 시스템, 액터, 유스케이스, 관계로 이루어져 있습니다.</P>
</details>



<details>
<summary>squence diagram</summary>
<p>- 특정 행동이 어떠한 순서로 어떤 객체와 어떻게 상호작용을 하는지 표현하는 행위 다이어그램입니다. 현재 존재하는 시스템이 어떠한 시나리오로 움직이고 있는지를 나타내는데 장점을 가지고 있습니다</P>
<p>- API 등의 유즈 케이스를 디테일하게 알 수 있고 타 시스템의 API 호출 등의 로직을 모델링할 수 있어 시나리오를 파악하기 좋습니다.</P>
</details>

<details>
<summary>Restful API</summary>
<p>- HTTP 통신에서 어떤 자원에 대한 CRUD 요청을 Resource와 Method로 표현하여 특정한 형태로 전달하는 방식입니다. </P>
<p>- REST란 어떤 자원에 대해 CRUD(Create, Read, Update, Delete) 연산을 수행하기 위해 URI(Resource)로 요청을 보내는 것으로, Get, Post 등의 방식(Method)을 사용하여 요청을 보내며, 요청을 위한 자원은 특정한 형태(Representation of Resource)으로 표현됩니다. 그리고 이러한 REST 기반의 API를 웹으로 구현한 것이 RESTful API
</P>
<p> </P>
</details>

<details>
<summary>HTTP status code</summary>
<p>- HTTP 요청이 성공했는지 실패했는지를 서버에서 알려주는 코드다.
</P>
<p>1xx(정보) : 요청을 받았으며 프로세스를 계속 진행합니다.</P>
<p>101은 클라이언트에 의해 보낸 업그레이드 요청 헤더에 대한 응답으로 보내집니다.</p>
<p>2xx(성공) : 요청을 성공적으로 받았으며 인식했고 수용하였습니다.</P>
<p>200 OK:요청이 성공적으로 되었습니다. 정보는 요청에 따른 응답으로 반환됩니다.</P>
<p>202 Accepted: 요청을 수신하였지만, 그에 응하여 행동할 수 없습니다. </P>
<p>3xx(리다이렉션) : 요청 완료를 위해 추가 작업 조치가 필요합니다.</P>
<p>4xx(클라이언트 오류) : 요청의 문법이 잘못되었거나 요청을 처리할 수 없습니다.</P>
<p>400 Bad Request: 이 응답은 잘못된 문법으로 인하여 서버가 요청하여 이해할 수 없음을 의미합니다.</P>
<p>404 Not Found: 서버는 요청받은 리소스를 찾을 수 없습니다. 브라우저에서는 알려지지 않은 URL을 의미합니다. </P>
<p>5xx(서버 오류) : 서버가 명백히 유효한 요청에 대한 충족을 실패했습니다.</P>
<p> </P>
<p> </P>
<p> </P>
</details>

<details>
<summary>시나리오 description</summary>
<p>505 HTTP Version Not Supported: 서버에서 지원되지 않는 HTTP 버전을 클라이언트가 요청하였습니다.</P>
</details>

## 논문 혹은 프로젝트 관련 질문과 설명 (+ 기술 소개, 왜 그 기술을 사용했는지)
- ‘AI & 빅데이터 기반 어린이 맟춤형 성장 프로그램’ 아이디어 기획 
    - 코로나 19에 어린이들이 집에만 있게 되면서 줄어든 운동량과 불규칙한 식습관을 개선시키기 위해 성장하고 아파하는 가상 캐릭터를 보면서 스스로 흥미를 느끼고 고칠 수 있도록 돕는 애플리케이션 서비스 (부모님과 어린이가 모두가 성장할 수 있는 쌍방향 플랫폼.)
    - 미션은 식생활과 운동으로 나누져 '식생활교육지원법'의 바른 식생활 개념인 건강, 배려 그리고 환경에 운동이라는 단어를 바른 식사, 바른 행동 그리고 바른 운동이라고 재 정의하여 제공됩니다.- 미션 데이터는 신뢰성있는 서비스를 위해 한국영양학회에서 개발한 지수인 NQ-C, 한국인의 식생활 지침에 포함된 지수인 KDAGCAI와 학생건강체력 평가제도인 팝스와 3학년부터 6학년까지의 지학사 체육 교과서를 바탕

- ‘동화를 이용한 코딩 교육 플랫폼’ 제작 
    - 코딩 교육은 개미와 베짱이, 신데렐라, 견우와 직녀, 알라딘, 헨젤과 그레텔 등 유명한 전래 동화를 이용한 코딩 교육 콘텐츠를 제작한다.
    - 마이크로 비트란?
    - Nodejs
    - react js
    - mysql

- ‘Edge RSU을 통한 V2I 통신시스템 구현 및 최적경로 탐색’ 연구 진행 
    - Edge 서버인 RSU가 실시간 교통정보와 도로 위 이상현상을 수집, 분석하여 Edge 기기인 OBU에게 Astar 알고리즘을 이용하여 최적 경로와 도로 정보를 제공하는 V2I 통신시스템을 구현했다.
    - RSU
    - OBU

<details>
<summary>greengress Iot</summary>
<p> </P>
</details>

    - Edge Computing
    - Cloud Computing
    - sqlite
    - mysql과 sqlite 차이
    - mqtt
    - wave 통신 관련 이유
- ‘AI CCTV를 활용한 '실시간 차량사고와 도로장애물 알림모델’ 제작 
    - AI CCTV가 도로 위 이상 현상(교통사고, 장애물)을 감지하여 짧은 시간 내에 주변의 사용자에게 이상 현상 알림을 전달 함으로써 교통체증과 2차 교통사고 발생을 방지하는 시스템을 구축하는 서비스이다
    - Axure
    - Figma
    - yolo v4
    - 왜 yolo 선택
    - 테스트 비율
    - FCM
    - django 선택이유
- ‘얼굴인식을 이용한 애플리케이션 도어락’ 제작 
    - 사용자는 앱을 통해 사진을 찍으면, 미리 학습시켜놓은 사진 모델과 비교해 도어락을 해제시키는 서비스이다
    - opencv
    - socket
    - raspberry pi
    - 코틀린
- 인재 INC
    - openstack
    - openshift
    - minikube
    - ELK 연결
    - kubernetes 설치 과정
    - harbor
    - keycloak
    - kong 
    - kubernetes vs docker
    - SM5
- 사피엔스
    - 오조봇
    - 코두
    - 스파이크 프라임
