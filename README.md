# 말차색 포트폴리오 웹사이트

Astro로 구축한 디자이너 포트폴리오 웹사이트입니다. 말차색을 메인 컬러로 사용하여 차분하고 자연 친화적인 느낌을 살렸으며, 다크모드를 지원합니다.

## 🎨 특징

- **말차색 테마**: 차분하고 자연 친화적인 컬러 팔레트
- **다크모드 지원**: 라이트/다크 테마 전환 가능 (localStorage 저장)
- **반응형 디자인**: 모바일/태블릿/데스크톱 대응
- **포트폴리오 갤러리**: 프로젝트 쇼케이스
- **블로그 기능**: Markdown 기반 포스팅
- **GitHub Pages 무료 호스팅**

## 🚀 기술 스택

- [Astro](https://astro.build) - 정적 사이트 생성기
- [TypeScript](https://www.typescriptlang.org/) - 타입 안전성
- CSS Variables - 테마 시스템
- GitHub Pages - 무료 호스팅

## 🛠️ 시작하기

### 1. 저장소 클론

```bash
git clone https://github.com/username/username.github.io.git
cd username.github.io
```

### 2. 의존성 설치

```bash
npm install
```

### 3. 개발 서버 실행

```bash
npm run dev
```

브라우저에서 `http://localhost:4321`으로 접속하세요.

### 4. 빌드

```bash
npm run build
```

## 📝 콘텐츠 관리

### 프로젝트 추가

`src/content/work/` 폴더에 Markdown 파일을 추가하세요:

```markdown
---
title: 프로젝트명
description: 프로젝트 설명
publishDate: 2024-01-01
img: /assets/stock-1.jpg
tags:
  - Branding
  - UI/UX
---

프로젝트 상세 내용...
```

### 블로그 포스트 작성

`src/content/blog/` 폴더에 Markdown 파일을 추가하세요:

```markdown
---
title: 포스트 제목
description: 포스트 요약
publishDate: 2024-01-01
tags:
  - Design
  - Tutorial
---

본문 내용...
```

### 프로필 수정

`src/pages/about.astro` 파일을 수정하세요.

## 🎨 커스터마이징

### 테마 색상 변경

`src/styles/global.css` 파일에서 CSS 변수를 수정하세요:

```css
:root {
  --matcha-primary: #6B8E23;
  --matcha-secondary: #7A9E7E;
  /* ... */
}
```

### 폰트 변경

Google Fonts에서 원하는 폰트를 선택하여 `src/components/MainHead.astro`에 추가하세요.

## 📦 배포

GitHub Actions를 통해 자동으로 GitHub Pages에 배포됩니다.

`main` 브랜치에 push하면 자동으로 빌드 및 배포가 진행됩니다.

### GitHub Pages 설정

1. GitHub 리포지토리 Settings → Pages
2. Source: GitHub Actions 선택
3. `main` 브랜치에 push하면 자동 배포

### 수동 배포

```bash
npm run build
# dist 폴더의 내용을 배포
```

## 📄 라이선스

MIT License

---

제작 with 💚 and ☕
# Trigger workflow
