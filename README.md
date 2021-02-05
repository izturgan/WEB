# WEB
web midterm
<!DOCTYPE html>
<html>
<head>
	<title>iInfo - Official Apple Reseller</title>
	<link rel="stylesheet" href="midka.css">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@600&display=swap" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@100;200&display=swap" rel="stylesheet">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
	<link rel="shortcut icon" type="image/x-icon" href="apple.png" /> 	
</head>
<body> 
	<div class="container">
		<div class="toppane">
			iInfo
			<a href="https://www.apple.com/"><img src="applelogo2.png" width="45" height="55"></a>
		</div>
		<div class="leftpane">
  			<div class="leftpanetop">
  				<br><br><br>
				<a href="https://www.apple.com/iphone/"><img src="iphone.png" width="200" height="210"></a>
				<h2>iPhone</h2>
			</div>
			<div class="leftpanebottom">
				<br><br><br><br><br><br>
				<a href="https://www.apple.com/mac"><img src="28505-7-macbook-picture.png" width="200" height="120"></a>
				<h2>Mac</h2>
    		</div>
    	</div>
  	<div class="middlepane">
  		<h1 class="header"> Apple </h1>
  		<p class="info"> <b>Apple</b> is an American multinational technology company headquartered in Cupertino, California, that designs, develops, and sells consumer electronics, computer software, and online services. It is considered one of the <b>Big Five companies in the U.S.</b> information technology industry, along with Amazon, Google, Microsoft, and Facebook.</p>
  		<iframe width="800" height="450"
			src="https://www.youtube.com/embed/cnXapYkboRQ?autoplay=1">
		</iframe>
		<br>
		<a href="nextpage.html">
			<h2>More Info</h2>
		</a>
		<a href="accessories.html">
			<h2>Accessories</h2>
		</a>
  	</div>
 	<div class="rightpane">
		<div class="rightpanetop">
			<br>
			<br>
			<br>
			<a class="tablet" href="https://www.apple.com/ipad/"><img src="tablet.png" width="200" height="200"></a>		
 			<h2>iPad</h2>
 		</div>
 		<div class="rightpanebottom">
 			<br>
			<br>
			<br>
			<a href="https://www.apple.com/watch/"><img src="watch.png" width="200" height="200"></a>		
 			<h2>Watch</h2>
 		</div>
 	</div>

<footer>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<h2>Made by Nurgissa Izturgan</h2>
	<h3>+7(777) 777 77 77</h3>
	<a href="https://www.instagram.com/nurgiiss/" target="_"> <img src="https://cdn.freebiesupply.com/images/large/2x/instagram-icon-white-on-black-circle.png" height="50" width="60"> </a>  
	<a href="mailto:tasnur2002@gmail.com" target="_"> <img src="gmail.png"height="50" width="45"> </a> 
	<a href="https://vk.com/nurgissa" target="_"> <img src="vk.png"height="50" width="45"> </a>
</footer>
</body>
</html>
body, html {
  width: 100%;
  height: 100%;
  margin: 0;
}

.container {
  width: 100%;
  height: 100%;
}

h2{
  font-family: 'Raleway', sans-serif;
}

.leftpane {
  text-align: center;
  width: 15%;
  height: 100%;
  float: left;
  background-color: grey;
  border-collapse: collapse;
}

.leftpanetop{
  text-align: center;
}

.leftpanebottom{
  text-align: center;
}

.leftpanetop:hover{
  transition:  0.6s;
  -webkit-filter: invert(100%);
  filter: invert(100%);
}

.leftpanebottom:hover{
 transition:  0.6s; 
  -webkit-filter: invert(100%);
  filter: invert(100%);
}

.header{
    font-family: 'Oswald', sans-serif;
    font-size: 35px;
}

.info{
  padding-left: 100px;
  padding-right: 100px;
  font-family: 'Roboto', sans-serif;
}

.middlepane {
    text-align: center;
    width: 70%;
    height: 100%;
    float: left;
    background-color: white;
}

.rightpanetop:hover{
  transition:  0.6s;
  -webkit-filter: invert(100%);
  filter: invert(100%);
}

.rightpanebottom:hover{
  transition:  0.6s;
  -webkit-filter: invert(100%);
  filter: invert(100%);
}


.rightpane {
  -webkit-filter: invert(100%);
  filter: invert(100%);
  text-align: center;
  width: 15%;
  height: 100%;
  position: relative;
  float: right;
  background-color: grey;
  border-collapse: collapse;
}

.toppane {
  font-size: 70px;
  font-family: 'Roboto', sans-serif;
  color: white;
  width: 100%;
  height: 100px;
  padding-top: 4px;
  text-align: center;
  background-color: black;
}
a:link {
  color: black;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: black;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: black;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: black;
  background-color: transparent;
  text-decoration: underline;
}

footer{
  color: white;
  background-color: black;
  font-family: 'Awesome', sans-serif;
  text-align: center;
}
