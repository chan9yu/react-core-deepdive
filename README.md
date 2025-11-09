# React 코어 딥다이브

리액트의 핵심 동작 원리와 Fiber 아키텍처를 깊이 있게 알아보는 세미나 자료입니다.

## 시작하기

```bash
# 패키지 설치
pnpm install

# 개발 서버 시작
pnpm dev

# 브라우저에서 http://localhost:5173 접속
```

## 주요 내용

- JSX → JavaScript 변환 과정
- Virtual DOM의 진짜 의미
- Reconciliation 알고리즘
- 얕은 비교와 불변성
- Fiber Architecture

## 발표 기능

- **화살표 키**: 슬라이드 이동
- **S 키**: 발표자 모드 (노트, 타이머, 다음 슬라이드 미리보기)
- **F 키**: 전체화면
- **ESC**: 슬라이드 개요 보기

## 프로젝트 구조

```
react-core-deepdive/
├── index.html                   # 메인 프레젠테이션 파일
├── src/
│   ├── presentation.js         # 프레젠테이션 로직
│   └── reveal-custom.css       # Reveal.js 커스텀 스타일
├── public/
│   ├── contents/
│   │   └── 1.html ~ 24.html   # 개별 슬라이드
│   ├── css/
│   │   └── common-style.css   # 슬라이드 공통 스타일
│   └── favicon/
│       └── image.png          # 파비콘
└── docs/
    └── script.md              # 발표 스크립트
```

## 기술 스택

- [Reveal.js](https://revealjs.com/) - 프레젠테이션 프레임워크
- [Vite](https://vitejs.dev/) - 빌드 도구
- [Lucide Icons](https://lucide.dev/) - 아이콘 라이브러리
- [Pretendard](https://github.com/orioncactus/pretendard) - 한글 폰트

## 라이선스

이 프로젝트는 MIT 라이선스 하에 있습니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.