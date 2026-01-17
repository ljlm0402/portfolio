# 웹 포트폴리오 사이트

현대적이고 반응형 웹 포트폴리오 사이트입니다. Nuxt.js와 Tailwind CSS를 사용하여 구축되었습니다.

## 🚀 기능

- **반응형 디자인** - 모든 기기에서 완벽한 사용자 경험
- **다크 테마** - 세련된 다크 테마 디자인
- **부드러운 애니메이션** - 사용자 경험을 향상시키는 부드러운 전환 효과
- **SEO 최적화** - 검색 엔진에 최적화된 메타 태그
- **성능 최적화** - 빠른 로딩 속도와 최적화된 성능

## 🛠️ 기술 스택

- **Frontend**: Nuxt.js 4, Vue.js 3, TypeScript
- **스타일링**: Tailwind CSS
- **아이콘**: Nuxt Icon (@nuxt/icon)
- **패키지 매니저**: pnpm

## 📋 섹션

1. **Hero Section** - 인사말과 주요 정보
2. **About Section** - 자기소개와 통계
3. **Skills Section** - 기술 스택과 숙련도
4. **Projects Section** - 프로젝트 갤러리
5. **Contact Section** - 연락 정보와 메시지 폼

## 🚀 시작하기

### 전제 조건

- Node.js 18+
- pnpm

### 설치

```bash
# 의존성 설치
pnpm install

# 개발 서버 실행
pnpm dev

# 프로덕션 빌드
pnpm build

# 프로덕션 미리보기
pnpm preview

# 정적 사이트 생성
pnpm generate
```

## 📁 프로젝트 구조

```
nuxt-portfolio/
├── app/
│   └── app.vue          # 루트 앱 컴포넌트
├── components/          # Vue 컴포넌트
│   ├── TheHeader.vue    # 네비게이션 헤더
│   ├── HeroSection.vue  # 히어로 섹션
│   ├── AboutSection.vue # 소개 섹션
│   ├── SkillsSection.vue # 기술 섹션
│   ├── ProjectsSection.vue # 프로젝트 섹션
│   ├── ContactSection.vue # 연락처 섹션
│   └── TheFooter.vue    # 푸터
├── data/
│   └── portfolio.js     # 포트폴리오 데이터
├── pages/
│   └── index.vue        # 메인 페이지
├── public/              # 정적 파일
└── nuxt.config.ts       # Nuxt 설정 파일
```

## 🎨 커스터마이징

### 개인 정보 수정

[data/portfolio.js](data/portfolio.js) 파일에서 개인 정보, 스킬, 프로젝트 데이터를 수정할 수 있습니다:

```javascript
export const personalInfo = {
  name: "당신의 이름",
  title: "직업/타이틀",
  email: "your@email.com",
  // ... 기타 정보
};
```

### 스타일 수정

- **색상**: [tailwind.config.js](tailwind.config.js)에서 색상 팔레트 커스터마이징
- **컴포넌트**: 각 섹션 컴포넌트에서 레이아웃과 스타일 수정

## 📱 반응형 브레이크포인트

- **모바일**: < 768px
- **태블릿**: 768px - 1024px
- **데스크톱**: > 1024px

## 🎯 향후 개선 사항

- [ ] 다국어 지원 (i18n)
- [ ] 블로그 섹션 추가
- [ ] 다크/라이트 테마 토글
- [ ] 애니메이션 라이브러리 추가
- [ ] CMS 연동

## 📄 라이선스

이 프로젝트는 MIT 라이선스하에 배포됩니다.

## 🤝 기여

기여는 언제나 환영합니다! 이슈를 열거나 풀 리퀘스트를 제출해주세요.

---

⭐ 이 프로젝트가 도움이 되었다면 스타를 눌러주세요!
