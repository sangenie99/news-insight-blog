# Insight News

이 폴더는 `Insight News` 정적 사이트의 실행 루트입니다. 브라우저에서 `doc/index.html`을 열면 홈 화면으로 이동합니다.

## 파일 구조

- `doc/index.html`: 진입용 리다이렉트 페이지
- `doc/home.html`: 메인 뉴스 홈 화면
- `doc/deep-analysis.html`: 심층 분석 기사 화면
- `doc/about.html`: 소개 및 팀 소개 화면

## 실행 방법

1. 브라우저에서 `doc/index.html`을 엽니다.
2. `doc/home.html`에서 상단 버튼이나 하단 내비게이션으로 다른 화면으로 이동합니다.
3. `doc/` 안의 상대 경로로 서로 연결되어 있으므로, 같은 폴더를 기준으로 페이지를 열면 정상 동작합니다.

## 참고

- 이 사이트는 정적 HTML입니다.
- Tailwind CDN, Google Fonts, 원격 이미지에 의존합니다.
- 네트워크가 없으면 스타일과 이미지 일부가 제한될 수 있습니다.
