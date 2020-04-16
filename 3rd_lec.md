```css
/* 위로가기 바꾸기 */
#movetotop img{display:none}
#movetotop{display: inline-block;opacity:1;background:url(https://cdn.discordapp.com/attachments/700289358904950808/700306883818553464/up.png);
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
content: "어서오세요 ";
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
#board-info #board-info-bottom>a{
	color: #7c33b0;
}

/* 좌측 메뉴 */
#main .menu-wrapper>a>em {
  color: #b350fa;
}

#main .menu-wrapper>.header {
    background: #b350fa;
    border-radius: 4px 4px 0 0;
    border-bottom: 2px solid #b350fa;
}

/* 축구공내리기 
body {
background-image: url('https://cdn.discordapp.com/attachments/700289358904950808/700289483958124681/2.jpeg'),url('https://cdn.discordapp.com/attachments/700289358904950808/700289485660880967/3.jpeg');
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
*/
```
