# Change Me

<img src='public/images/readme/intro.svg' alt='change me 소개'> <br />

#### 개발 기간

- 2025.04.07 ~ 2025.04.28 <br /><br />

#### 🔗 [ChangeMe](https://change-me.vercel.app/)

- 테스트 계정 : test8@naver.com
- 패스워드 : a123456!

<br />

## ✅ 프로젝트 소개

하루하루를 나답게 채우고,

매일의 작은 반복이 쌓여 변화를 만들어 가면 좋겠습니다.

<br />

**Change Me**는 매일을 의미 있게 만들고 싶은 사람들을 위해

단순하지만 지속 가능한 습관 관리 도구를 제공합니다.

- 계획이 작심삼일로 끝나지 않도록 매일의 다짐을 기록할 수 있습니다.

- 루틴을 잊지 않도록 오늘 해야 할 일을 한눈에 확인할 수 있습니다.

- 성취감을 느낄 수 있도록 진행 상황을 시각적으로 확인할 수 있습니다.

<br />

## ✅ 기술 스택

### 🖥️ 프론트엔드 / 백엔드

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white" />
  <img src="https://img.shields.io/badge/Zustand-F4B73F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SWR-000000?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
</p>

### 🤝 협업 도구

<p>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
</p>

<br/>

## ✅ 프로젝트 구조 (**Clean Architecture 기반**)

```
📂app
├── 📂 api/                 # API 구현
├── 📂...                   # 페이지 구성
📂 application/
├── 📂 usecase/             # 비즈니스 로직 흐름
📂 domain/
├── 📂 entities/            # 도메인 엔티티 정의
├── 📂 repositories/        # 데이터 접근 인터페이스
📂 infra/
├── 📂 repositories/        # Supabase 기반 실제 repository 구현
📂 stores/                  # 전역 상태 관리
📂 utils/                   # 공통 유틸 함수
📂 hooks/                   # 커스텀 훅
📂 public/                  # 정적 파일 (이미지, 폰트)
```

<br />

## ✅ ERD

<img src='public/images/readme/erd.drawio.svg' alt='ERD' width='500px'>

<br />

## ✅ 주요 기능

### 1. 오늘의 루틴

#### ☑️ 진행 중인 습관 관리

- 오늘 완료한 습관을 체크할 수 있습니다.

- 현재 며칠째 진행 중인지 확인할 수 있습니다.

- 전체 기간 대비 진행률(%)을 확인할 수 있습니다.

- 새로운 습관을 등록하거나 기존 습관을 수정할 수 있습니다.

    <img src='public/images/readme/dailyRoutine.gif' alt='오늘의 루틴'> <br />

<br />

### 2. 기록 보기

#### 📝 습관 기록 열람

- 종료된 습관들을 **달성 / 실패 / 포기** 상태로 구분하여 확인할 수 있습니다.

- 진행 상태, 카테고리별 필터링 기능을 제공합니다.

    <img src='public/images/readme/record.png' alt='기록 보기'> <br />

<br />

### 3. 데일리 메시지

#### 🗨️ 회원 간 소통 공간

- 오늘의 루틴 페이지 하단에서 간편하게 메시지를 주고받을 수 있습니다.

- 회원 간 응원, 격려, 동기부여를 위한 메시지를 자유롭게 나눌 수 있습니다.

    <img src='public/images/readme/dailyMessage.gif' alt='데일리 메시지'> <br />

<br />

### 4. 회원

#### 🔐 인증 및 가입

- 이름, 이메일, 비밀번호, 닉네임을 입력해 회원가입할 수 있습니다.

- 비밀번호 변경 기능을 제공합니다.

    <img src='public/images/readme/signup.gif' alt='회원가입'> <br />
    <img src='public/images/readme/password.png' alt='비밀번호 변경'> <br />

<br />

### 5. 마이페이지

#### 👤 내 정보 관리

- 프로필 이미지 및 닉네임을 자유롭게 수정할 수 있습니다.

    <img src='public/images/readme/profile.gif' alt='마이페이지'> <br />

<br />

### 6. 관리자 페이지

#### 🛠️ 카테고리 관리

- 카테고리 목록 조회, 생성, 수정, 삭제가 가능합니다.

- 사용 중인 카테고리는 수정/삭제할 수 없습니다.

    <img src='public/images/readme/category.gif' alt='카테고리 관리'> <br />

<br />

## ✅ 팀원 소개

#### 🧑‍💻 [권우진](https://github.com/wojin57)

- DB 및 API 설계
- 클린 아키텍처 기반 프로젝트 구조 설계
- 데일리 메시지 기능 구현
- 습관 상세 보기 기능 구현

#### 👩‍💻 [박은지](https://github.com/EJ-99)

- DB 및 API 설계
- 클린 아키텍처 기반 프로젝트 구조 설계
- 모두의 습관 페이지 구현
- 카테고리 관리 기능 구현

#### 🧑‍💻 [박찬우](https://github.com/pcw7)

- DB 및 API 설계
- 클린 아키텍처 기반 프로젝트 구조 설계
- 회원 인증 기능(회원가입, 로그인) 구현
- 마이페이지 UI 및 기능 구현
- 오늘의 루틴 페이지 구현
- 기록 보기 페이지 구현

#### 🧑‍💻 [이건](https://github.com/leegeon-spinachSW)

- 서비스 기획
- DB 및 API 설계
- 클린 아키텍처 기반 프로젝트 구조 설계
- 기록 보기 페이지 구현

<br />
