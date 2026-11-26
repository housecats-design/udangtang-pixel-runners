# 우당탕 게임룸

현재 버전: **1.1.15**

[최신 게임 실행](https://udangtang-pixel-runners.housecats850262.chatgpt.site) · [기존 GitHub Pages 주소](https://housecats-design.github.io/udangtang-pixel-runners/)

기존 GitHub Pages 주소는 최신 온라인 게임으로 이동합니다. 온라인 방 API는 Sites의 Worker와 D1에서 운영합니다.

`udangtang-game-source.zip`에 최신 코드·실행 이미지·사운드·테스트·서버 코드를 보관합니다. 압축 해제 후 `npm ci`, `npm test`, `npm run dev`로 실행합니다. 원본 대형 제작 이미지와 영상은 Sites 소스에 보관하고, 모든 게임 실행 아틀라스와 제작 메타데이터를 포함했습니다. 소스 커밋과 아카이브 해시는 `SOURCE_VERSION.json`에서 확인할 수 있습니다.

1.1.15에서는 선택한 PixelLab 02번 둥근 SD형 캐릭터를 클레이 사격에 적용했습니다. 방향 전환 17프레임과 발사·반동·복귀 9프레임을 실제 재생하고, 참가자별 머리·피부·상의·하의 색상을 반영합니다. 개인 화면과 8인 공동 경기장 모두 적용했으며 164개 테스트와 온라인 빌드를 통과했습니다. 좌→우 전환은 전환 클립 역재생, 왼쪽 발사는 오른쪽 클립 좌우 반전을 사용합니다. 기존 명중·점수·서버 입력 판정은 유지합니다.
