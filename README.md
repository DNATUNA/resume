# 김건훈

![image](https://user-images.githubusercontent.com/28949165/122682976-5d94d000-d237-11eb-9b22-2daee90e881c.png)

안녕하세요! Back-End 개발자 김건훈입니다.🙇🏻‍♂️

JS 생태계를 좋아하고 System Architechure에 관심이 있습니다.

세상을 바꾸는 IT 서비스에 관심이 많습니다.

주로 밤에 많이 활동합니다. 🦉

## Contact
- Email : dnatuna123@gmail.com
- Github : github.com/DNATUNA

## 목차
1. [Work](#work)
2. [Education](#education)
3. [Skill](#skill)
4. [Project](#project)
5. [Activity](#activity)
6. [Prize](#prize)

## Work
### 일자리를 구하고 있습니다^^
### 🤪 Coming Soon..!


## Education
- 서울과학기술대학교 컴퓨터공학과 3학년 재학
    - 2017.03 ~ 2023.02(졸업예정)
- 아름고등학교 졸업

## Skill
- Language
    - JavaScript, TypeScript, C++
- Framework
    - Express, routing-controller
- DB
    - MySQL, Redis
- Container
    - Docker
- Cloud
    - AWS, Naver Cloud Platform


## Project
### [Gamp](https://github.com/junction-hippy)
- 기간
    - 2021.05.21. ~ 2021.05.23.
- 정보
    - 2021 Junction X Seoul AWS GameTech 1st 프로젝트
        - [발표영상](https://drive.google.com/file/d/1xYeWnZrA0f2nwBu2Au5TtnWR5c8HUTUi/view?usp=sharing)
        - [발표자료](./asset/Hippy_Gamp.pdf)
    - [LoL Voice](#lol-voice)의 완성형 프로젝트
- 서비스 설명
    - 음성 채팅 서비스가 없는 게임에서 게임이 시작하면 팀원들과 자동으로 음성 매칭을 해주는 서비스
        - 데모에서는 League of Legends(이하 lol)
    - WebRTC와 AWS Chime을 활용한 서비스
    - 개인 프로젝트 중 [LoL Voice](#lol-voice) 개선 작품
- 역할
    - 미디어 채널링 서버 Serverless로 구현
        - [AWS Demo Open Source](https://github.com/aws-samples/amazon-ivs-chime-web-demo)를 활용하여 미디어 채널링 서버를 [AWS Chime](https://aws.amazon.com/ko/chime/?chime-blog-posts.sort-by=item.additionalFields.createdDate&chime-blog-posts.sort-order=desc)을 사용하여 구축하였고 Lambda와 API Gateway를 사용하여 Severless로 구현했습니다.
        - 서버 빌드는 AWS CloudFormation으로 빌드했습니다.
    - LoL API 사용
        - LoL API를 사용하여 계속 현재 LoL 게임이 계속 플레이 중인지 확인하는 API를 만들었습니다.
            - LoL API와 통신하여 채널링 서버를 관리하는 서버는 Node.js와 Express를 사용해 개발했습니다.
- 차후 개선 사항
    - 추후 클라우드 서비스를 이용하지 않고 [Kurento](https://www.kurento.org/)를 사용해서 직접 채널링 서버를 만들어 볼 예정입니다.

### [Hippy](https://github.com/woori-hippy)
- 기간
    - 2021.04.30. ~ 2021.05.04.
- 정보
    - 2021 프로젝트 블루아워 우리은행 온택트 해커톤 장려상
    - NFT 현금 거래 플랫폼
        - NFT를 생성하고 거래할 수 있는 기능이 있습니다.
        - NFT를 거래할 때 생기는 수수료를 예측하여 코인 거래가 아닌 현금 거래가 가능하도록 했습니다.
- 서비스 설명
    - NFT를 생성하고 거래할 수 있습니다.
    - NFT 거래 시 발생하는 ETH 수수료를 추정한 뒤 현금 거래가 가능하도록 구현했습니다.
- 역할
    - solidity를 활용한 스마트 컨트랙트 구축
        - NFT를 생성하고 거래할 수 있도록 [truffle suite](https://www.trufflesuite.com/)를 사용해 스마트 컨트랙트를 구현했습니다.
        - [Ganache](https://www.trufflesuite.com/ganache)를 통해 가상 이더리움 거래 환경에서 개발했습니다.
        - [Web3](https://github.com/ChainSafe/web3.js)를 활용하여 거래 수수료를 추정했습니다.
    - 우리은행 API를 활용해 금융 거래 API 개발

### [EC Promotion](https://github.com/EndlessCreation/ec_homepage_spring)
- 기간
    - 2021.03 ~ 2021.03
- 서비스 설명
    - 교내 학술 동아리 Endless Creation 홍보 목적으로 제작한 홈페이지입니다.
    - www.endlesscreation.kr
- 역할
    - 스프링 5 스터디
        - 개발 전 진행한 Spring 5 스터디를 통해 Dispatcher-Servlet, IoC Container에 대한 이해를 했습니다.
    - Spring Boot와 JPA를 활용한 Web API 개발
        - Spring에 대한 개념 이해 및 스터디한 내용을 토대로 간단한 개발을 진행해보며 Spring의 맛을 봤습니다.
        - Spring Boot와 JPA에 대한 사용 경험을 쌓았습니다.

### [습관빵](https://github.com/prography/6th-habitbread-node)
- 기간
    - 2020.04 ~ 2020.12
- 서비스 설명
    - 프로그라피 6기 팀원들과 개발한 좋은 습관을 만들고 싶은 사용자들에게 도움을 주는 모바일 앱 서비스입니다.
- 역할
    - Docker와 pm2를 활용해 AWS EC2에 서버 배포 ­ MySQL, redis 서버를 docker로 관리
        - Docker를 사용해 blue-green 무중단 배포를 구현했습니다.
    - Google, Apple OAuth 인증 구현
    - JWT를 통한 Stateless 서버 구축
    - Redis를 캐쉬 메모리로 사용하여 스케줄 및 랭킹 작업 부하 감소
    - Winston과 Sentry를 통한 log 관리
- 차후 개선 사항
    - Redis를 사용하는 것 대신 Message Queue를 사용하면 사용자 별 푸시 메세지 관리를 할 수 있어 차후 프로젝트를 진행할 때는 Message Queue를 사용할 것 입니다.
    - Docker와 pm2 둘 다 로드밸런싱의 매커니즘이 프로세스를 늘리는 방식이라 같이 사용하는 것은 좋지 않아 차후 프로젝트를 진행할 때는 Docker만을 사용하여 배포를 할 것 입니다. 무중단 배포 또한 Docker만을 사용하여 충분히 구현 가능하므로 pm2를 굳이 사용하지 않을 예정입니다.

### [Easy Order Bot](https://github.com/Naver-AI-Burning-Day/server_kiosk)
- 기간
    - 2020.02.13. ~ 2020.02.15.
- 정보
    - Naver AI Burning Day 본선 진출 작품입니다.
- 서비스 설명
    - 노인을 위한 실시간 음성 챗봇 키오스크입니다. 플랫폼은 안드로이드 기반으로 제작되었고 음성으로 조작이 가능하도록 TTS와 챗봇 서비스를 융합했습니다.
- 역할
    - Naver Cloud Platform의 TTS, Chatbot API 연동
        - 3명의 팀원(Android 1명, 서버 1명, 서버 및 디자인 1명)으로 구성된 팀에서 NCP Service를 연동하는 일을 맡아 개발했습니다.
    - 주문 시나리오를 제작한 뒤 Chatbot 학습
        - 간단한 대화 시나리오를 구상한 뒤 이에 맞는 엔티티들을 직접 만들어 학습시켰습니다.

### WeAreHere
- 기간
    - 2019.11 ~ 2019.12
- 서비스 설명
    - 인스타그램의 태그 검색 기능을 모티브로 개발한 웹 쇼핑몰입니다. SNS 느낌의 쇼핑몰이며, 검색 기능은 태그 검색을 기반으로 합니다.
- 역할
    - Express를 사용한 Web API 제작
        - Node.js의 이벤트 루프, 싱글 스레드, 논블로킹 I/O 개념을 학습하며 개발을 진행했습니다.
    - Multer를 이용해 이미지 업로드 기능 구현
    - Passport를 이용해 local login과 Kakao OAuth 인증 구현
        - cookie, session, Oauth 개념을 이해한 뒤 개발을 진행했습니다.
    - Sequelize를 활용해 판매자-게시물1:N, 게시물-태그 N:M 관계 테이블 구축
        - ORM 개념을 이해한 뒤 개발을 진행했습니다.
    - Raw query로 태그 검색 기능 개발
        - ORM의 사용이 미숙했어서 직접 SQL query를 작성했습니다.
    - nodemon을 활용한 개발환경 구축

### LoL Voice
- 기간
    - 2017.07 ~ 2017.11
- 서비스 설명
    - ’리그오브레전드’라는 게임을 즐겨하며 불편했던 사항을 개선해보고자 시작한 프로젝트입니다. 1대1 음성 채팅을 구현한 뒤 테스트할 때의 짜릿함이 저를 개발자의 길로 이끌었던 뜻 깊은 프로젝트입니다.
- 역할
    - Node.js 기반 Express 프레임워크를 사용해 서버 구축
    - WebRTC를 기반으로 한 easyRTC의 데모 코드를 활용해 1대1 음성채팅 기능 구현
    - SQL을 이용한 Login 구현
    - Bootstrap을 이용한 반응형 웹사이트 구현
    - https를 구현을 위해 OpenSSL 및 groom.io의 클라우드 서비스 이용
- 차후 개선 사항
    - P2P 통신을 활용해 다자간 서비스 구축에 실패했습니다. 1:1 대화 구현에서 멈춘 것이 많이 아쉽습니다. 추후 완벽한 서비스 개발을 하여 서비스를 완성시키고자 합니다.


## Activity
### 2021 Junction X Seoul
- 기간 : 2021.05.21. ~ 2021.05.23. (2박 3일)
- 팀원 : Back-End(Express) 2명, Front-End(React) 2명, UI/UX 1명, Entrepeneur 1명
- 성과
    - AWS GameTech 1st
    - 게임 중 팀원들과 실시간 음성 채팅이 가능한 Gamp 서비스 개발

### 2021 우리은행 블루아워 온택트 해커톤
- 기간 : 2021.04.30. ~ 2021.05.04. (4박 5일)
- 팀원 : 서버 개발자 2명, 프론트(react) 개발자 2명
- 성과 : NFT를 활용한 소셜 커머스 플랫폼 Hippy 개발, 장려상

### 교내 학술동아리 Endless Creation 회장 및 Node.js 파트장 활동
- 기간 : 2021.01 ~ 2021.12
- 활동
    - [Endless Creation 홍보 프로젝트 진행](www.endlesscreation.kr)
    - [재학생 스터디 활성화](https://github.com/endlesscreation)
    - [신입 기수 Node.js 6주 스터디 진행](https://github.com/EndlessCreation/nodejs_part_study_2021)
    - 신입 기수 팀 프로젝트(EC:Advance) 지도 및 진행
- 성과
    - 개인 활동 위주였던 동아리를 팀 활동 기반 동아리로 변경

### [Prography 6/6.5기](http://prography.org/)
- 기간 : 2020.04 ~ 2020.12
- 팀원 : Back-End(Express) 2명, Android 2명, iOS 2명, BX 1명
- 활동
    - TypeScript를 사용한 Back-End 환경 구축 스터디 참여
    - 습관빵 서비스 개발 이후 구글 플레이 스토어에 배포(현재는 내렸습니다!)
        - 습관빵 브랜딩 아이디어 제공 및 기획, 개발 단계 참여

### Naver AI Burning Day 본선 진출
- 기간 : 2020.02.13. ~ 2020.02.15. (2박 3일)
- 팀원 : Back-End(Express) 2명, Android 1명
- 성과 : 해커톤 본선 진출

### Django와 ELK를 활용한 로그 분석 서비스 개발 
- 기간 : 2018.06 ~ 2018.12 (5개월 반)
- 팀원 : Back-End(Django + ELK) 1명, ML 1명
- 활동
    - 주식회사 AMIS 산하 팀이었던 솔루션랩스에서 로그 분석 시스템 개발
        - ELK를 활용해 로그를 수집한 뒤 간단한 조건으로 검색할 수 있는 검색 엔진 개발
        - Django와 연동을 통한 Admin 서버 개발
        - 5개월 반 참여

### GCPUG 해커톤 본선 진출
- 기간 : 2018.03.20 ~ 2018.03.21 (1박 2일)
- 팀원 : Back-End 2명, UI/UX 1명, Entrepeneur 1명
- 활동
     - 기획자로써 '범죄율이 높은 구역을 회피하는 Safe Navi' 기획
     - BigQuary의 Chicago Crime Data에서 위도와 경도를 받아와 0.0015*0.0015 구역 사이의 범죄 횟수를 구하는 Query 작성

### 교내 학술동아리 Endless Creation 학술부장 활동
- 기간 : 2018.01 ~ 2018.12
- 활동
    - 신입생들을 대상으로 C언어 기초부터 구조체까지 범위의 세미나 진행
    - 알고리즘 소개 및 문제 풀이
    - 동아리 개인 프로젝트 활동 개최 및 멘토로 활동


## Prize
- __2021 Junction X Seoul AWS GameTech track 1st__
    - 수상일 : 2021.05.23.
- __2021 프로젝트 블루아워 우리은행 온택트 해커톤 장려상__
    - 수상일 : 2021.05.07