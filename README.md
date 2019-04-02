# y9web
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="mycss.css">
<link rel="icon" href="international.png" type="image/gif" sizes="16x16">
<style>
body {
  font-family: Arial;
  padding: -10px;
  margin:0;
  background-color: #B5D6DB;
  transition: background-color .5s;
}

.button {
  background-color: #11B0F4;
  padding: 15px 32px;
  text-align: center;
  font-size: 16px;
  margin: 4px 2px;
  position: fixed;
  top: 20px;
  right: 10px;
  border-radius: 50%;
}

.button2:hover {
  box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24),0 17px 50px 0 rgba(0,0,0,0.19);
}

.navbar {
  overflow: hidden;
  background-color: #299BB2;
}

.navbar a {
  float: left;
  color: #11A0F3;
  text-align: center;
  padding: 0px 30px;
  text-decoration: none;
  font-size: 24px;
}

.dropdown {
  float: left;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 30px;  
  border: none;
  outline: black;
  color: white;
  padding: 30px 30px;
  background-color: inherit;
  font-family: inherit;
  margin: 10;
}

.navbar a:hover, .dropdown:hover{
  background-color: #11B0F4 ;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #25606C;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 30px 30px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #08649A;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.sidenav {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: #111;
  overflow-x: hidden;
  transition: 0.5s;
  padding-top: 60px;
}

.sidenav a {
  padding: 8px 8px 8px 32px;
  text-decoration: none;
  font-size: 25px;
  color: #818181;
  display: block;
  transition: 0.3s;
}

.sidenav a:hover {
  color: #f1f1f1;
}

.sidenav .closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 50px;
}

.caption {
  position: absolute;
  top: 70px;
  left: 0;
  top: 25%;
  width: 100%;
  text-align: center;
  color: #000;
}

.caption span.border {
  color: #fff;
  padding: 18px;
  font-size: 60px;
  letter-spacing: 10px;
}

.bgimg-4 {
  background-image: url("gethelpnow.jpg");
  min-height: 100%;
}

p {
	color:#020202;
}

h3 {
  letter-spacing: 5px;
  text-transform: uppercase;
  font: 25px Lucida, Console, monospace;
  color: #fff;
  text-align: center;
}

table {
   position: absolute;
   top: 350px;
   left: 350px;

}

td {
	border: 1px solid black;
}

.flex-container {
  display: flex;
  justify-content:center;
  text-align: center;
}

.flex-container > div {
  background-color: #f1f1f1;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  width:300px;
  position: relative;
  top: 250px;
}

h1 {
	text-align: center;
	font-size: 60px;
}

#main {
  transition: margin-left .5s;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}

</style>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
  document.getElementById("main").style.marginLeft = "250px";
  document.body.style.backgroundColor = "rgba(0,0,0,0.4)";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
  document.getElementById("main").style.marginLeft= "0";
  document.body.style.backgroundColor = "#B5D6DB";
}
</script>
</head>
<body>

<div class="navbar">
  	  <a href="#home"><span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776; <img src="international.png" width="100px"> </span></a>
  <div class="dropdown">
    <button class="dropbtn">Data 
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">  
        <a href="worldmap.html">Globe Data</a>
        <a href="datas.html">Graph Data</a>
	</div>
	</div>
	<div class="dropdown">
    <button class="dropbtn">Need Help?
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">
      <a href="assess.html">Assessing the situation</a>
      <a href="comfort.html">Comforting a victim</a>
	</div>
    </div>
	<button class="button button2"><a href="gethelpnow.html">Get Help Now</a>
</div>


<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href="creating.html">Homepage</a>
  <a href="data.html">Data</a>
  <a href="needhelp.html">Need Help?</a>
  <a href="gethelpnow.html">Get Help Now</a>
   <a href="changes.html">Changes to design</a>
</div>

<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body, html {
  height: 100%;
  margin: 0;
  color: #777;
}

.bgimg-1, .bgimg-2, .bgimg-3 {
  position: relative;
  opacity: 0.65;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

}
.bgimg-1 {
  background-image: url("backgroundimg.jpg");
  min-height: 100%;
}

.bgimg-2 {
  background-image: url("img2.jpg");
  min-height: 600px;
}

.bgimg-3 {
  background-image: url("img3.jpg");
  min-height: 600px;
}

.caption {
  position: absolute;
  top: 50px;
  left: 0;
  top: 20%;
  width: 100%;
  text-align: center;
  color: #000;
}

.caption span.border {
  background-color: #111;
  color: #fff;
  padding: 18px;
  font-size: 80px;
  letter-spacing: 10px;
}

h3 {
  letter-spacing: 5px;
  text-transform: uppercase;
  font: 20px "Lato", sans-serif;
  color: #111;
}

</style>
</head>
<body>

<div class="bgimg-1">
  <div class="caption">
  <span class="border">Suicide Rates and Prevention</span>
  </div>
</div>

<div style="color: #777;background-color:white;text-align:center;padding:50px 80px;text-align: justify;">
  <h3 style="text-align:center;">Suicide</h3>
  <p>Suicide is the act of intentionally causing one's death. Those at risk include people with mental disorders such as depression, substance abuse, bipolar disorder, and schizophrenia; stress factors; and those who have previously attempted suicide are at a higher risk for future attempts Effective suicide prevention efforts include limiting access to methods of suicide—such as firearms, drugs, and poisons; treating mental disorders and substance misuse; proper media reporting of suicide; and improving economic conditions.</p>
</div>

<div class="bgimg-2">
  <div class="caption">
  <span class="border" style="background-color:transparent;font-size:25px;color: #f7f7f7;"></span>
  </div>
</div>

<div style="position:relative;">
  <div style="color:#ddd;background-color:#282E34;text-align:center;padding:50px 80px;text-align: justify;">
  <p>This website shows suicide rates among all countries around the world in the form or bar graphs and ways to prevent suicide with lists	 of phrases.</p>
  </div>
</div>

<div class="bgimg-3">
  <div class="caption">
  <span class="border" style="background-color:transparent;font-size:25px;color:#020202;">SCROLL UP TO GET STARTED</span>
  </div>
</div>

<div style="position:relative;">
  <div style="color:#ddd;background-color:#282E34;text-align:center;padding:50px 80px;text-align: justify;">
  <p>©Copyright 2019. All rights reserved. Trademark and other use of Suicide Rates and Prevention will result in 5 years imprisonment</p>
  </div>
</div>

<div id="main">
</div>










