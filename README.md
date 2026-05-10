# Whale Survivors — Homepage

도트 인디 서바이버 액션 게임 *Whale Survivors* 의 정적 소개 홈페이지.

## 구성

- `index.html` — 단일 HTML 페이지 (Hero / Story / Stages / Bosses / Features / Weapons / Gallery)
- `i18n.js` — 10개 언어 번역 사전 (ko · en · ja · zh-CN · zh-TW · ru · es · pt-BR · de · fr)
- `assets/` — 게임 프로젝트에서 복사한 도트 이미지 / 씬 / 로비 아이콘 / 캐릭터 스프라이트

## 다국어

브라우저 언어를 자동 감지해 적용하고, 우상단 드롭다운으로 즉시 전환할 수 있다. 선택값은 `localStorage` 에 저장된다.

## 로컬에서 보기

빌드 단계 없음. `index.html` 더블클릭 또는:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## 스택

순수 HTML / CSS / Vanilla JS. React · 빌드 도구 · 외부 의존성 없음.
폰트: Press Start 2P + VT323 (Google Fonts).
