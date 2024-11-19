# 킨더피아(Kinderpia)
<br />

## 서비스 소개

## 팀원 구성

## 🙋 2. Back-End Developers

#### 김어진 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/qldirr)
- 유저, 관리자 관리 시스템 개발

#### 석원준 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ymind14563)
- 채팅, 신고, 파이프라인 자동화 구축
- 서버 배포: AWS (EC2, RDS, S3), NGINX

#### 유예진 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/yjyoo6831)
- 장소 검색, 리뷰 CRUD

#### 윤예슬 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/errorose)
- 모임 관리 시스템 개발

## 개발 일정

## 개발 환경 및 기술 스택

## 프로젝트 설계

- [요구분석 정의서/명세서](https://docs.google.com/spreadsheets/d/1gSM3U5_iIPCi3uZO0OA2bNrZaqUr0ofMC7ZDPXP2jQE/edit?usp=sharing)
- [테이블 명세서](https://docs.google.com/spreadsheets/d/18Qe6gyXHZGjYSOT_aBlw2B_aoWGzkUCpWcnQP_UIWB0/edit?gid=0#gid=0)
- [DB 설계](https://www.erdcloud.com/d/3WZ38QnZe9BXJywD9)
- [화면 설계](https://www.figma.com/design/02t3ifbBDnqWeSDWkBBV3y/sesac-3rd?node-id=17-2&node-type=canvas&t=n7qn5s3rjdVDjdgQ-0)
- [명명법](https://docs.google.com/spreadsheets/d/1PZu6fUjUPuSyrVNv09v6w6CyTfszG57dqVE4vMwtHkw/edit?gid=257359927#gid=257359927)

<br/>

## 시스템 아키텍처
![image](https://github.com/user-attachments/assets/9298e6e9-9c3b-4f7e-aa16-00785c6ddfab)


## 데이터베이스 ERD (주요 테이블)
![image](https://github.com/user-attachments/assets/ca384d30-35e7-40ef-86b2-0adc12ff25e9)

## 커밋 컨벤션

## 프로젝트 구조

```
Kinderpia - Back
src
 └── main
     ├── java
     │   └── sesac_3rd
     │       └── sesac_3rd
     │           ├── Sesac3rdApplication.java
     │           ├── config               // 설정 파일 (JWT, 보안 설정 등)
     │           ├── constant             // 상수 관리 (ex: 상태 값)
     │           ├── controller           // 컨트롤러 계층
     │           ├── dto                  // 데이터 전송 객체 (DTO)
     │           ├── entity               // 엔티티 클래스
     │           ├── exception            // 예외 처리
     │           ├── handler              // 핸들러 클래스
     │           ├── mapper               // 매퍼 (DTO <-> 엔티티 변환)
     │           ├── repository           // 데이터 접근 레이어
     │           ├── service              // 서비스 계층
     │           └── utils                // 유틸리티 클래스 (ex: S3 관리)
     └── resources
         ├── application.properties
         ├── data.sql
         └── static
             └── index2.html
```

## 역할 분담

## 주요 기능

## 소감
