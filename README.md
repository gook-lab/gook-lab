<div align="center">

`PLAYER 01 · FRONTEND ENGINEER · STATUS ONLINE`

# YOON SEONGGUK

### 복잡한 제품을 검증 가능한 구조로 바꾸고,
### 해결 과정을 팀이 다시 사용할 수 있는 자산으로 남깁니다.

`React` · `TypeScript` · `Next.js` · `WebGL2` · `WebCodecs` · `DICOM`

[Portfolio](https://seonggukyoon-portfolio.vercel.app/) · [Resume](https://app.notion.com/p/Frontend-Engineer-2240958387f480318d17ff5cad933e03) · [Email](mailto:ym0520047@gmail.com)

</div>

---

## 01 · PROLOGUE

안녕하세요. 의료영상 렌더링 엔진과 웹 SaMD 제품을 개발하는 6년차 프론트엔드 엔지니어 윤성국입니다.

외부 라이브러리 기반 DICOM Viewer를 자체 SDK로 전환하고, 렌더링·디코딩·측정 도구 계층을 설계했습니다. 현재는 이 SDK를 사용하는 의료기관 대상 B2B 엔터프라이즈 웹 제품과 운영 도구를 함께 개발하고 있습니다.

B2C 웹과 WebView, 운영 Admin에서 시작해 의료영상 도메인까지 경험했습니다. 기능 구현에 머무르지 않고 성능과 동작을 측정하며, 운영 중 발견한 문제를 테스트·문서·자동화에 반영해 재발 가능성을 줄이는 방식으로 일합니다.

---

## 02 · CURRENT STAGE

### Sonix Health — 의료영상 SDK·웹 SaMD

의료진의 심초음파 진단을 지원하는 AI 기반 분석 제품과 DICOM Viewer SDK를 개발합니다.

- WebGL2 2D Array Texture 기반 멀티프레임 렌더러 개발
- WebCodecs 하드웨어 디코딩과 Safari 폴백 디코더 구현
- DICOMweb, WADO-RS, WADO-URI 데이터 전송 방식 지원
- 렌더링·디코딩·측정 도구를 npm 패키지로 구성하고 사내 Nexus로 배포
- React·Next.js 기반 웹 SaMD와 의료기관별 운영 기능 개발
- Vitest·Testing Library 컴포넌트 테스트와 Playwright E2E 공통 구조 설계
- 실제 장애와 회귀 사례를 반영한 CI 검증 단계 운영

[Ontact Health](https://www.ontacthealth.com/kr/index.php) · [Sonix Health](https://www.sonixhealth.ai/ko)

---

## 03 · BOSS STAGE

제품에서 마주친 기술적 제약을 측정하고, 직접 구현하거나 검증 절차를 보완해 해결했습니다.

| Stage | Challenge | Result |
| --- | --- | --- |
| `BOSS 01` | 다수의 심초음파 영상을 동시에 재생해야 하는 렌더링 비용 | WebGL2 2D Array Texture 렌더러로 100개 뷰포트 동시 재생 환경 구성 |
| `BOSS 02` | 브라우저별 영상 디코딩 지원 범위 차이 | WebCodecs 하드웨어 디코딩과 Safari용 JavaScript 폴백 구현 |
| `BOSS 03` | 대규모 제품 리팩터링 과정의 동작 변경 위험 | 원본 결과 비교와 실제 회귀 사례를 이용한 CI 검증 단계 구성 |
| `BOSS 04` | 서비스마다 반복되는 테스트와 개발 환경 설정 | Vitest·Testing Library·Playwright 시나리오를 공유하는 공통 구조 설계 |

---

## 04 · ITEM BOX

업무 밖에서도 직접 사용해 보고 싶었던 도구와 서비스를 만들며 제품 설계와 기술 선택을 검증합니다.

| Project | Description | Stack |
| --- | --- | --- |
| [modul](https://github.com/gook-lab/modul) | 제품별 스타일 확장을 열어 둔 헤드리스 React 컴포넌트 라이브러리 | React · TypeScript · Radix UI · Storybook |
| [pig-ma](https://github.com/gook-lab/pig-ma) · [Demo](https://pig-ma.vercel.app) | 도형·리치 텍스트·커넥터·댓글을 지원하는 무한 캔버스 라이브러리 | React · Konva · Zustand · Tiptap |
| [myeongri-seojae](https://github.com/gook-lab/myeongri-seojae) | 대운과 시기별 흐름을 살펴보는 명리 서비스 | React · TypeScript · Tailwind CSS |
| [nihongo](https://github.com/gook-lab/nihongo) | 간격 반복 학습과 AI 튜터를 결합한 일본어 학습 PWA | React · Firebase · IndexedDB · Gemini |
| [couple-map](https://github.com/gook-lab/couple-map) | 함께 다닌 장소와 기록을 지도에 쌓는 커플 PWA | React · Firebase · Kakao Maps · d3-geo |
| [dungeon-craft](https://github.com/gook-lab/dungeon-craft) | 순수 JavaScript와 PixiJS로 만든 턴제 JRPG | JavaScript · PixiJS · Vite · Vitest |

더 많은 프로젝트와 구현 과정은 [포트폴리오](https://seonggukyoon-portfolio.vercel.app/)에서 확인할 수 있습니다.

---

## 05 · STATUS

| Category | Technologies |
| --- | --- |
| Frontend | React · Next.js · Vite · Vue.js · TypeScript |
| State & Data | TanStack Query · Zustand · Redux · Jotai |
| UI | Tailwind CSS · Radix UI · Emotion · Storybook |
| Medical Imaging | DICOM · DICOMweb · PACS · Cornerstone3D |
| Rendering | WebGL2 · WebCodecs · Canvas · PixiJS |
| Testing | Vitest · Testing Library · Playwright |
| Delivery | GitHub Actions · GitLab CI · npm · Nexus · Vercel |

---

## 06 · PLAY STYLE

- 변경 전후 결과를 비교할 수 있는 기준을 먼저 정합니다.
- 장애와 회귀 사례를 테스트로 남겨 다음 변경에서도 같은 문제를 확인합니다.
- 반복되는 해결 과정은 문서와 공용 도구로 정리해 팀이 다시 사용할 수 있게 합니다.
- 기획자·디자이너와 요구사항, UX, 기술적 제약을 함께 확인하고 구현 가능한 대안을 제안합니다.

---

<div align="center">

### CONTINUE?

결과의 근거를 확인하고, 복잡한 문제를 검증 가능한 설계와 기술로 해결합니다.  
[Portfolio](https://seonggukyoon-portfolio.vercel.app/) · [Resume](https://app.notion.com/p/Frontend-Engineer-2240958387f480318d17ff5cad933e03) · [Email](mailto:ym0520047@gmail.com)

</div>
