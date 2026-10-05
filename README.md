# Wonhee Youn

### 백엔드 개발자 · 9년 차

**커머스와 인플루언서 플랫폼의 설계·구현·운영을 연결해 온 백엔드 개발자**

[![Portfolio](https://img.shields.io/badge/Portfolio-younwony.github.io-4285F4?style=flat-square&logo=google-chrome&logoColor=white)](https://younwony.github.io)
[![Tistory](https://img.shields.io/badge/Tech_Blog-FF5A00?style=flat-square&logo=Tistory&logoColor=white)](https://youn12.tistory.com)
[![Gmail](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white)](mailto:wony9324@gmail.com)

---

## 자기소개

Java/Spring 기반 9년차 백엔드 개발자입니다. 커머스 플랫폼에서 상품·전시·리뷰와 외부 판매채널 연동을 담당했고, 최근에는 400만 건 이상의 인플루언서 데이터를 수집·검색해 캠페인 운영으로 연결하는 플랫폼을 초기 설계했습니다. 구현뿐 아니라 데이터 증가, 실패 복구와 운영 안정성까지 함께 책임져 왔습니다.

| 성과 | 내용 |
|:---|:---|
| 검색 10초+ → 1초 이내 | 400만+ 건·복합 조건 검색을 Elasticsearch 역색인으로 전환(동일 조건 API 조회 테스트). MySQL 원본·ES 검색 분리, 신규 인덱스 적재 후 Alias 전환 |
| 수집 수작업 수십 명/일 → 약 5,000명/일 | 목적별 외부 API 수집 자동화를 직접 설계·구현, 데이터 풀 10만 → 400만+(고유 UID 기준 중복 제거) |
| 신규 연동 4~6주 → 1~2주 | 판매채널·부티크 연동을 주문·배송, 상품·발주 두 공통 흐름으로 정리 |
| 상품 조회 API 200 → 3,000 TPS | 동기 단건 인덱싱을 메모리 큐 기반 Bulk 처리로 분리(동일 조건 JMeter 부하 테스트) |
| AI 개발 워크플로 팀 공식 절차 채택 | 계획 → 구현 → 다른 AI의 교차 리뷰 → 변경 요약 → 작업 기록 흐름을 정리·공유해 백엔드 팀원 전원이 활용. 공통 실행 환경(하네스)은 설정으로 공유 |

---

## 경력

| 기간 | 회사 | 역할 |
|:---:|:---|:---|
| 2022.02 ~ | (주)구하다 | 명품 커머스 상품·가격·주문, 판매채널·부티크 API 연동 · Kglowing 인플루언서 데이터·캠페인 플랫폼 백엔드 설계·구축 |
| 2021.09 ~ 2022.01 | (주)인터파크 | Seller Admin 유지보수·신규 기능 개발 |
| 2018.06 ~ 2021.08 | 한국문헌정보기술(주) | 기록물 관리 솔루션 SI/SM, Elasticsearch 기반 자체 검색 엔진 구축 |

---

## 기술 스택

<table>
<tr>
<td valign="top" width="50%">

### 백엔드
<p>
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white">
<img src="https://img.shields.io/badge/Spring_Batch-6DB33F?style=flat-square&logo=Spring&logoColor=white">
<img src="https://img.shields.io/badge/JPA/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white">
<img src="https://img.shields.io/badge/QueryDSL-0769AD?style=flat-square">
<img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white">
</p>

### 데이터 · 검색
<p>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white">
<img src="https://img.shields.io/badge/BigQuery_·_GA4-669DF6?style=flat-square&logo=googlebigquery&logoColor=white">
</p>

</td>
<td valign="top" width="50%">

### 인프라 · 배포
<p>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white">
<img src="https://img.shields.io/badge/Elastic_APM-005571?style=flat-square&logo=elastic&logoColor=white">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white">
</p>

### AI · 자동화 · 연동
<p>
<img src="https://img.shields.io/badge/Codex-000000?style=flat-square&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/Claude_Code-CC9B7A?style=flat-square&logo=anthropic&logoColor=white">
<img src="https://img.shields.io/badge/MCP-6366F1?style=flat-square&logo=anthropic&logoColor=white">
<img src="https://img.shields.io/badge/Slack_API-4A154B?style=flat-square&logo=slack&logoColor=white">
<img src="https://img.shields.io/badge/Google_Sheets_API-34A853?style=flat-square&logo=googlesheets&logoColor=white">
</p>

### 도구
<p>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellij-idea&logoColor=white">
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white">
<img src="https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white">
</p>

</td>
</tr>
</table>

---

## 핵심 역량

| | |
|:---|:---|
| **데이터·검색 플랫폼** | 신규 플랫폼의 수집·검색·운영 백엔드를 설계·구축하고 운영. 원본 저장소와 검색 책임을 나누고, 색인 전환이 실패해도 기존 검색 경로를 유지 |
| **커머스 도메인·외부 연동** | 채널별 API 차이는 연동 경계에 격리하고 내부 처리 흐름을 공통 구조로 재사용. API 호출 한도 안에서 우선순위 상품부터 경쟁 가격 반영 |
| **운영 자동화** | 발주·MD·주문·CS·물류팀 요구사항을 Slack·Admin 흐름으로 설계하고, 현업이 직접 운영할 범위와 개발 범위를 나눔 |
| **팀 개발 기준** | PR 리뷰 참여 기준(팀 인원 30% 이상·최소 2명) 제안·주도, 반복 운영 데이터 처리를 내부 도구로 전환 |
| **AI 개발 워크플로** | 교차 리뷰·작업 기록을 포함한 개발 워크플로를 정리·공유해 팀 공식 절차로 채택. 역할·도구·명령 권한·안전 Hook을 설정으로 공유 |

---

## 알고리즘

<div align="center">

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=wony9324)](https://solved.ac/wony9324)

</div>
