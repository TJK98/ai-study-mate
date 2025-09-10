# AI Study Mate - Frontend

React + Vite + Tailwind CSS로 구축된 AI 스터디 메이트 프론트엔드입니다.

## 🚀 기술 스택

- **React 19** - 최신 React 버전
- **Vite** - 빠른 빌드 도구
- **Tailwind CSS** - 유틸리티 퍼스트 CSS 프레임워크
- **React Router** - 클라이언트 사이드 라우팅
- **Zustand** - 상태 관리
- **Axios** - HTTP 클라이언트

## 📦 설치 및 실행

```bash
# 의존성 설치
npm install

# 개발 서버 실행
npm run dev

# 빌드
npm run build

# 미리보기
npm run preview
```

## 🎨 Tailwind CSS 설정

### 커스텀 컬러 팔레트

- **Primary**: 파란색 계열 (primary-50 ~ primary-900)
- **Secondary**: 회색 계열 (secondary-50 ~ secondary-900)

### 커스텀 컴포넌트 클래스

- `.btn-primary` - 기본 버튼 스타일
- `.btn-secondary` - 보조 버튼 스타일
- `.btn-outline` - 아웃라인 버튼 스타일
- `.input-field` - 입력 필드 스타일
- `.card` - 카드 컴포넌트 스타일
- `.card-hover` - 호버 효과가 있는 카드

### 커스텀 애니메이션

- `animate-fade-in` - 페이드 인 애니메이션
- `animate-slide-up` - 슬라이드 업 애니메이션
- `animate-bounce-gentle` - 부드러운 바운스 애니메이션

## 📁 프로젝트 구조

```
src/
├── components/     # 재사용 가능한 컴포넌트
├── pages/         # 페이지 컴포넌트
├── services/      # API 서비스
├── stores/        # Zustand 스토어
├── styles/        # 글로벌 스타일
├── utils/         # 유틸리티 함수
├── App.jsx        # 메인 앱 컴포넌트
└── main.jsx       # 앱 진입점
```

## 🔧 개발 가이드

### Tailwind CSS 사용법

```jsx
// 기본 유틸리티 클래스
<div className="bg-blue-500 text-white p-4 rounded-lg">
  Hello World
</div>

// 커스텀 컴포넌트 클래스
<button className="btn-primary">
  클릭하세요
</button>

// 반응형 디자인
<div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
  <div>모바일: 1열, 태블릿: 2열, 데스크톱: 3열</div>
</div>
```

### 컴포넌트 작성 가이드

1. 컴포넌트는 `src/components/` 디렉토리에 생성
2. 파일명은 PascalCase 사용 (예: `UserProfile.jsx`)
3. Tailwind CSS 클래스를 활용한 스타일링
4. 재사용 가능한 컴포넌트로 설계

## 📝 라이브 코딩 팁

- **유틸리티 퍼스트**: CSS 파일 작성 없이 HTML에서 바로 스타일링
- **빠른 프로토타이핑**: Tailwind의 풍부한 유틸리티 클래스로 빠른 개발
- **일관된 디자인**: 미리 정의된 디자인 시스템 활용
- **반응형 디자인**: `sm:`, `md:`, `lg:`, `xl:` 접두사로 간편한 반응형 구현
