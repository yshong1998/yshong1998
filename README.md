<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/farms/yshong1998"/>
</a>

## 안녕하세요, 백엔드 개발자 홍예석입니다 👋

**사람이 손으로 하던 일을 코드로 옮기는 백엔드 개발자입니다.**

* 📄 <a href="https://yshong1998.notion.site/3be1260b1cea8023b40cc13cb871bb5d?source=copy_link" target="_blank" rel="noopener noreferrer">이력서</a>
* ✉️ yshong1998@gmail.com

<br>

### 저를 소개할게요

* 청소 서비스(O2O)에서 상담사의 업무 자동화를 맡고 있어요
* 대화를 복사하고, AI에 붙여넣고, 폼으로 정리하고, 다른 툴에 옮겨 적던 4단계를 **명령어 한 번**으로 만들었어요 (건당 1분 → 5초)
* Java/Spring으로 시작해 지금은 **NestJS**로 일합니다
* **비개발 직군이 실제로 어떻게 일하는지** 관찰하는 걸 좋아해요
* 로그가 디스크를 채우고(PM2 logs), 잘 돌아가는 워크플로우(채널톡)가 조용히 과금되는 걸 겪으면서 **배포 이후**를 함께 생각하게 됐어요

<br>

### 걸어온 길

**경력**

* **2026.01 ~ 현재** · (주)에코라이프밸런스 — 백엔드 개발자
* **2025.03 ~ 2025.04** · (주)웨이브이 — 백엔드 인턴 (해외 대학 진학 튜터링 플랫폼)
* **2023.08 ~ 2023.11** · 팀스파르타 — 항해99 부트캠프 Assistant PM

**교육 · 자격**

* **2025.07 ~ 2026.01** · 삼성 청년 SW·AI 아카데미(SSAFY) Java 비전공 트랙
* **2024.11 ~ 2025.02** · 팀스파르타 Java 단기 심화
* **2024.03 ~ 2024.09** · 멋쟁이사자처럼 백엔드 스쿨
* **2018.03 ~ 2024.02** · 세종대학교 교육학과 학사
* **2024.06** · SQLD (한국데이터산업진흥원)

<br>

### 이런 걸 고민합니다

**자동화는 기술보다 관찰의 문제라고 생각해요.** <br>
부트캠프 운영 매니저로 100여 명을 관리하던 시절이 있었는데, 그때 익힌 감각이 지금 자동화 요구사항을 구현하는 데 그대로 쓰이고 있어요.

**스택이 바뀌어도 고민은 남더라고요.** <br>
Spring에서 NestJS로 넘어와 보니 싱글/멀티 스레딩과 동기/비동기로 인한 차이로부터 기인하는 차이점이 많았습니다. <br>
다만 트랜잭션 경계나 실패 처리 같은 문제에 대한 고민은 비슷했고, 이를 어떻게 일관성 있게 해결할 것인지 찾아나가는 중입니다 :)

<br>

### 기술 스택

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"><img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=NestJS&logoColor=white"><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white">

<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white"><img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white"><img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=Redis&logoColor=white"><img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=Amazon%20Web%20Services&logoColor=white">

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"><img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=GraphQL&logoColor=white"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">

<br>

## 실무에서 한 일

#### 에코라이프밸런스 (2026.01 ~ 현재) — 채널톡 기반 고객 상담 자동화

* 채널톡 웹훅을 수신·처리하는 NestJS 서버를 개발·운영하고 있어요
* 예약 확정부터 협업 툴(Flow) 작업 등록까지 이어지던 4단계 수작업을 명령어 한 번으로 처리 — **건당 약 1분 → 5초**
* Claude API로 상담 메시지(건당 약 100개)에서 고객명·연락처·주소·작업 유형·일시·예상 비용·특이사항을 정형 폼으로 추출
* 상담방 전체를 요약하니 재방문 고객의 이전 방문 내용까지 섞이는 문제가 있었어요. 명시적 시작/종료 명령 방식은 채널톡의 상담방 생성 구조와 상담사의 조작 부담 때문에 접고, **고객의 재방문 패턴과 상담방 재사용 규칙을 분석해 이번 방문 구간만 식별**하도록 해결했습니다
* 기술 스택: NestJS / TypeScript / PostgreSQL / AWS EC2 / PM2 / Claude API / 채널톡 API / Flow API

#### 웨이브이 (2025.03 ~ 2025.04) — 백엔드 인턴

* REST + MongoDB 기반 레거시 서버를 **GraphQL + PostgreSQL** 구조로 마이그레이션 (NestJS)
* PostgreSQL 이벤트 트리거와 SSE를 연동해 실시간 알림 전송 기능 구현

<br>

## 프로젝트

> 실무 이전 부트캠프 팀 프로젝트입니다.

#### <a href="https://github.com/Sparta-Triple/CultureTicket">컬쳐티켓</a> (2025.01 ~ 2025.02) - MSA 기반 공연 티켓팅 서비스

* 백엔드 5명 · 커밋 47개 · **User, Performance, Coupon 서비스**를 담당했어요
* Redis Sorted Set으로 실시간 인기 공연 랭킹 구현, 쿠키로 동일 사용자의 조회수 중복 증가를 막고 주 단위로 랭킹이 초기화되도록 스케줄러 구성
* 회원가입·로그인부터 탈퇴, 계정 복구까지 User 도메인 전반과 Gateway의 JWT 인증 필터 구현
* 쿠폰 발급 시 중복 발급을 차단하고, 해당 정책을 테스트 코드로 검증
* Swagger 문서 설정과 이슈·PR 템플릿 작성으로 협업 규칙 정비, 대기열 도입 전후 비교를 위한 JMeter 부하 테스트 분담 수행
* 기술 스택: Spring Boot / Spring Cloud / PostgreSQL / Redis / QueryDSL / Docker

#### <a href="https://github.com/project-gongsimchae/gongsimchae">공심채</a> (2024.07 ~ 2024.09) - 1인 가구를 위한 공동구매·소분 쇼핑몰

* 백엔드 5명 · 커밋 142개 · **이벤트/쿠폰 도메인**과 관리자 페이지를 담당했어요
* 할인·쿠폰발급·쿠폰코드발급 세 가지 이벤트 타입을 하나의 생성 흐름에서 분기 처리하도록 설계, 이벤트 생성·삭제가 대상 카테고리 상품의 할인율에 반영되도록 연동
* 이벤트를 물리 삭제하지 않고 상태값으로 관리해, 사용자 화면에서는 숨기고 관리자 화면에서는 이력이 남도록 구현
* 카테고리·신상품·베스트·이벤트 페이지의 조회, 정렬, 페이지네이션 구현
* 기술 스택: Spring Boot / Spring Security / MySQL / JPA / Thymeleaf / AWS
<br>

> 실무 코드는 회사 비공개 저장소에 있습니다.
> 어떤 문제를 어떻게 풀었는지는 <a href="https://yshong1998.notion.site/3be1260b1cea8023b40cc13cb871bb5d?source=copy_link">이력서</a>에 정리해 두었어요.
