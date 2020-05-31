'''css

/* 댓글 수 */
#article-list>.article-list-row>.item>.list-title>small.comment-count {
color: #b350fa;
}

#article-reply-area > .header h5 {
	color: #b350fa;
}

/* 작성자 색상 */
#article-list>.article-list-row>.item>.list-title>.list-writer.logged>span {
color: #000000;
}
/* 추천수 색상 */
#article-list>.article-list-row>.item>.list-header>span {
color: white;
background: #b350fa;
}

/*좌측 메뉴 호버링*/
.menu-wrapper>a{
     display: block; 
     width: 100%; 
     padding: 20px; 
     border-left: 5px solid; 
     border-color: #b350fa;
     position: relative; 
     z-index: 2;
     text-decoration: none;
     color: #444;
     box-sizing: border-box;  
     -moz-box-sizing: border-box;  
     -webkit-box-sizing: border-box; 
	}
.menu-wrapper>a:hover{ border-bottom: 6px; color: #b350fa}

.menu-wrapper>a:after { 
     content: ""; 
     height: 100%; 
     left: 0; 
     top: 0; 
     width: 0px; 
     position: absolute; 
     transition: all 0.3s ease 0s; 
     -webkit-transition: all 0.3s ease 0s; 
     z-index: -1;
   }
.menu-wrapper>a:hover:after{ width: 100%;}
.menu-wrapper>a:nth-child(n):after { background-color: #f7cdf2;}
   
  /* 페이지 버튼*/
.pagination>.active>a,
.pagination>.active>a:focus,
.pagination>.active>a:hover{
border: 1px solid #b350fa;
}

.pagination>li>a, .pagination>li>span{
color: #b350fa;
border: 1px solid #b350fa;
border-bottom: 1px solid #b350fa;
}

.pagination>.active>a,
.pagination>.active>a:focus,
.pagination>.active>a:hover,
.pagination>.active>span,
.pagination>.active>span:focus,
.pagination>.active>span:hover{
background: #b350fa;
}

.pagination>li>a:focus,
.pagination>li>a:hover,
.pagination>li>span:focus,
.pagination>li>span:hover{
color: #fff;
background: #b350fa;
border: 1px solid #b350fa;
font-weight: bold;
}


'''
