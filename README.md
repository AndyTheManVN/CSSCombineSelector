# CSSCombineSelector
CSS selector multiple element and class

DIỄN GIẢI	HTML	CSS
HTML elmenent: tên class có khoảng trắng.	
Vd: (img class = "bacon circular" src="...")
1. Case 1:
		img { height: 10px;  }
		.bacon { background-color: red;}
		.circular {  radius: 100%;  }
2. Case 2:
		.bacon.cirular { }

Class nằm trong cùng element: khai báo css không có khoảng trắng giữa 2 selector	
  <div class="blue">	div.blue {font-size:10px;}
Chọn 2 selector khác nhau: trong css khai báo có khoảng trắng giữa các selector	
  (div class="dropdown-menu")
	 .....
	      <a href=""> 
  Khai báo css: 	.dropdown-menu a {  }
