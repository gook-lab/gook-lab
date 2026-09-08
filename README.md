<div align="center">

**한국어** · [English](./README.en.md)

# 윤성국 | Frontend Engineer

### 복잡한 제품을 검증 가능한 구조로 바꾸고,
### 해결 과정을 팀이 다시 사용할 수 있는 자산으로 남깁니다.

`React` · `TypeScript` · `Next.js` · `Testing` · `Frontend Architecture`

[Portfolio](https://seonggukyoon-portfolio.vercel.app/) · [Resume](https://app.notion.com/p/Frontend-Engineer-2240958387f480318d17ff5cad933e03) · [Email](mailto:ym0520047@gmail.com)

</div>

---

## 👋 About Me

안녕하세요. React와 TypeScript를 기반으로 웹 제품을 개발하는 6년차 프론트엔드 엔지니어 윤성국입니다.

B2C 웹과 WebView, 운영 Admin, 의료기관 대상 엔터프라이즈 제품을 개발했습니다. 로그인·본인인증 같은 사용자 진입 기능부터 데이터 조회·결과 화면, 운영 관리 기능까지 제품의 주요 영역을 담당했습니다. 현재는 의료영상 뷰어 SDK와 이를 활용하는 웹 제품을 만들고 있습니다.

코드를 작성할 때는 동작 여부뿐 아니라 변경 전후의 결과를 확인할 수 있는 기준을 함께 만듭니다. 운영 중 발견한 문제는 테스트와 자동화에 반영하고, 해결 과정은 문서로 남겨 재발 가능성을 줄입니다.

---

## 🧭 What I Do

- **제품 개발**: React·Next.js·TypeScript로 B2C 웹, WebView, 운영 Admin과 B2B 엔터프라이즈 제품을 개발하며 WebView와 앱의 통신 인터페이스도 설계했습니다.
- **상태와 데이터 흐름**: TanStack Query로 서버 상태를 관리하고, Zustand·Redux·Jotai를 제품 규모와 상태의 성격에 맞게 사용합니다.
- **컴포넌트와 라이브러리**: 반복되는 UI와 제품 기능을 재사용 가능한 컴포넌트·npm 패키지로 만들고, Storybook을 통해 디자이너·기획자와 동작 기준을 공유합니다.
- **품질 자동화**: 실제 장애와 회귀 사례를 테스트로 전환하고, Vitest·Testing Library·Playwright 검증을 CI에 연결합니다.
- **성능과 접근성**: 번들·렌더링 비용을 측정하고 지연 로딩·폰트·이미지를 최적화하며 Lighthouse와 브라우저 테스트로 확인합니다.

---

## 🏢 Current Work

### Sonix Health — B2B Enterprise Web

의료기관에서 사용하는 AI 분석 제품과 운영 도구의 프론트엔드를 개발하고 있습니다. 외부 뷰어 라이브러리를 자체 SDK로 전환했으며, 제품 요구사항에 맞는 렌더링·디코딩·측정 기능과 패키지 배포 환경을 함께 관리합니다.

- **15만 LOC 규모의 제품 프론트엔드**를 기능 단위로 분리하고 TypeScript 검증 범위 확대
- 실제 장애와 회귀 사례를 반영한 **CI 검증 단계 10개** 운영
- Vitest·Testing Library 컴포넌트 테스트와 Playwright E2E 시나리오를 여러 서비스에서 재사용할 수 있는 구조로 설계
- 공통 권한·라우팅·미들웨어 구조를 설계하고 여러 프론트엔드 서비스에 적용
- **17개 서비스의 기술 문서와 ADR 276건**을 하나의 문서 허브에서 관리

[Ontact Health](https://www.ontacthealth.com/kr/index.php) · [Sonix Health](https://www.sonixhealth.ai/ko)

---

## 🧸 Selected Projects

<table>
  <tr>
    <td width="33.33%" valign="top">
      <a href="https://pig-ma.vercel.app"><img src="https://raw.githubusercontent.com/gook-lab/pig-ma/main/docs/screenshots/01-canvas.png" alt="pig-ma 무한 캔버스" width="100%" /></a>
      <br /><strong>pig-ma</strong><br />
      <sub>도형·텍스트·커넥터·댓글을 한 화면에서 다루는 무한 캔버스</sub><br />
      <a href="https://github.com/gook-lab/pig-ma">Code</a> · <a href="https://pig-ma.vercel.app">Demo</a>
    </td>
    <td width="33.33%" valign="top">
      <a href="https://saju-blond-six.vercel.app"><img src="https://raw.githubusercontent.com/gook-lab/myeongri-seojae/main/docs/screenshots/01-intro.png" alt="명리서재 시작 화면" width="100%" /></a>
      <br /><strong>myeongri-seojae</strong><br />
      <sub>대운과 시기별 흐름을 차분하게 살펴보는 명리 서비스</sub><br />
      <a href="https://github.com/gook-lab/myeongri-seojae">Code</a> · <a href="https://saju-blond-six.vercel.app">Demo</a>
    </td>
    <td width="33.33%" valign="top">
      <a href="https://nihan-go-test.netlify.app/"><img src="https://raw.githubusercontent.com/gook-lab/nihongo/main/homepage-with-mascot.png" alt="nihongo 일본어 학습 홈" width="100%" /></a>
      <br /><strong>nihongo</strong><br />
      <sub>간격 반복 학습과 AI 튜터를 결합한 일본어 학습 PWA</sub><br />
      <a href="https://github.com/gook-lab/nihongo">Code</a> · <a href="https://nihan-go-test.netlify.app/">Demo</a>
    </td>
  </tr>
</table>

| Project | Description | Stack |
| --- | --- | --- |
| [modul](https://github.com/gook-lab/modul) | 제품별 스타일 확장을 열어 둔 헤드리스 React 컴포넌트 라이브러리 | React · TypeScript · Radix UI · Storybook |
| [pig-ma](https://github.com/gook-lab/pig-ma) · [Demo](https://pig-ma.vercel.app) | 도형·리치 텍스트·커넥터·댓글을 지원하는 무한 캔버스 라이브러리 | React · Konva · Zustand · Tiptap |
| [myeongri-seojae](https://github.com/gook-lab/myeongri-seojae) · [Demo](https://saju-blond-six.vercel.app) | 대운과 시기별 흐름을 살펴보는 명리 서비스 | React · TypeScript · Tailwind CSS |
| [nihongo](https://github.com/gook-lab/nihongo) · [Demo](https://nihan-go-test.netlify.app/) | 간격 반복 학습과 AI 튜터를 결합한 일본어 학습 PWA | React · Firebase · IndexedDB · Gemini |
| [couple-map](https://github.com/gook-lab/couple-map) | 함께 다닌 장소와 기록을 지도에 쌓는 커플 PWA | React · Firebase · Kakao Maps · d3-geo |
| [dungeon-craft](https://github.com/gook-lab/dungeon-craft) | 순수 JavaScript와 PixiJS로 만든 턴제 JRPG | JavaScript · PixiJS · Vite · Vitest |

더 많은 프로젝트와 구현 과정은 [포트폴리오](https://seonggukyoon-portfolio.vercel.app/)에서 확인할 수 있습니다.

---

## 🛠️ Skills

| Category | Technologies |
| --- | --- |
| Language | TypeScript · JavaScript |
| Framework & Library | React · Next.js · Vite · Vue.js |
| State & Data | TanStack Query · Zustand · Redux · Jotai |
| UI | Tailwind CSS · Radix UI · Emotion · Storybook |
| Testing & Monitoring | Vitest · Testing Library · Playwright · Sentry |
| Rendering | WebGL2 · WebCodecs · Canvas · PixiJS |
| Delivery | GitHub Actions · GitLab CI · npm · Nexus · Vercel |

---

## 🔍 How I Work

- 변경 전후 결과를 비교할 수 있는 기준을 먼저 정합니다.
- 장애와 회귀 사례를 테스트로 남겨 다음 변경에서도 같은 문제를 확인합니다.
- 반복되는 해결 과정은 문서와 공용 도구로 정리해 팀이 다시 사용할 수 있게 합니다.
- 기획자·디자이너와 요구사항, UX, 기술적 제약을 함께 확인하고 구현 가능한 대안을 제안합니다.

---

<div align="center">

결과의 근거를 확인하고, 복잡한 문제를 검증 가능한 설계와 기술로 해결합니다.

</div>
