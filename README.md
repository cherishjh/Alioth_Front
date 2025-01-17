# 🌟 Alioth - 영업 관리 시스템

<p align="center">
  <img src="docs/Alioth표지.png"/>
<br>


**Alioth**는 효율적인 영업 관리를 지원하는 시스템으로, 조직 내 협업, 데이터 통합, 성과 관리를 위한 강력한 도구를 제공합니다.  
이 프로젝트는 고객 데이터 관리부터 매출 실적 분석까지 다양한 기능을 포함하여 현대적인 영업 관리를 지원합니다.

#### GitHub Link

* [Back-End](https://github.com/lemony1122/Alioth-Back)
* [Front-End](https://github.com/lemony1122/Alioth-Front)


<br>

## 📚 목차
>📝 [프로젝트 개요](#-프로젝트-개요)\
👾 [팀원 소개](#-팀원-소개)\
🧑‍💻 [팀원 역할](#-팀원-역할)\
🛠️ [사용 기술](#-사용-기술)\
🚀 [기능](#-기능)\
🖥️ [시스템 아키텍처](#-시스템-아키텍처)\
📑 [참고 자료](#-참고-자료)\
📂 [File Link](#-file-link)

<br>

## 📝 프로젝트 개요


<p align="center">
  <img src="docs/Alioth개요1.png"/>
  <img src="docs/Alioth개요2.png"/>
</p>

- **프로젝트 기간**: 2024-03-14 ~ 2024-05-09
- **주제**: 영업 관리 시스템 개발
- **목표**:
    - **조직 관리**: 효율적인 인력 및 성과 관리
    - **일정 관리**: 영업 활동의 체계적인 계획
    - **매출 관리**: 매출 및 계약 데이터 분석

<br>

## 👾 팀원 소개

<div align="center">

|                                                                         박성준                                                                          |                                                                         조경남                                                                          |                                                                         조훈                                                                          |                                                                         한희준                                                                          |
|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|
| <img src="https://avatars.githubusercontent.com/u/56985486?v=4" height="150" width="150"> <br> [@J-unStiN](https://github.com/J-unStiN) | <img src="https://avatars.githubusercontent.com/u/63902992?v=4" height="150" width="150"> <br> [@GyeongNam](https://github.com/GyeongNam) | <img src="https://avatars.githubusercontent.com/u/142702766?v=4" height="150" width="150"> <br> [@hoonjo123](https://github.com/hoonjo123) | <img src="https://avatars.githubusercontent.com/u/139551676?v=4" height="150" width="150"> <br> [@lemony1122](https://github.com/lemony1122) |

</div>

<br>

## 🧑‍💻 팀원 역할


- **박성준**
    - **기획**: 요구사항 명세서, 인터페이스 설계서, TDD 기획
    - **백엔드**: 로그인 서비스, 통계 서비스, 팀 개발 백업
    - **프론트**: 사용자 관련 페이지(로그인, 마이페이지)
    - **배포**: AWS S3(이미지 관리), ECR


- **조경남**
    - **기획**: 요구사항 명세서, 인터페이스 설계서, WBS 작성
    - **백엔드**: 캘린더 서비스, 게시판 서비스, 팀 개발 백업
    - **프론트**: 캘린더 서비스, 팀 개발 백업
    - **배포**: AWS EKS, GitHub Actions


- **조훈**
    - **기획**: 요구사항 명세서, 인터페이스 설계서, 단위 테스트 명세서
    - **백엔드**: FCM 알림 서비스, 아마존 SNS, 계약 관리 서비스
    - **프론트**: 알림 관련 헤더, 게시판, 계약 관련 페이지


- **한희준**
    - **기획**: 요구사항 명세서, 인터페이스 설계서
    - **백엔드**: 사원 관리 서비스, 팀 관리 서비스, 엑셀 다운로드 서비스
    - **프론트**: 레이아웃, 사원 관련 페이지, 팀 관련 페이지


<br>

## 🛠️ 사용 기술

### Back-End
![Java 21](https://img.shields.io/badge/Java_21-007396?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Batch](https://img.shields.io/badge/Spring_Batch-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)

### Front-End
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=white)

### DB
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Infra
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![AWS_EKS](https://img.shields.io/badge/AWS_EKS-1C1D21?style=for-the-badge&logo=amazonekseks&logoColor=white)
![AWS_ECR](https://img.shields.io/badge/AWS_ECR-FF6600?style=for-the-badge&logo=amazonecr&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)
![AWS CloudFront](https://img.shields.io/badge/AWS_CloudFront-FF8C00?style=for-the-badge&logo=amazoncloudwatch&logoColor=white)
![AWS IAM](https://img.shields.io/badge/AWS_IAM-FF9900?style=for-the-badge&logo=amazoniam&logoColor=white)
![AWS Route 53](https://img.shields.io/badge/AWS_Route_53-006FBB?style=for-the-badge&logo=amazonroute53&logoColor=white)

### CI/CD
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

### Tools
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC.svg?&style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)



<br>

## 🚀 기능


### 1. 조직 관리 서비스

<br>

#### 🏢 본사
- **전사 사원 고객 평가 및 직원 관리**
    - 모든 직원의 고객 평가 데이터를 관리하고 이를 바탕으로 직원 관리를 수행합니다.

- **팀 정보 관리**
    - 회사 내 팀 구성 정보 등록, 수정, 삭제 기능 제공.

- **팀원 및 팀원 배정**
    - 각 팀의 직원 조회 및 팀 배정 관리.

- **공지사항 관리**
    - 회사 내부 공지사항 작성, 배포, 수정, 삭제 가능.

- **전사 사원 건의사항 관리**
    - 직원들이 제출한 건의사항을 한눈에 확인하고 관리.

- **팀 고객 평가**
    - 각 팀에서 제공받은 고객 평가 데이터를 수집하고 관리.

- **개인 건의사항 등록**
    - 직원 개인이 건의사항을 등록할 수 있는 기능.

- **개인 정보 조회**
    - 직원 개인 정보를 조회하고 필요한 데이터 확인.

- **공지사항 조회**
    - 등록된 공지사항을 조회하여 필요한 정보를 확인.

<br>

#### 🌍 지점장
- **팀원 고객 평가 및 관련 부여**
    - 팀원들이 받은 고객 평가 확인 및 관련 권한 할당.

- **팀 정보 조회**
    - 팀 관련 정보를 열람하여 팀 구성 및 활동 확인.

- **팀원 배정**
    - 팀원 배정 추가/수정 기능 제공.

- **공지사항 관리**
    - 지점 내 공지사항 작성, 수정, 삭제.

- **팀원 건의사항 관리**
    - 팀원들이 제출한 건의사항 확인 및 조치.

- **개인 건의사항 등록**
    - 지점장이 본인의 건의사항 등록.

- **개인 정보 조회**
    - 지점장 개인의 정보 확인 및 관리.

- **공지사항 조회**
    - 전체 공지사항을 열람하고 필요한 정보 확인.

<br>

#### 💼 영업 사원
- **개인 건의사항 등록**
    - 영업 사원이 본인의 건의사항 등록.

- **개인 정보 조회**
    - 영업 사원이 자신의 개인 정보 열람 및 수정.

- **공지사항 조회**
    - 회사나 지점에서 등록한 공지사항 확인.

<br>

---

### 2. 일정 관리 서비스

<br>

#### 🏢 본사
- **전사 일정 조회**
    - 전사적으로 공유된 일정을 확인.

- **팀 일정 조회**
    - 특정 팀의 일정을 열람하고 관리.

- **개인 일정 관리**
    - 본사 직원들이 개인 일정을 등록, 수정, 삭제.

<br>

#### 🌍 지점장
- **팀 일정 조회**
    - 담당 지점 내 팀 일정 열람.

- **개인 일정 관리**
    - 지점장이 본인의 일정 등록, 수정, 삭제.

<br>
    
#### 💼 영업 사원
- **개인 일정 관리**
    - 영업 사원이 자신의 일정을 추가하고 관리.

<br>

---

### 3. 매출 관리 서비스

<br>

#### 🏢 본사

- **전사 계약 관리**
    - 회사 전체 계약 내용을 관리.

- **팀 계약 관리**
    - 특정 팀 계약 정보 조회 및 작업 수행.

- **개인 계약 관리**
    - 본사 직원이 본인의 계약 내용을 관리.

- **전사 매출 실적 조회**
    - 회사 전체 매출 실적 데이터 확인.

- **팀 매출 실적 조회**
    - 특정 팀의 매출 실적 확인 및 분석.

- **개인 매출 실적 조회**
    - 개인 매출 실적 조회 및 확인.

- **전사 매출 목표 관리**
    - 회사 차원에서 설정한 매출 목표 관리.

- **팀 매출 목표 관리**
    - 팀 단위 매출 목표 관리.

- **개인 매출 목표 관리**
    - 개인 매출 목표 추가, 수정 및 확인.

- **기간별 전사 매출 실적 순위**
    - 기간별로 집계된 회사 매출 실적 순위 확인.

<br>

#### 🌍 지점장
- **팀 계약 관리**
    - 지점 내 특정 팀 계약 정보 조회 및 관리.

- **개인 계약 관리**
    - 지점장이 본인의 계약 내용을 관리.

- **기간별 전사 매출 실적 순위**
    - 기간별 매출 실적 순위 열람.

- **팀 매출 실적 조회**
    - 팀별 매출 실적 데이터 확인.

- **개인 매출 실적 조회**
    - 지점장이 개인 매출 실적 확인.

- **팀 매출 목표 관리**
    - 팀 단위 매출 목표 관리.

<br>

#### 💼 영업 사원
- **개인 계약 관리**
    - 영업 사원이 본인의 계약 정보 관리.

- **기간별 전사 매출 실적 순위**
    - 회사 전체 매출 실적 순위 열람.

- **개인 매출 실적 조회**
    - 영업 사원이 본인의 매출 실적 데이터 조회.



<br>

## 🖥️ 시스템 아키텍처

<p align="center">
  <img src="docs/Alioth배포.png"/>
</p>

- **서버 구성**:
    - 2개의 애플리케이션 서버
    - RDB (MariaDB) 및 Redis 기반 데이터 처리
- **배포 환경**: AWS를 활용한 클라우드 배포

### 📊 ERD
<p align="center">
  <img src="docs/AliothERD.png"/>
</p>

### 🔄 플로우차트
<p align="center">
  <img src="docs/AliothFlowChart.png"/>
</p>

<br>

## 📑 참고 자료
- [스프링 배치 공식 문서](https://docs.spring.io/spring-batch/docs/current/reference/html/)
- [AWS EKS 공식 문서](https://aws.amazon.com/eks/)
- [Spring Boot 공식 문서](https://spring.io/projects/spring-boot)
- [Vue.js 공식 문서](https://vuejs.org/)
- [MariaDB 공식 문서](https://mariadb.org/)
- [Redis 공식 문서](https://redis.io/)
- [GitHub Actions 공식 문서](https://docs.github.com/en/actions)

<br>

## 📂 File Link
* [GitHub Repository](https://github.com/beyond-sw-camp/be03-fin-6team-Alioth)
* [Alioth 요구사항 정의서](/docs/Alioth.xlsx-요구사항정의서.pdf)
* [Alioth WBS](/docs/Alioth.xlsx-WBS.pdf)
* [Alioth Api 명세서](/docs/Alioth.xlsx-api명세서.pdf)
* [Alioth UI/UX](/docs/ALIOTH_2024.04.24_UI_UX.pdf)
* [Alioth 단위테스트 명세서](/docs/Alioth.xlsx-단위테스트명세서.pdf)
* [Alioth 발표 자료](/docs/Alioth.pptx)
* [Alioth 시연 영상](/docs/시연%20영상.mp4)
