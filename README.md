# 김건훈

안녕하세요! Back-End 개발자 김건훈입니다.🙇🏻‍♂️

JS 생태계를 좋아하고 System Architechure에 관심이 있습니다.

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
### 🤪Coming Soon..!

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
- 정보
    - 2021 Junction X Seoul AWS GameTech 1st 프로젝트
        - [발표영상](https://drive.google.com/file/d/1xYeWnZrA0f2nwBu2Au5TtnWR5c8HUTUi/view?usp=sharing)
        - [발표자료](./asset/Hippy_Gamp.pdf)
    - LoL Voice의 완성형 프로젝트
- 서비스 설명
    - 음성 채팅 서비스가 없는 게임에서 게임이 시작하면 팀원들과 자동으로 음성 매칭을 해주는 서비스
        - 데모에서는 League of Legends(이하 lol)
    - WebRTC와 AWS Chime을 활용한 서비스
    - 개인 프로젝트 중 [LoL Voice](#lol-voice) 개선 작품
- 기간
    - 2021.05.21. ~ 2021.05.23.
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
- 정보
    - 2021 프로젝트 블루아워 우리은행 온택트 해커톤 장려상
    - NFT 현금 거래 플랫폼
        - NFT를 생성하고 거래할 수 있는 기능이 있습니다.
        - NFT를 거래할 때 생기는 수수료를 예측하여 코인 거래가 아닌 현금 거래가 가능하도록 했습니다.
- 서비스 설명
    - NFT를 생성하고 거래할 수 있습니다.
    - NFT 거래 시 발생하는 ETH 수수료를 추정한 뒤 현금 거래가 가능하도록 구현했습니다.
- 기간
    - 2021.04.30. ~ 2021.05.03.
- 역할
    - solidity를 활용한 스마트 컨트랙트 구축
        - NFT를 생성하고 거래할 수 있도록 [truffle suite](https://www.trufflesuite.com/)를 사용해 스마트 컨트랙트를 구현했습니다.
        - [Ganache](https://www.trufflesuite.com/ganache)를 통해 가상 이더리움 거래 환경에서 개발했습니다.
        - [Web3](https://github.com/ChainSafe/web3.js)를 활용하여 거래 수수료를 추정했습니다.
    - 우리은행 API를 활용해 금융 거래 API 개발

### [EC Promotion](https://github.com/EndlessCreation/ec_homepage_spring)
- 서비스 설명
    - 교내 학술 동아리 Endless Creation 홍보 목적으로 제작한 홈페이지입니다.
    - www.endlesscreation.kr
- 기간
    - 2021.03 ~ 2021.03
- 역할
    - 스프링 5 스터디
        - 개발 전 진행한 Spring 5 스터디를 통해 Dispatcher-Servlet, IoC Container에 대한 이해를 했습니다.
    - Spring Boot와 JPA를 활용한 Web API 개발
        - Spring에 대한 개념 이해 및 스터디한 내용을 토대로 간단한 개발을 진행해보며 Spring의 맛을 봤습니다.
        - Spring Boot와 JPA에 대한 사용 경험을 쌓았습니다.

### [습관빵](https://github.com/prography/6th-habitbread-node)
- 서비스 설명
    - 프로그라피 6기 팀원들과 개발한 좋은 습관을 만들고 싶은 사용자들에게 도움을 주는 모바일 앱 서비스입니다.
- 기간
    - 2020.04 ~ 2020.12
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
- 정보
    - Naver AI Burning Day 본선 진출 작품입니다.
- 서비스 설명
    - 노인을 위한 실시간 음성 챗봇 키오스크입니다.
- 기간
    - 2020.04 ~ 2020.12

### WeAreHere
### LoL Voice