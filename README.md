# Universal Mint prototypes

팀 검토용 HTML 프로토타입입니다.

## 공유 링크

- [프로토타입 선택 화면](https://hyunalee0509-ui.github.io/universal-mint-prototype/)
- [Issuer Onboarding](https://hyunalee0509-ui.github.io/universal-mint-prototype/issuer-onboarding.html)
- [Add Token · AD0–AD8, PR1–PR5, BMAX, 오류 상황](https://hyunalee0509-ui.github.io/universal-mint-prototype/add-token-flow/)
- [Deposit Confirmation · DS2](https://hyunalee0509-ui.github.io/universal-mint-prototype/ds2/)
- [Bar Serial Numbers · DS4g](https://hyunalee0509-ui.github.io/universal-mint-prototype/ds4g/)
- [Issue and Redeem · IS0–D2, RD2–RC1x, RC0](https://hyunalee0509-ui.github.io/universal-mint-prototype/issue-flow/)
- [Menu](https://hyunalee0509-ui.github.io/universal-mint-prototype/menu/) (Home에서 시작)
- [Onboarding](https://hyunalee0509-ui.github.io/universal-mint-prototype/onboarding/) (로그인에서 시작, Menu와 같은 파일)

로그인이나 저장소 초대 없이 웹 링크로 열 수 있습니다. 저장소와 배포된 웹사이트는 공개입니다.

## 파일

- `index.html`: 다섯 프로토타입으로 이동하는 시작 화면
- `issuer-onboarding.html`: 제공된 `Issuer Onboarding MVP.html` 원본
- `ds2/`: DS2 입고 확인 프로토타입 원본과 `deposit.png`
- `ds4g/`: DS4g 바 시리얼 번호 검토 프로토타입 원본과 `serialization.png`
- `onboarding/`: 온보딩과 메뉴를 합친 프로토타입. `menu/`와 같은 파일이고 로그인 화면에서 시작
- `menu/`: 온보딩과 메뉴를 합친 프로토타입(로그인, 조직 만들기, 심사, Home, 알림 등). Home에서 시작. 화면 이름은 Figma 화면 코드, 원본은 따로 관리하고 완성 파일만 넣음
- `issue-flow/`: Issue 흐름(IS0–D2)과 Redeem 흐름(RD2–RD4, RC0–RC1x) 프로토타입과 문서 이미지 `transfer.png`, `deposit.png`, `serialization.png`
- `add-token-flow/`: Figma Tokens 진입(TK1, TK2)과 Add Token 구현. 정상 경로(AD0–AD8), 철회·거절 결과, 조직 승인 경로(PR1–PR5, E1), BMAX, 입력 오류와 막힘·실패 상황. "프로토타입 설정"은 세 칸입니다. 열 화면 고르기에서는 진입, 작성, 검토·제출, 조직 승인, 플랫폼 심사, 결과 6단계 아래에 정상 화면과 막힘·실패 상황이 묶여 있고, 조건(토큰 종류, 보는 사람, 상장 규칙)을 고른 뒤 확인을 누르면 그 화면이 바로 열립니다. 지금 화면에서 칸은 상태를 유지한 채 보는 사람을 바꾸거나 승인을 진행합니다. 주소 끝에 Figma 프레임 번호를 붙이면(예: `#AD6b`) 그 화면이 바로 열리고, Figma 각 프레임 위의 "HTML ↗" 링크가 이 주소로 연결됩니다. 상자 맨 위에는 지금 보이는 화면의 Figma 프레임 번호(예: AD6b)가 표시되고, 누르면 Figma의 해당 프레임이 새 탭에서 열립니다. 설정 상자는 항상 열려 있고, 넓은 화면에서는 오른쪽에 고정됩니다. 아이콘과 로고는 `assets/`

외부 글꼴은 Google Fonts에서 불러옵니다. 별도 빌드나 설치가 필요하지 않습니다.
화면 내 인증, 파일 선택, 서명 및 제출은 프로토타입 시뮬레이션입니다.

## 화면 업데이트

같은 이름의 HTML 파일을 수정하거나 교체하여 `main` 브랜치에 저장하면 GitHub Pages가 다시 배포합니다.
GitHub Pages 게시 설정: `main` 브랜치의 `/ (root)`.
