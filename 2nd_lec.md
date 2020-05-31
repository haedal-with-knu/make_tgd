```css
/* 배경 그라데이션 */
html {
background: linear-gradient(#ffdbfb, #e2b0ff , #cfd0ff);
height: auto !important;
}

/*폰트*/
@font-face { font-family: 'yg-jalnan'; src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_four@1.2/JalnanOTF00.woff') format('woff'); font-weight: normal; font-style: normal; }

body {
background: transparent; /*이 친구 넣어줘야 배경 바뀜*/
font-family : 'yg-jalnan', sans-serif;
}

/* 0게더 */
header .row>div:nth-child(1)>a {
display: block;
width: 140px;
height: 50px;
background: url(https://cdn.discordapp.com/attachments/700289358904950808/700309408390840430/logo.png) no-repeat;
background-size: auto 51px;
}

header .row>div:nth-child(1)>a>img {
display: none;
}

/* 게시판 배경바꾸기 */
#main #main-content>div.frame {
   background: url("https://cdn.discordapp.com/attachments/700289358904950808/700293905899454515/KakaoTalk_20200416_193436052.png") no-repeat;
   background-size: 900px 8000px;
}

/* 검색창 */
header #right-search-form>input[type='text'] {
 margin-top: 0;
    border: 2px SOLID #b350fa;
    border-radius: 7px;
}
/* 각종 테두리, 선 */
header #header-bar>.row, #main .menu-wrapper, #main #main-content>div.frame {
    border-radius: 7px;
    border: 2px solid #b350fa;
}
#main .menu-wrapper .spacer {
    background: #b350fa;
    height: 2px;
}
/* 게시판 광고 위에 가로선 */
#article-list #article-list-category { 
    border-top: 2px solid #b350fa !important;
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
cursor: url(https://media.discordapp.net/attachments/700289358904950808/700307224521867314/cursor.png) 0 0, auto !important;
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
cursor: url(https://media.discordapp.net/attachments/700289358904950808/700307224521867314/cursor.png) 0 0, auto !important;
}

/* 입력창 마우스 */
span#viewers,
#article-list #boardSearchForm .form-control,
.fr-view,
.fr-box.fr-basic.fr-element,
input[type='text']
{
cursor: url(https://media.discordapp.net/attachments/700289358904950808/700307224521867314/cursor.png) 0 0, auto !important;
}

```
