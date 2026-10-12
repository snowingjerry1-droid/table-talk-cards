# 테이블 대화 카드

파티에서 테이블마다 폰 1대를 가운데 두고 같이 보는 대화 카드 웹앱입니다.
서버 없이 브라우저만으로 동작하고, 진행 상태는 그 폰에만 저장됩니다.

- 앱: https://snowingjerry1-droid.github.io/table-talk-cards/
- 테이블별 QR 인쇄: https://snowingjerry1-droid.github.io/table-talk-cards/qr.html
- QR 이미지 파일: `qr/` 폴더 (`table-01.png` ~ `table-10.png`, 진행자용 `main.png`)

## 구성
- 테이블 10개: 1~8번 6인, 9~10번 8인
- 대화 4단계 40분: 워밍업 10분, 취향과 경험 15분, 요즘 사는 얘기 10분, 마무리 5분
- 마무리 단계는 "집에 가서 찾아볼 거" 카드가 첫 장으로 나옵니다.
- 주소 끝에 `?t=3`처럼 테이블 번호를 붙이면 시작 화면에서 그 번호가 미리 선택됩니다.

## 질문 고치기
`index.html` 위쪽의 `STAGES` 배열만 수정하면 됩니다. 저장하고 GitHub에 올리면 1~2분 뒤 반영됩니다.
