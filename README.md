# Universal Mint prototypes

팀 검토용 HTML 프로토타입입니다.

## 공유 링크

- [프로토타입 선택 화면](https://hyunalee0509-ui.github.io/universal-mint-prototype/)
- [Issuer Onboarding](https://hyunalee0509-ui.github.io/universal-mint-prototype/issuer-onboarding.html)
- [Add Token · AD0–AD8, PR1–PR5, BMAX, 오류 상황](https://hyunalee0509-ui.github.io/universal-mint-prototype/add-token-flow/)
- [Deposit Confirmation · DS2](https://hyunalee0509-ui.github.io/universal-mint-prototype/ds2/)
- [Bar Serial Numbers · DS4g](https://hyunalee0509-ui.github.io/universal-mint-prototype/ds4g/)
- [Issue and Redeem · IS0–D2, RD2–RC1x, RC0](https://hyunalee0509-ui.github.io/universal-mint-prototype/issue-flow/)
- [Menu](https://hyunalee0509-ui.github.io/universal-mint-prototype/menu/)

로그인이나 저장소 초대 없이 웹 링크로 열 수 있습니다. 저장소와 배포된 웹사이트는 공개입니다.

## 파일

- `index.html`: 다섯 프로토타입으로 이동하는 시작 화면
- `issuer-onboarding.html`: 제공된 `Issuer Onboarding MVP.html` 원본
- `ds2/`: DS2 입고 확인 프로토타입 원본과 `deposit.png`
- `ds4g/`: DS4g 바 시리얼 번호 검토 프로토타입 원본과 `serialization.png`
- `menu/`: 메뉴 쪽 프로토타입(Home, 알림, 워크스페이스 전환 등). 화면 이름은 Figma 화면 코드, 원본은 따로 관리하고 완성 파일만 이 폴더에 넣음
- `issue-flow/`: Issue 흐름(IS0–D2)과 Redeem 흐름(RD2–RD4, RC0–RC1x) 프로토타입과 문서 이미지 `transfer.png`, `deposit.png`, `serialization.png`
- `add-token-flow/`: Figma Add Token 구현. 정상 경로(AD0–AD8), 철회·거절 결과, 조직 승인 경로(PR1–PR5, E1), BMAX, 입력 오류와 막힘·실패 상황. 오른쪽 아래 "프로토타입 설정"에서 보는 사람, 상장 규칙, 상황을 바꿉니다. 아이콘과 로고는 `assets/`

외부 글꼴은 Google Fonts에서 불러옵니다. 별도 빌드나 설치가 필요하지 않습니다.
화면 내 인증, 파일 선택, 서명 및 제출은 프로토타입 시뮬레이션입니다.

## 화면 업데이트

같은 이름의 HTML 파일을 수정하거나 교체하여 `main` 브랜치에 저장하면 GitHub Pages가 다시 배포합니다.
GitHub Pages 게시 설정: `main` 브랜치의 `/ (root)`.
