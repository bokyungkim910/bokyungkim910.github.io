---
title: "Astro로 포트폴리오 웹사이트 만들기"
publishDate: 2024-04-02 00:00:00
description: |
  Jekyll 대신 Astro를 사용하여 디자이너 포트폴리오 웹사이트를 구축하는 방법을 소개합니다.
  말차색 테마와 다크모드를 적용한 결과물을 공유합니다.
tags:
  - Astro
  - Portfolio
  - Web Development
---

## Astro란?

Astro는 콘텐츠 중심의 웹사이트를 구축하기 위한 올인원 웹 프레임워크입니다. 

### 주요 특징

- **Zero JavaScript by Default**: 필요한 경우에만 JavaScript 로드
- **Content Collections**: Markdown/MDX 콘텐츠를 타입 안전하게 관리
- **Island Architecture**: 부분적 하이드레이션 지원
- **Framework Agnostic**: React, Vue, Svelte 등과 함께 사용 가능

## 포트폴리오 구축 과정

### 1. 프로젝트 초기화

```bash
npm create astro@latest matcha-portfolio -- --template portfolio
```

### 2. 테마 커스터마이징

말차색을 메인 컬러로 선택하여 차분하고 자연 친화적인 느낌을 살렸습니다.

### 3. 다크모드 구현

CSS 변수와 localStorage를 활용하여 다크모드를 구현했습니다.

## 마무리

Astro는 정적 사이트 생성에 매우 적합한 프레임워크입니다. GitHub Pages와 함께 사용하면 완전히 무료로 포트폴리오를 호스팅할 수 있습니다.
