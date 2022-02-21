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

<details>
<summary>nginx</summary>
<p> </p>
<p> </p>


<details>
<summary>ha proxy</summary>
<p> </p>
<p> </p>

<details>
<summary>kong ingress controller</summary>

<details>
<summary>logstash</summary>

<details>
<summary>centos 와 ubuntu</summary>

<details>
<summary>greengress Iot</summary>

<details>
<summary>Axure</summary>

<details>
- 클래스 다이어그램</summary>

<details>
- use case 다이어그램</summary>

<details>
- squence diagram</summary>

<details>
- 시나리오 description</summary>

<details>
- HTTP status code</summary>

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
    - 왜 greengrass Iot
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
