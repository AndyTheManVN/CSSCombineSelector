# CSSCombineSelector
CSS selector multiple element and class

DIỄN GIẢI	HTML	CSS<br>
HTML elmenent: tên class có khoảng trắng.<br>	
Vd: (img class = "bacon circular" src="...")<br>
1. Case 1:<br>
		img { height: 10px;  }<br>
		.bacon { background-color: red;}<br>
		.circular {  radius: 100%;  }<br>
2. Case 2:<br>
		.bacon.cirular { }<br>

Class nằm trong cùng element: khai báo css không có khoảng trắng giữa 2 selector<br>	
(div class="blue")<br>	
div.blue {font-size:10px;}<br>

Chọn 2 selector khác nhau: trong css khai báo có khoảng trắng giữa các selector	<br>
  (div class="dropdown-menu")<br>
	 .....<br>
	      (a href="") <br>
Khai báo css: 	.dropdown-menu a {  }
