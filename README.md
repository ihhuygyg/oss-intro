# 🌌 Project Nebula: 우주 공간의 데이터 시각화 엔진

![License: MIT](https://shields.io)
![Version](https://shields.io)
![Build Status](https://shields.io)

**Project Nebula**는 복잡한 다차원 데이터를 3D 우주 성운(Nebula) 형태로 변환하여 시각화해 주는 오픈소스 라이브러리입니다. 빅데이터 속에서 길을 잃은 개발자들을 위한 혁신적인 네비게이션 도구입니다.

> "우리는 모두 별에서 왔고, 우리의 데이터도 마찬가지입니다." — *지나가는 시니어 개발자*

## ✨ 주요 기능

* **실시간 3D 렌더링**: WebGL 기반으로 수백만 개의 데이터 포인트를 끊김 없이 시각화합니다.
* **스마트 클러스터링**: AI 알고리즘이 자동으로 연관된 데이터들을 성단(Star Cluster)으로 묶어줍니다.
* **우주선 모드 (Fly-through)**: WASD 키를 이용해 데이터 사이를 직접 비행하며 탐색할 수 있습니다.
* **다양한 테마**: '다크 매터(기본)', '슈퍼노바(라이트)', '사이버펑크 레트로' 테마를 지원합니다.

## 🚀 시작하기

### 설치 방법

```bash
# npm을 사용하는 경우
npm install project-nebula-core

# yarn을 사용하는 경우
yarn add project-nebula-core
```

### 빠른 사용법

```javascript
import { NebulaEngine } from 'project-nebula-core';

// 엔진 초기화
const engine = new NebulaEngine({
  canvasId: '#nebula-canvas',
  theme: 'dark-matter',
  gravity: 0.5
});

// 랜덤 데이터 세트 생성 및 로드
const myData = engine.generateRandomStars(1000);
engine.feed(myData);

// 우주 생성!
engine.bigBang();
```

## 🛠️ 기술 스택

* **Frontend**: TypeScript, Three.js, React
* **Backend (Data Processor)**: Rust, WebAssembly
* **Build Tool**: Vite

## 📅 로드맵

- [x] WebGL 기반 3D 코어 엔진 구현
- [x] 은하수 모양 데이터 정렬 알고리즘 추가
- [ ] VR/AR 기기 연동 (Oculus Meta Quest 지원 예정)
- [ ] 데이터가 충돌할 때 폭발하는 이펙트 추가 (블랙홀 모드)

## 🤝 기여하기

버그 발견이나 새로운 기능 제안은 언제나 환영합니다!
1. 이 저장소를 **Fork**합니다.
2. 새 기능 브랜치를 만듭니다 (`git checkout -b feature/AmazingFeature`).
3. 변경 사항을 **Commit**합니다 (`git commit -m 'Add some AmazingFeature'`).
4. 브랜치에 **Push**합니다 (`git push origin feature/AmazingFeature`).
5. **Pull Request**를 생성합니다.

## 📜 라이선스

이 프로젝트는 **MIT 라이선스**를 따릅니다. 자세한 내용은 `LICENSE` 파일을 참고하세요.
