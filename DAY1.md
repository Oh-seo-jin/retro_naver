## Git Hub 연결
RETRO_NAVER이라는 폴더에 만들어갈 예정

ZeroCho 강의 들으면서 따라가는 중
## .html 만들기
- 기본서식 : VScode에서 doc 탭
- UTF-8 : 인코딩 방식 VScode에서도 동일한지 확인하기
- <meta http-equiv="X-UA-Compatible" content="IE=edge"> : 엣지 브라우저용으로 넣어두기
- <meta name="viewport" content="width=device-width, initial-scale=1.0"> : 모바일용으로 넣어두기
- display:inline-bloack : div는 기본적으로 block이라서 남은 부분 margin이 차지 -> inline-bloack으로 수정
- position : 모든 태그는 기본 position:static
  - static : 고정
  - relative : 원래 자리에서 left, right, top, bottom 값만큼 이동
  - absolute : 기본값은 원래 자리, body를 기준으로 이동, 기준점 변경 가능(static이 아닌 가까운 조상)
  - fixed : 스크롤을 내려도 항상 고정
  - sticky : absolute였다가 스크롤을 어느정도 내리면 fixed
- 가상태그 : 모든 태그에 디자인적인 요소를 위해 존재하지 않는 ::before, ::after을 추가 가능
  - ::before : content 필요, 자식과 동일
- z-index : 요소(레이어) 뒤로 내리거나 앞으로 가져오기, 서로 형제일 때만 적용
- blind class : 시각장애인을 위한 요소, display=none이면 스크린 리더에 읽히지 않기 때문에 X
- box-sizing: border-box; : 기본값은 content-box인데 바꾸면 padding까지를 크기로 포함
- form+input : form 안에서 input을 넣으면 enter를 치면 자동으로 검색하게 됨
