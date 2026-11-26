# 우당탕 게임룸

현재 버전: **1.1.16**

[최신 게임 실행](https://udangtang-pixel-runners.housecats850262.chatgpt.site) · [기존 GitHub Pages 주소](https://housecats-design.github.io/udangtang-pixel-runners/)

기존 GitHub Pages 주소는 최신 온라인 게임으로 이동합니다. 온라인 방 API는 Sites의 Worker와 D1에서 운영합니다.

`udangtang-game-source.zip`에 최신 코드·실행 이미지·사운드·테스트·서버 코드를 보관합니다. 압축 해제 후 `npm ci`, `npm test`, `npm run dev`로 실행합니다. 원본 대형 제작 이미지와 영상은 Sites 소스에 보관하고, 모든 게임 실행 아틀라스와 제작 메타데이터를 포함했습니다. 소스 커밋과 아카이브 해시는 `SOURCE_VERSION.json`에서 확인할 수 있습니다.

1.1.16에서는 사용자가 선택한 PixelLab ① 민트 기본형의 둥근 SD 양궁 캐릭터를 적용했습니다. 실제 생성된 17프레임에서 장전·조준 유지·발사·팔 반동·자세 복귀 구간을 경기 입력에 맞춰 재생합니다. B를 장전 전에 놓으면 발사하지 않고, 화살은 새 활 위치에서 출발합니다. 개인 화면과 8인 공동 경기장에 참가자별 색상을 반영했습니다. 기존 고정 과녁·점수·각도·쿨다운 판정을 유지하며, 추가 생성 없이 완료된 결과를 사용했습니다. 168개 테스트와 온라인 빌드를 통과했습니다.
