# 🥃(기주 이미지)

<p align="center">
  <img src="https://github.com/user-attachments/assets/87617cf0-cfd4-457b-b638-9f90c6189958" alt="설명" width="400"/>

<h2 align="center">기주</h2>

**그대를 향해 술을 부치다**  
기주 온라인 주류 판매 사이트

---

## 📌 프로젝트 소개

기주는 온라인으로 다양한 전통주를 소개하고 판매하는 웹 플랫폼입니다.  
사용자는 회원가입 없이도 상품을 둘러볼 수 있으며, OAuth2(카카오) 로그인을 통해 간편하게 구매할 수 있습니다.  
안정적인 서버 아키텍처와 간편한 결제 시스템, 직관적인 UI를 통해 사용자에게 최적의 경험을 제공합니다.

---

## 👥 팀원

| Backend | Backend | Backend | Frontend |
|--------|--------|--------|---------|
| <img src="https://avatars.githubusercontent.com/u/97016371?v=4" width="100" alt="Kimseonj's Profile"/> | <img src="https://avatars.githubusercontent.com/u/49217569?v=4" width="100" alt="hwan4338's Profile"/> | <img src="https://avatars.githubusercontent.com/u/48951477?v=4" width="100" alt="jongbinchoi's Profile"/> | <img src="https://avatars.githubusercontent.com/u/178686486?v=4" width="100"  alt="JangInChan's Profile"/> |
| [김선준](https://github.com/kimseonj) | [김창환](https://github.com/hwan4338) | [최종빈](https://github.com/jongbinchoi) | [장인찬](https://github.com/JangInChan) |

---

## 💻 시연
| 지역 탐색 | 소셜 로그인 |
|-------------|--------------|
| <img src="./gifs/지도.gif" width="475"/> | <img src="./gifs/로그인.gif" width="475"/> |

| 상품 페이지 | 랭킹 시스템 |
|--------|-------------|
| <img src="./gifs/상세페이지.gif" width="475"/> | <img src="./gifs/랭킹.gif" width="475"/> |

| 결제 | 리뷰 작성 |
|--------------|--------------|
| <img src="./gifs/결제.gif" width="475"/> | <img src="./gifs/리뷰.gif" width="475"/> |

---

## 🛠️ 기술 스택

### 🔹 Backend

- **Language**: Java 21
- **Frameworks**: Spring Framework, Spring Boot
- **Database**: MySQL
- **ORM**: JPA
- **Deployment**: AWS EC2 (서버), AWS S3 (이미지 저장)
- **External API**:
  - 로그인: Kakao OAuth2
  - 결제: Toss Payments API
  - 지도: Kakao Map API

### 🔹 Frontend

- **Language**: TypeScript
- **Frameworks**: Next.js
- **Styling**: Tailwind CSS
- **Deployment**: Vercel

### 🔹 기타

- 협업 도구: Notion
- 디자인 툴: 피그마, 어도비 폰트

---

## 🏗️ 프로젝트 아키텍쳐

### 📌 사용자 요청 흐름도  
> 이미지 삽입 예정  
`(여기에 사용자 요청 흐름도 이미지를 삽입할 예정입니다.)`

---

### ⚙️ 백엔드 구조  
> 이미지 삽입 예정  
`(여기에 백엔드 서비스 구조 다이어그램을 삽입할 예정입니다.)`

- 컨트롤러 → 서비스 → 리포지토리 구조
- DTO를 활용한 계층 간 분리
- JPA 기반 CRUD 처리
- 예외 핸들링 및 전역 에러 처리

---

### 🔁 CI/CD

> 이미지 삽입 예정  
`(여기에 CI/CD 파이프라인 이미지 또는 설명을 삽입할 예정입니다.)`

- GitHub Actions를 이용한 자동 빌드 및 테스트
- AWS EC2 배포 자동화
- S3를 활용한 이미지 업로드 저장

---

### 💻 프론트 구조

> 이미지 삽입 예정  
`(여기에 프론트엔드 디렉토리 구조 이미지 또는 설명을 삽입할 예정입니다.)`

- Next.js 기반 서버 사이드 렌더링
- 페이지/컴포넌트 분리
- Tailwind CSS를 활용한 반응형 UI
- 카카오 지도 및 결제 API 연동

