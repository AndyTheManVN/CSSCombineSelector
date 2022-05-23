# CSSCombineSelector
CSS selector multiple element and class<br>

Tip: nằm cùng element không spacebar, khác element có spacebar<br>

DIỄN GIẢI	HTML	CSS<br>
HTML elmenent: tên class có khoảng trắng.<br>	
Vd: (img class = "bacon circular" src="...")<br>
1. Case 1: ghép giữa 2 class name <br>
		img { height: 10px;  }<br>
		.bacon { background-color: red;}<br>
		.circular {  radius: 100%;  }<br>
2. Case 2: 2 class name không spacebar <br>
		.bacon.cirular { }<br>

Class nằm trong cùng element: khai báo css không spacebar giữa 2 selector<br>	
- HTML: (div class="blue")<br>	
- CSS: div.blue {font-size:10px;}<br>

Chọn 2 selector khác nhau: trong css khai báo có spcacbar giữa các selector	<br>
  (div class="dropdown-menu")<br>
	 .....<br>
	      (a href="") <br>
Khai báo css: 	.dropdown-menu a {  }
