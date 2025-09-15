# Findex - team9
Findex는 외부 Open API와 연동하여 금융 지수 데이터를 제공하는 대시보드 서비스입니다.
사용자는 직관적인 UI에서 금융 지수의 흐름을 파악하고, 자동 연동 기능을 통해 최신 데이터를 분석할 수 있습니다. 지수별 성과 분석, 이동평균선 계산, 자동 데이터 업데이트 기능을 통해 가볍고 강력한 금융 분석 도구를 경험해 보세요! 📈📊

## 🔍 프로젝트 개요
- **프로젝트 기간**: 2025.9.8 ~ 2025.9.
- **목표**: 사용자가 지수 정보를 쉽고 직관적으로 조회할 수 있도록 필터링, 정렬, 커서 기반 페이지네이션을 지원하는 안정적인 API를 개발하고, 이를 통해 사용자가 원하는 지수 정보를 빠르고 정확하게 확인할 수 있도록 기능을 구현합니다.
- [코드잇 프로젝트1 노션 페이지](https://misty-aardvark-f86.notion.site/1-26719446708e803a8a05c25e42ecf0bc?pvs=74)

## 🧑‍💻 팀원 소개
|                                   팀장                                   |                                   팀원                                    |                                   팀원                                   |                                   팀원                                    |
| :--------------------------------------------------------------------------: | :---------------------------------------------------------------------------: | :--------------------------------------------------------------------------: | :--------------------------------------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/96522559?v=4" width="100"> | <img src="https://avatars.githubusercontent.com/u/77165598?v=4" width="100"> | <img src="https://avatars.githubusercontent.com/u/217873189?v=4" width="100"> | <img src="https://avatars.githubusercontent.com/u/91006942?v=4" width="100"> |
|                    [정기주](https://github.com/jeonggiju)                     |                    [권지인](https://github.com/kjn4101)                     |                      [김수연](https://github.com/sooyeonz)                      |                   [김찬혁](https://github.com/chanhyeok0201)                 |


## ⚙️ 기술 스택
<div align=left> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>

## 📍 주요 기능

### 📋 대시보드
- **실시간 모니터링**: 주요 지수 현황 요약 및 통계 차트
- **맞춤형 구성**: 사용자 맞춤형 지수 선택 및 대시보드 구성
- **시각화**: 직관적인 차트를 통한 데이터 분석

### 📊 지수 정보 관리
- **지수 CRUD**: 지수 등록/수정/삭제 및 Open API 연동
- **데이터 검증**: 지수별 중복 방지 및 초기값 자동 설정
- **종합 관리**: 다양한 연동 설정을 통한 통합 관리

### 📈 지수 데이터 관리
- **데이터 CRUD**: 지수 데이터 등록/수정/삭제/조회
- **파일 업로드**: CSV 파일 업로드 지원
- **자동 등록**: Open API를 통한 실시간 데이터 수집

### 🔗 연동 및 자동화
- **API 연동**: Open API를 통한 지수/데이터 자동 등록
- **배치 처리**: 스케줄러를 활용한 주기적 데이터 갱신
- **외부 연동**: 다양한 외부 시스템과의 연동 지원

### ⚙️ 공통 기능
- **효율적 조회**: 커서 기반 페이지네이션 및 복잡 검색 조건 지원
- **데이터 검증**: 데이터 유효성 검증 및 무결성 보장
- **API 지원**: RESTful API를 통한 외부 시스템 연동

### 🕐 시스템 관리
- **스케줄 관리**: 배치 주기 설정 및 예약 로그 조회
- **트랜잭션**: 안전한 트랜잭션 처리 및 롤백 지원
- **로깅**: CASCADE 처리 및 상세 로그 기록

## 🧩 팀원별 구현 기능 상세
| 팀원 | 구현 기능 |
|------|----------|
| 정기주 | 지수 정보 관리 API|
| 권지인 | 지수 데이터 관리 API, 연동 API |
| 김수연 | 지수 데이터 관리 API, 연동 API |
| 김찬혁 | 자동 연결 설정 API |

### 🟦 정기주  
<img width="800" alt="정기주 작업 화면" src="https://github.com/user-attachments/assets/5677fec2-9673-45a8-bde3-655607b21533" />

- **지수 정보 관리 API**
  - 지수 메타정보 생성/조회/검색
  - 인덱스명/분류/상태 기반 필터 & 정렬

---

### 🟩 권지인  

| ![권지인 작업1](https://github.com/user-attachments/assets/045f1028-637e-442a-8fa0-0a980e8b76fe) | ![권지인 작업2](https://github.com/user-attachments/assets/a64f1e3e-0545-49a9-a556-e117fe691d17) |
| --- | --- |

- **지수 데이터 관리 API**
  - 메인 페이지에서 전체 지수 데이터를 무한 스크롤 기반 커서 페이지네이션으로 조회 및 필터링 검색
  - 사용자가 직접 지수 데이터 생성 가능
  - 대시보드 상에서 지수별 차트 데이터 조회 및 지수의 기간별 성과 TOP10 조회
  - 인덱스명/분류/상태 기반 필터링 & 정렬  
- **연동 작업 API**
  - 연동 이력 목록을 무한 스크롤 기반 커서 페이지네이션으로 조회 및 필터링 검색

---

### 🟨 김수연  

| ![김수연 작업1](https://github.com/user-attachments/assets/c0075011-e86f-447c-a6bf-51c2d7ca86e1) | ![김수연 작업2](https://github.com/user-attachments/assets/0b31ba34-ba54-451e-9fc9-c6cd0aca7a97) |
| --- | --- |

- **지수 데이터 관리 API**
  - 지수 데이터 삭제/수정
  - 관심 지수 성과 조회
  - 지수 데이터 CSV export (바이트 스트림 사용)
- **연동 작업 API**
  - 지수 정보 연동
  - 지수 데이터 연동
- **Open API parsing**
  - 성능 향상을 위해 배치 처리와 복합 조건으로 DB 조회

### 🟥 김찬혁  
<img width="800" alt="김찬혁 작업 화면" src="https://github.com/user-attachments/assets/30b3355d-e4f1-4634-adc7-5608ef9fd2be" />

- **자동 연동 설정 API**
  - 지수별 enabled 토글로 자동 동기화 대상 관리
  - 매일 06:00 KST 스케줄러가 enabled=true인 지수만 동기화
  - **JPA Specification** 기반 필터( indexInfoIdEq / enabledEq / idAfter ) & **커서 페이지네이션**

## 📂 파일 구조
```
 src
   ├─ main
   │  ├─ java
   │  │  └─ com
   │  │     └─ codeit
   │  │        └─ findex
   │  │           ├─ FindexApplication.java
   │  │           ├─ common
   │  │           │  ├─ config
   │  │           │  │  └─ SwaggerConfig.java
   │  │           │  ├─ exception
   │  │           │  │  └─ GlobalExceptionHandler.java
   │  │           │  ├─ openapi
   │  │           │  │  ├─ controller
   │  │           │  │  │  └─ ApiDataInitializer.java
   │  │           │  │  ├─ dto
   │  │           │  │  │  └─ ApiResponseDto.java
   │  │           │  │  └─ service
   │  │           │  │     ├─ ApiIndexDataService.java
   │  │           │  │     └─ ApiIndexInfoService.java
   │  │           │  └─ util
   │  │           │     └─ ApiLoggingAspect.java
   │  │           ├─ indexData
   │  │           │  ├─ controller
   │  │           │  │  ├─ IndexChartController.java
   │  │           │  │  ├─ IndexDataController.java
   │  │           │  │  ├─ IndexDataCsvExportController.java
   │  │           │  │  ├─ IndexDataQueryController.java
   │  │           │  │  ├─ IndexFavoriteController.java
   │  │           │  │  └─ IndexPerformanceController.java
   │  │           │  ├─ domain
   │  │           │  │  ├─ IndexData.java
   │  │           │  │  ├─ PerformancePeriodType.java
   │  │           │  │  └─ PeriodType.java
   │  │           │  ├─ dto
   │  │           │  │  ├─ IndexChartResponse.java
   │  │           │  │  ├─ IndexDataRequestDto.java
   │  │           │  │  ├─ IndexDataResponseDto.java
   │  │           │  │  ├─ IndexDataUpdateRequest.java
   │  │           │  │  ├─ IndexDataUpdateResponse.java
   │  │           │  │  ├─ IndexFavoritePerformance.java
   │  │           │  │  ├─ IndexPerformanceDto.java
   │  │           │  │  └─ IndexPerformanceRankResponse.java
   │  │           │  ├─ repository
   │  │           │  │  └─ IndexDataRepository.java
   │  │           │  └─ service
   │  │           │     ├─ IndexChartService.java
   │  │           │     ├─ IndexDataCsvExportService.java
   │  │           │     ├─ IndexDataQueryService.java
   │  │           │     ├─ IndexDataService.java
   │  │           │     ├─ IndexFavoriteService.java
   │  │           │     └─ IndexPerformanceService.java
   │  │           ├─ indexInfo
   │  │           │  ├─ controller
   │  │           │  │  └─ IndexInfoController.java
   │  │           │  ├─ domain
   │  │           │  │  └─ IndexInfo.java
   │  │           │  ├─ dto
   │  │           │  │  ├─ request
   │  │           │  │  │  ├─ IndexInfoCreateRequestDto.java
   │  │           │  │  │  ├─ IndexInfoGetRequestDto.java
   │  │           │  │  │  └─ IndexInfoUpdateRequestDto.java
   │  │           │  │  └─ response
   │  │           │  │     ├─ IndexInfoCreateResponseDto.java
   │  │           │  │     ├─ IndexInfoGetByIdResponseDto.java
   │  │           │  │     ├─ IndexInfoGetResponseDto.java
   │  │           │  │     ├─ IndexInfoSummaryResponseDto.java
   │  │           │  │     └─ IndexInfoUpdateResponseDto.java
   │  │           │  ├─ mapper
   │  │           │  │  └─ IndexInfoMapper.java
   │  │           │  ├─ repository
   │  │           │  │  └─ IndexInfoRepository.java
   │  │           │  └─ service
   │  │           │     └─ IndexInfoService.java
   │  │           └─ openApi
   │  │              ├─ controller
   │  │              │  ├─ AutoSyncConfigController.java
   │  │              │  └─ SyncJobController.java
   │  │              ├─ domain
   │  │              │  ├─ AutoSyncConfig.java
   │  │              │  └─ SyncJob.java
   │  │              ├─ dto
   │  │              │  ├─ request
   │  │              │  │  ├─ AutoSyncConfigUpdateRequest.java
   │  │              │  │  ├─ AutoSyncConfigDto.java
   │  │              │  │  ├─ IndexDataSyncRequest.java
   │  │              │  │  └─ SyncJobListRequest.java
   │  │              │  └─ response
   │  │              │     ├─ CursorPageResponseAutoSyncConfigDto.java
   │  │              │     ├─ PagedSyncJobResponse.java
   │  │              │     └─ SyncJobResponse.java
   │  │              ├─ mapper
   │  │              │  └─ AutoSyncConfigMapper.java
   │  │              ├─ repository
   │  │              │  ├─ AutoSyncConfigRepository.java
   │  │              │  ├─ DbAdvisoryLockRepository.java
   │  │              │  └─ SyncJobRepository.java
   │  │              ├─ scheduler
   │  │              │  └─ DailyEnabledIndexSyncScheduler.java
   │  │              ├─ service
   │  │              │  ├─ AutoSyncConfigService.java
   │  │              │  ├─ AutoSyncService.java
   │  │              │  ├─ IndexDataSyncService.java
   │  │              │  ├─ SyncJobQueryService.java
   │  │              │  └─ SyncService.java
   │  │              └─ spec
   │  │                 ├─ AutoSyncConfigBackfillRunner.java
   │  │                 ├─ AutoSyncConfigSpecs.java
   │  │                 └─ CursorUtil.java
   │  └─ resources
   │     ├─ application.yml
   │     ├─ application-local.yml
   │     ├─ application-localtest.yml
   │     ├─ application-prod.yml
   │     ├─ sql
   │     │  ├─ Findex.sql
   │     │  └─ dummy.sql
   │     └─ static
   │        ├─ favicon.ico
   │        ├─ index.html
   │        └─ assets
   │           ├─ index-CGZC7fCi.js
   │           └─ index-Dtn62Xmo.css
   └─ test
      └─ java
         └─ com
            └─ codeit
               └─ findex
                  ├─ FindexApplicationTests.java
                  ├─ indexData
                  │  └─ IndexInfoServiceTest.java
                  └─ openApi
                     └─ controller
                        └─ AutoSyncConfigControllerTest.java
```
---

## 📺구현 홈페이지

https://findex-backend-production.up.railway.app/#/index-data

---

## 📑프로젝트 회고록

- 🎥시연 영상

https://drive.google.com/file/d/1ume5g5NSc2rE3w9FmRfSd4_gcy2fIbk2/view?usp=sharing

- 🎬PPT

https://www.canva.com/design/DAGyuWi1Aig/-B1ffzPpD4Wy5oSzuRq03g/edit
