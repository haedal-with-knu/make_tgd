/* 배경 그라데이션 */
html {
background: linear-gradient(#a4fc97, #6a63fb, #f9244b);
height: auto !important;
}

/*폰트*/
@font-face {
font-family : 'CookieRunOTF-Bold';
src : url("https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_twelve@1.0/CookieRunOTF-Bold00.woff") format('woff');
}

body {
background: transparent; /*이 친구 넣어줘야 배경 바뀜*/
font-family : 'CookieRunOTF-Bold', sans-serif;
}

/* 0게더 */
header .row>div:nth-child(1)>a {
display: block;
width: 140px;
height: 50px;
background: url(https://cdn.discordapp.com/attachments/682866632237907983/686839457332461578/unknown.png) no-repeat;
background-size: auto 51px;
}

header .row>div:nth-child(1)>a>img {
display: none;
}

/* 게시판 배경바꾸기 */
#main #main-content>div.frame {
   background: url("https://cdn.discordapp.com/attachments/682866632237907983/686866126185168915/unknown.png") no-repeat;
   background-size: 900px 30000px;
}

/* 검색창 */
header #right-search-form>input[type='text'] {
 margin-top: 0;
    border: 2px SOLID #468de8;
    border-top-left-radius: 2px;
    border-top-right-radius: 2px;
    border-bottom-left-radius: 2px;
    border-bottom-right-radius: 2px;
    border-radius: 7px;
}
/* 각종 테두리, 선 */
header #header-bar>.row, #main .menu-wrapper, #main #main-content>div.frame {
    border-radius: 7px;
    border: 2px solid #468de8;
}
#main .menu-wrapper .spacer {
    background: #468DE8;
    height: 2px;
}
/* 게시판 광고 위에 가로선 */
#article-list #article-list-category { 
    border-top: 2px solid #468de8 !important;
	margin-top: 4px;
   margin-bottom: 4px;
}

/* 기본 마우스 커서 */
html,
body,
.fr-popup.emoticons,
.fr-top,
select.form-control,
input[type=checkbox],
input[type=radio],
.opt
{
cursor: url(https://cdn.discordapp.com/attachments/682866632237907983/686868194228830219/1.png) 0 0, auto !important;
}

/* 선택 마우스 */
#right-search-form>#right-search-btn,
#board-info #board-info-bottom #addFavoriteBtn,
#article-list #article-option-area>#article-option-area-toggle-btn,
#article-list>.article-list-row>.item>.list-title>.list-writer>span,
.reply > .reply-header > .reply-writer.logged,
.reply-menu,
.btn,
.fr-toolbar .fr-command.fr-btn,
.fr-popup .fr-command.fr-btn,
.fr-view img,
.pull-left,
a {
cursor: url(https://cdn.discordapp.com/attachments/682866632237907983/686868195512156198/2.png) 0 0, auto !important;
}

/* 입력창 마우스 */
span#viewers,
#article-list #boardSearchForm .form-control,
.fr-view,
.fr-box.fr-basic.fr-element,
input[type='text']
{
cursor: url(https://cdn.discordapp.com/attachments/682866632237907983/686868195512156198/2.png) 0 0, auto !important;
}

