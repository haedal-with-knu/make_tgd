/*좌측 메뉴 호버링*/
.menu-wrapper>a{
     display: block; 
     width: 100%; 
     padding: 20px; 
     border-left: 5px solid; 
     border-color: #468DE8;
     position: relative; 
     z-index: 2;
     text-decoration: none;
     color: #444;
     box-sizing: border-box;  
     -moz-box-sizing: border-box;  
     -webkit-box-sizing: border-box; 
	}
.menu-wrapper>a:hover{ border-bottom: 6px; color: #468DE8}

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
.menu-wrapper>a:hover:after{ width: 100%; }
.menu-wrapper>a:nth-child(n):after { background-color: #58ccff; }
   
  /* 페이지 버튼*/
.pagination>.active>a,
.pagination>.active>a:focus,
.pagination>.active>a:hover{
border: 1px solid #468de8;
}

.pagination>li>a, .pagination>li>span{
color: #468de8;
border: 1px solid #468de8;
border-bottom: 1px solid #468de8;
}

.pagination>.active>a,
.pagination>.active>a:focus,
.pagination>.active>a:hover,
.pagination>.active>span,
.pagination>.active>span:focus,
.pagination>.active>span:hover{
background: #468de8;
}

.pagination>li>a:focus,
.pagination>li>a:hover,
.pagination>li>span:focus,
.pagination>li>span:hover{
color: #fff;
background: #468de8;
border: 1px solid #468de8;
font-weight: bold;
}
   