<h1>진행 표시줄</h1>
<p>scrollHeight(콘텐츠의 전체 길이)와 clientHeight(클라이언트 화면 세로 길이) 그리고 scrollTop(스크롤바의 수직 현재 위치)속성을 사용하여 스크롤이 아래로 내려가면 진행 표시줄이 100%에 점점 가까워지게 구현했습니다.</p>

<h2>일정 주기마다 진행율 업데이트</h2>
<p>throttle함수를 사용해 0.1초마다 진행율이 업데이트 되도록 구현 (진행율 표시가 매끄럽지 못 한 단점이 있음)</p>
<img src="https://github.com/tptkds/ProgressBar/assets/58039782/3ac84294-686e-4e1c-8a06-96141b4aad3a">
