## javascript

classList.toggle 로 "active" 클래스를 넣었다 뺏다 하며 여러가지 클릭이벤트효과를
생성하였다.

특히 햄버거 버튼은 클릭이벤트 발생시 두개의 span 바가 로테이트 , 트랜스레이트 효과가
적용됨으로써 닫기 버튼인 X 로 변경되게하였고 X클릭시엔 다시 햄버거 모양으로 돌아오게 하였다.

모바일GNB 를 width:0; overflow:hidden; 상태에서 acitve 클래스가 들어오면 (햄버거버튼 클릭시 액티브부여)
width:48%; 로 전환하였고 트랜지션을 주어서 0.3초간 너비가 늘어나도록 설정하였다.

## CSS
PC환경의 픽셀기반 레이아웃을 미디어쿼리를 사용해 모바일한경에서는 100%로 바꿧고, 여백은 패딩으로 주었다.
모바일 환경 특성을 고려해 text-align:center 로 글자들을 가운데 정렬하였다.