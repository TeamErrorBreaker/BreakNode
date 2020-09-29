# Spring Boot / Node.js

> 마지막 파이널 프로젝트를 하며 RESTful API 와 자바스크립트에 대한 중요성을 뼈저리게 느꼈다. 
우리가 정말 구현하고자 하는 기능들은 모두 비동기에 의해 구현해야 했고, 이 부분을 명확히 해결하려면 통신 프로토콜에 대한 이해와 이를 활용할 수 있는 Front-End 영역의 지식도 필요하다고 느꼈다.

Full-Stack 개발자로 향하는 것을 목표로 한다!

### 목표

- 요즘 자바 프로그래머라면 필수인 Spring Boot 와 JPA 그리고 Node.js 까지 공부하여 Full-Stack 개발자로 향한 한 걸음 한 걸음!
- 학원에서 배운 내용을 바탕으로 하여 새로운 기술에 접목 시킨 후 우리들의 작은 토이 프로젝트를 만들어 보자! 
***(ex. Github 를 이용한 포트폴리오 사이트 제작 / 웹 소캣을 이용한 웹 챗 구현 등 아이디어 제공해주세요!)***

### 계획

- 일정 : 매주 화 / 수 중 하루, 대략 15:00 ~ 16:00 (약 2시간 진행 예정)
- 기간 : 약 7주 과정 예상
- 만남의 목적 : 한 주에 얼만큼 새로운 기술에 대해 공부 했는지, 해당 기술의 코어 기술은 무엇인지 토론하고 토이 프로젝트를 어떻게 진행할 것인지 회의하는 시간을 가질 예정입니다.

### 스터디 진행 방향

- **[<Node.js 교과서>](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&barcode=9791160505221)** 를 바탕으로 Node.js  공부
    - 1장부터 6장까지를 목표 (MySQL 이전)

    [Node.js 교과서 - 교보문고](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791165212308&orderClick=LEA&Kc=)

- **[Youtube 백기선 님의  Spring Boot 강좌](https://www.youtube.com/watch?v=CnmTCMRTbxo&list=PLfI752FpVCS8tDT1QEYwcXmkKDz-_6nm3)** 를 활용하여 Spring Boot 의 개념과 코어 개념에 대한 공부

    [https://www.youtube.com/watch?v=CnmTCMRTbxo&list=PLfI752FpVCS8tDT1QEYwcXmkKDz-_6nm3&index=1](https://www.youtube.com/watch?v=CnmTCMRTbxo&list=PLfI752FpVCS8tDT1QEYwcXmkKDz-_6nm3&index=1)

    - 해당 영상은 대략적인 개념에 대해 훑는 영상 같습니다. ~~*더 자세한 강의는 인프런에 백기선님의 강의가 있는데 비용이 만만치 않군요..!*~~
    - 총 40개의 영상, 약 40시간 정도 →18강까지 라도 완독하는 것을 목표로 한다.
- 위의 내용을 바탕으로 개인 포트폴리오 사이트 제작이든 Node.js 교과서에 있는 프로젝트를 조금 더 발전시키는 방향으로 하나의 프로젝트를 진행할 예정!

‼️이미 충분히 알고 있는 내용이라면 패스해도 괜찮습니다!

### 계획표

1. **1주차**
    - 🦖Node.js :  1 ~ 2장 내용 공부
        - 1장 : Node 시작하기
        - 2장 : 알아두어야 할 자바스크립트
    - 🍃Spring Boot :   1강 ~ 3강 영상 시청 후 실습 해보기
        1. 스프링 부트 시작하기
        2. Executable JAR 어떻게 만들고 동작하는가
        3. Spring Boot Starter
2. **2주차**
    - 🦖Node.js : 3장 내용 공부
        - 3장 : 노드 기능 알아보기
    - 🍃Spring Boot : 4강 ~ 7강 영상 시청 후 실습 해보기
        1. @SpringBootApplication / XML 빈 설정 파일 사용하기
        2. spring-boot-devtools 그리고 릴로딩
        3. 배너 그리고 SpringApplication
        4. SpringApplication 커스터마이징과 Admin 기능(MBeans)
3. **3주차**
    - 🦖Node.js : 4 ~ 5장 내용 공부
        1. http 모듈로 서버 만들기
        2. 패키지 매니저
    - 🍃Spring Boot : 8강 ~ 10강 영상 시청 후 실습 해보기
        1. 프로퍼티와 각종 외부 설정의 우선 순위
        2. YAML 사용하기
        3. @ConfigurationProperties 의 여러 장점과 유일한 단점
4. 4**주차**
    - 🦖Node.js : 6장 내용 공부
        1. 익스프레스 웹 서버 만들기
    - 🍃Spring Boot : 11강 ~ 14강 영상 시청 후 실습 해보기
        1. 스프링 프로파일과 스프링 부트 기본 로깅
        2. 커스텀 로그 설정 제공하기와 logback 에서 스프링 프로파일 사용하기
        3. 웹 애플리케이션 그리고 HttpMessageConverters
        4. HttpMessageConverters 부가 설명 그리고 Static 리소스 맵핑과 위치 변경
    - 프로젝트 회의
        - 주제 설정 및 2주간 계획 설계
5. 5**주차**
    - 🦖Node.js : 10장 내용 공부
        1. 웹 API 서버 만들기
    - 🍃Spring Boot : 15강 ~ 18강 영상 시청 후 실습 해보기
        1. WebJar 그리고 컨텐츠 협상
        2. DataBinder, Template Engine, Error Handling
        3. Converter 등록하기 및 Error Handling 그리고 Hateoas
        4. CORES 로 웹 MVC 마무리 그리고 아티클 하나 
    - 프로젝트 진행
6. 6**주차**
    - 🦖Node.js : 12장 내용 공부
        1. 웹 소켓으로 실시간 데이터 전송하기
    - 🍃Spring Boot : 23강 ~ 25강 영상 시청 후 실습 해보기
        1. 스프링 웹플럭스
        2. 스프링 웹플럭스와 타임 리프
        3. 웹플럭스 마무리와 내장 컨테이너 커스터마이징
    - 프로젝트 진행
7. **7주차**
    - 🦖Node.js : 전반적인 개념 정리하기
    - 🍃Spring Boot : 전반적인 개념 정리하기
    - 프로젝트 진행 및 마무리 진행

---
