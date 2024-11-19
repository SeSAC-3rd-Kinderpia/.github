# 킨더피아(Kinderpia)
<br />

## 서비스 소개

## 팀원 구성

## 개발 일정

## 개발 환경 및 기술 스택

## 프로젝트 설계

- [요구분석 정의서/명세서](https://docs.google.com/spreadsheets/d/1gSM3U5_iIPCi3uZO0OA2bNrZaqUr0ofMC7ZDPXP2jQE/edit?usp=sharing)
- [테이블 명세서](https://docs.google.com/spreadsheets/d/18Qe6gyXHZGjYSOT_aBlw2B_aoWGzkUCpWcnQP_UIWB0/edit?gid=0#gid=0)
- [DB 설계](https://www.erdcloud.com/d/3WZ38QnZe9BXJywD9)
- [화면 설계]
- [명명법](https://docs.google.com/spreadsheets/d/1PZu6fUjUPuSyrVNv09v6w6CyTfszG57dqVE4vMwtHkw/edit?gid=257359927#gid=257359927)

<br/>

## 시스템 아키텍처
![image](https://github.com/user-attachments/assets/9298e6e9-9c3b-4f7e-aa16-00785c6ddfab)


## 데이터베이스 ERD (주요 테이블)
![image](https://github.com/user-attachments/assets/ca384d30-35e7-40ef-86b2-0adc12ff25e9)

## 커밋 컨벤션

## 프로젝트 구조

src
 └── main
     ├── java
     │   └── sesac_3rd
     │       └── sesac_3rd
     │           ├── Sesac3rdApplication.java
     │           ├── config               // 설정 파일 (JWT, 보안 설정 등)
     │           ├── constant          // 상수 관리 (ex: 상태 값)
     │           ├── controller        // 컨트롤러 계층
     │           ├── dto                   // 데이터 전송 객체 (DTO)
     │           ├── entity               // 엔티티 클래스
     │           ├── exception        // 예외 처리
     │           ├── handler           // 핸들러 클래스
     │           ├── mapper           // 매퍼 (DTO <-> 엔티티 변환)
     │           ├── repository       // 데이터 접근 레이어
     │           ├── service             // 서비스 계층
     │           └── utils                    // 유틸리티 클래스 (ex: S3 관리)
     └── resources
         ├── application.properties
         ├── data.sql
         └── static
             └── index2.html


## 역할 분담

## 주요 기능

## 소감
