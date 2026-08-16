<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/farms/yshong1998"/>
</a>

## 안녕하세요, 백엔드 개발자 홍예석입니다 👋

**사람이 손으로 하던 일을 코드로 옮기는 백엔드 개발자입니다.**

* 📝 <a href="#">개발 블로그</a>
* 📄 <a href="#">이력서</a>
* ✉️ yshong1998@gmail.com

<br>

### 저를 소개할게요

* O2O 서비스 회사에서 **상담사의 업무 자동화**를 맡고 있어요
* 대화를 복사하고, 폼으로 정리하고, 다른 툴에 옮겨 적던 4단계를 명령어 한 번으로 만들었어요
* Java/Spring으로 시작해 지금은 **NestJS**로 일합니다
* **비개발 직군이 실제로 어떻게 일하는지** 관찰하는 걸 좋아해요
* 로그가 디스크를 채우고(PM2 logs), 잘 돌아가는 워크플로우(채널톡)가 조용히 과금되는 걸 겪으면서 **배포 이후**를 함께 생각하게 됐어요

<br>

### 이런 걸 고민합니다

**자동화는 기술보다 관찰의 문제라고 생각해요.**
부트캠프 운영 매니저로 100여 명을 관리하던 시절이 있었는데, 그때 몸으로 익힌 감각이 지금 자동화할 지점을 찾는 데 그대로 쓰이고 있습니다.

**스택이 바뀌어도 고민은 남더라고요.**
Java에서 TypeScript로 넘어와 보니 트랜잭션 경계나 실패 처리 같은 문제는 그대로였습니다. 그 공통된 부분을 먼저 붙잡는 방식으로 새 환경에 적응해 왔어요.

<br>

### 기술 스택

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"><img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=NestJS&logoColor=white"><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white">

<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white"><img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white"><img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=Redis&logoColor=white"><img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=Amazon%20Web%20Services&logoColor=white">

<br>

## 프로젝트

#### <a href="https://github.com/Sparta-Triple/CultureTicket">컬쳐티켓</a> (2025.01) - MSA 기반 공연 티켓팅 서비스
* 백엔드 5명 · 커밋 47개 · **User, Performance, Coupon 서비스**를 담당했어요
* Redis Sorted Set으로 실시간 인기 공연 랭킹 구현, 쿠키로 동일 사용자의 조회수 중복 증가를 막고 주 단위로 랭킹이 초기화되도록 스케줄러 구성
* 회원가입·로그인부터 탈퇴, 계정 복구까지 User 도메인 전반과 Gateway의 JWT 인증 필터 구현
* 쿠폰 발급 시 중복 발급을 차단하고, 해당 정책을 테스트 코드로 검증
* 기술 스택: Spring Boot / Spring Cloud / PostgreSQL / Redis / QueryDSL / Docker

#### <a href="https://github.com/project-gongsimchae/gongsimchae">공심채</a> (2024.07) - 1인 가구를 위한 공동구매·소분 쇼핑몰
* 백엔드 5명 · 커밋 142개 · **이벤트/쿠폰 도메인**과 관리자 페이지를 담당했어요
* 할인·쿠폰발급·쿠폰코드발급 세 가지 이벤트 타입을 하나의 생성 흐름에서 분기 처리하도록 설계
* 이벤트를 물리 삭제하지 않고 상태값으로 관리해, 사용자 화면에서는 숨기고 관리자 화면에서는 이력이 남도록 구현
* 카테고리·신상품·베스트·이벤트 페이지의 조회, 정렬, 페이지네이션 구현
* 기술 스택: Spring Boot / Spring Security / MySQL / JPA / Thymeleaf / AWS

<br>

> 실무 코드는 회사 비공개 저장소에 있습니다.
> 어떤 문제를 어떻게 풀었는지는 <a href="#">이력서</a>에 정리해 두었어요.
