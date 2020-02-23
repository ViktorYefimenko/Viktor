    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8"/>
	   <title>test</title>
       <link href="https://fonts.googleapis.com/css?family=Abril+Fatface&display=swap" rel="stylesheet"> 
	   <link href="style.css" rel="stylesheet" type="text/css"/>
    </head>
    <body> 
  
        <div class="wrapper">
		     <div class="header">
			     <a class="inner-header">Мoя пробная  версия!!!</a>
                 <p class="inner-header-1">	<img src="image/IMG_20180922_164928.jpg" alt="Viktor" width="130px" height="130px" /></p>
			 </div>
		     <div class="row">
		     <div class="sidebar-1">
		         <a class="inner-sidebar-1" href="#">Главная</a>
			 </div>
		     <div class="sidebar-2">
		         <a class="inner-sidebar-2" href="#">Доставка</a>
			 </div>	 
		     <div class="sidebar-3">
		         <a class="inner-sidebar-3" href="#">Оплата</a>
			 </div>	 
		     <div class="sidebar-4">
		         <a class="inner-sidebar-4" href="#">Акции</a>
		     </div>
	         <div class="sidebar-5">
		         <a class="inner-sidebar-5" href="#">Статьи</a>
			 </div>
		     <div class="sidebar-6">
		         <a class="inner-sidebar-6" href="#">Контакты</a>
		     </div>
			 </div>
            <div class="row">
            <div class="content-1">
                <a class="inner-content-1" href="#">Ваша услуга1</a>
                </div>
            <div class="content-2">
                <a class="inner-content-2" href="#">Ваша услуга2</a>
                </div>
            <div class="content-3">
                <a class="inner-content-3" href="#">Ваша услуга3</a>
                </div>
             <div class="content-4">
                <a class="inner-content-4" href="#">Ваша услуга4</a>
                 </div>
             <div class="content-5">
                <a class="inner-content-5" href="#">Ваша услуга5</a>
                 </div>
                <div class="content-6">
                 <p> <img src="image/Lighthouse.jpg" alt="Lighthouse" width="1000px" height="300px" /></p>
            </div>
            </div>    
            <div class="copy">© 2020 Viktor Yefimenko</div>
      </div>
		
	
    </body>
    </html>
*{
	box-sizing:border-box;
}

 body{
   background:#808080;
   color:#FFFFFF;
	font-size:30px;
     width: auto;
}
.row:after {
  visibility: hidden;
  display: block;
  font-size: 0;
  content: " ";
  clear: both;
  height: 0;
}
.row { display: inline-block; }
/* start commented backslash hack \*/
* html .row { height: 1%; }
.row { display: block; }
/* close commented backslash hack */

.header{
    margin: auto;
    background:#808080;
	height:150px;
	font-weight:auto;
}

.inner-header{
	text-align: center;
    font-family: 'Abril Fatface', cursive;
    height: 100px;
    width: 100px;
    color: blue;
    font-size: 75px;
}
.inner-header-1{
    float: right;
    margin: auto;
    border: 1px solid;
    border-radius: 55%;
    opacity: 35;
}

.sidebar-1{
	width:16.6%;
	float:left;
    background:#3C80EE;
	min-height:50px;
	text-align:center;
    margin-right: 1px;
}
.sidebar-2{
	width:16.6%;
	float:left;
    background:#5AA518;
	min-height:50px;
	text-align:center;
     margin-right: 1px;
}
.sidebar-3{
	width:16.6%;
	float:left;
    background:#D1AC26;
	min-height:50px;
	text-align:center;
     margin-right: 1px;
}
.sidebar-4{
	width:16.6%;
	float:left;
    background:#5132AB;
	min-height:50px;
	text-align:center;
     margin-right: 1px;
}
.sidebar-5{
	width:16.6%;
	float:left;
    background:#D24725;
	min-height:50px;
    text-align:center;
     margin-right: 1px;
}
.sidebar-6{
	width:16.6%;
	float:left;
    background:#AB338f;
	min-height:50px;
	text-align:center;
     margin-right: 1px;
    }

.inner-sidebar-1{
    text-decoration: none;
    transition: color .2s linear;
}
.inner-sidebar-2{
    text-decoration: none;
    transition: color .2s linear;
}
.inner-sidebar-3{
    text-decoration: none;
    transition: color .2s linear;
}
.inner-sidebar-4{
    text-decoration: none;
    transition: color .2s linear;
}
.inner-sidebar-5{
    text-decoration: none;
    transition: color .2s linear;
}
.inner-sidebar-6{
    text-decoration: none;
    transition: color .2s linear;
}

.inner-sidebar-1:hover{
    color: #F8FF00
}
.inner-sidebar-2:hover{
    color: #F8FF00
}
.inner-sidebar-3:hover{
    color: #F8FF00
}
.inner-sidebar-4:hover{
    color: #F8FF00
}
.inner-sidebar-5:hover{
    color: #F8FF00
}
.inner-sidebar-6:hover{
    color: #F8FF00
}

.row:after {
  visibility: hidden;
  display: block;
  font-size: 0;
  content: " ";
  clear: both;
  height: 0;
}
.row { display: inline-block; }
/* start commented backslash hack \*/
* html .row { height: 1%; }
.row { display: block; }
/* close commented backslash hack */
.inner-content-1{
    text-decoration: none;
    transition: color .3s linear;
}
.inner-content-2{
    text-decoration: none;
    transition: color .3s linear;}
.inner-content-3{
    text-decoration: none;
    transition: color .3s linear;}
.inner-content-4{
    text-decoration: none;
    transition: color .3s linear;}
.inner-content-5{
    text-decoration: none;
    transition: color .3s linear;}

.content-1{
	width:30%;
	padding:left;
    background:#BA1616;
	min-height:60px;
	text-align:center;
    margin-top: 5px;
}
.content-2{
	width:30%;
	padding:left;
    background:#BA1616;
	min-height:60px;
	text-align:center;
    margin-top: 5px;
}
.content-3{
	width:30%;
	padding:left;
    background:#BA1616;
	min-height:60px;
	text-align:center;
    margin-top: 5px;
}
.content-4{
	width:30%;
	padding:left;
    background:#BA1616;
	min-height:60px;
	text-align:center;
    margin-top: 5px;
}
.content-5{
	width:30%;
	padding:left;
    background:#BA1616;
	min-height:60px;
	text-align:center;
    margin-top: 5px;
}

.inner-content-1:hover{
        color: #F8FF00
}
.inner-content-2:hover{
        color: #F8FF00
}
.inner-content-3:hover{
        color: #F8FF00
}
.inner-content-4:hover{
        color: #F8FF00
}
.inner-content-5:hover{
        color: #F8FF00
}

.content-6{
    border: 2px dashed;
    color: deepskyblue;
    float: right;
    padding-bottom:-250px;
    margin-bottom: -1000px;
}

.social-links-footer{
    	width:30%;
	padding:auto;
	min-height:60px;
	text-align:center;
    margin-top: 5px;
}
