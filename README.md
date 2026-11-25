# 우당탕 게임룸

현재 버전: **1.1.13**

[최신 게임 실행](https://udangtang-pixel-runners.housecats850262.chatgpt.site) · [기존 GitHub Pages 주소](https://housecats-design.github.io/udangtang-pixel-runners/)

기존 GitHub Pages 주소는 최신 온라인 게임으로 이동합니다. 온라인 방 API는 Sites의 Worker와 D1에서 운영합니다.

`udangtang-game-source.zip`에 최신 코드·실행 이미지·사운드·테스트·서버 코드를 보관합니다. 압축 해제 후 `npm ci`, `npm test`, `npm run dev`로 실행합니다. 원본 대형 제작 이미지와 영상은 Sites 소스에 보관하고, 모든 게임 실행 아틀라스와 제작 메타데이터를 포함했습니다. 소스 커밋과 아카이브 해시는 `SOURCE_VERSION.json`에서 확인할 수 있습니다.

1.1.13에서는 PC 방장·휴대폰 참가 경로로 8종목을 점검했습니다. 입력 시각의 경기 상태로 판정을 다시 계산하고 휴대폰 화면을 응답 사이에도 갱신해, 지연에 따른 도마·세단뛰기·장대높이뛰기의 잘못된 실격과 입력 뭉침을 보완했습니다. 양궁의 풍향도 각 선수별로 유지합니다. 왕복 지연 0·240·500ms의 24개 종목 시나리오, 8인 경기와 중복 입력 검사를 포함한 160개 테스트 및 온라인 빌드를 통과했습니다. 실제 모든 휴대폰 기종에서의 실기 검증은 별도입니다.
