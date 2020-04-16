
/* 위로가기 바꾸기 */
#movetotop img{display:none}
#movetotop{display: inline-block;opacity:1;background:url(https://cdn.discordapp.com/attachments/682866632237907983/686832252818423821/unknown.png);
width: 200px; height: 200px;background-size: contain;}

/* 프로필 위치 이동, 프로필 테두리 추가 시작 */
#board-info img{
float:left !important;
border: 2px SOLID #FFFFFF;
/* display: none; */
}
/* 프로필 위치 이동, 프로필 테두리 추가 끝 */

/* 접속자 수 색상 시작 */
#board-info #viewers-area {
color: #000000;
}
/* 접속자 수 색상 끝 */

/* 접속자 수 문구 수정 시작 */
#board-info #viewers-area #viewers:before {
content: "꿈꾸는 ";
color: #000000;
cursor: text;
font-weight:normal;
font-size: large;
}

#board-info #viewers-area #viewers:after {
content: "명의 트수 ";
color: #000000;
cursor: text;
font-weight:normal;
font-size: large;
}

/* 좌측 메뉴 */
#main .menu-wrapper>a>em {
  color: #4D6CFF;
}

#main .menu-wrapper>.header {
    background: #468DE8;
    border-radius: 7px 7px 0 0;
    border-bottom: 2px solid #468de8;
}


/* 축구공내리기 */
body {
background-image: url('https://media.discordapp.net/attachments/682866632237907983/686866185840754689/1.png'),url('https://cdn.discordapp.com/attachments/682866632237907983/686865228134088746/2.png');
-webkit-animation: snow 10s linear infinite;
-moz-animation: snow 10s linear infinite;
-ms-animation: snow 10s linear infinite;
animation: snow 10s linear infinite;
}

@keyframes snow {
0% {background-position: 0px 0px, 0px 0px, 0px 0px;}
100% {background-position: 500px 1000px, 400px 400px, 300px 300px;}
}

@-moz-keyframes snow {
0% {background-position: 0px 0px, 0px 0px, 0px 0px;}
100% {background-position: 500px 1000px, 400px 400px, 300px 300px;}
}

@-webkit-keyframes snow {
0% {background-position: 0px 0px, 0px 0px, 0px 0px;}
50% {}
100% {background-position: 500px 1000px, 400px 400px, 300px 300px;}
}

@-ms-keyframes snow {
0% {background-position: 0px 0px, 0px 0px, 0px 0px;}
100% {background-position: 500px 1000px, 400px 400px, 300px 300px;}
}