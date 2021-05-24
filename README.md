# coding

<!DOCTYPE html>
<html>
<head>

<title>MW Main Page</title>
<link rel="stylesheet" type="text/css" href="MW-Main-Page.css"/>
</head>

<body class="page">
<h1 class="title">MW</h1>
<h2>Pronounced: em double-u</h2>
<nav>
<img class="cart" src="Photo/Shopping Cart.jpg" alt="Shopping">
<p><a class="bio-link" href="MW-Bio-Page.html">Bio</a></p>
</nav>

<img class="main-logo" src="Photo/Business logo 1.png" alt="logo 1">
<p class="p1">Welcome to <b>"MW"</b> a home-based business where we sell products based on their respected sections.</p>

<a href="MW-Photo-Page.html"><img class="sub-logo2" src="Photo/Business logo 3.png" alt="logo 3"></a>
<p class="p3">This section takes you to a wide variety of beautiful Photographs of landscape, ocean, mountain views and the sky taken across North Wales and hopefully across the world soon.</p>

<a href="MW-Spice-Page.html"><img class="sub-logo1" src="Photo/Business logo 2.png" alt="logo 2"></a>
<p class="p2">This section takes you to a wide variety of spices made around the world and mixed together at home to make extremely nice flavours, perfect for making curry and chilli.</p>

<div class="footer">
<h1 class="footer-title">Contact details</h1>
<h3 class="email">Email Address: MWEnterprise@phonecoop.coop</h3>
<img class="gmail-logo" src="Photo/Gmail.jpg" alt="logo 4">
<h3 class="phone">Phone Number: 04867 443169</h3>
<img class="phone-logo" src="Photo/Phone.jpg" alt="logo 5">
<h3 class="instagram">Instagram: MW_Enterprise</h3>
<img class="instagram-logo" src="Photo/Instagram.jpg" alt="logo 6">
</div>
</body>
  
  .page {
	width: 100%;
	height: 1380px;
	border: 5px solid red;
	background: url('Photo/Business logo 1 bg.jpg');
	background-attachment: fixed;
	padding-right: 900px;
}

h2 {
	position: relative;
	left: 810px;
}

.cart {
	width: 70px;
	position: relative;
	top: 2px;
	left: 1662px;
}

* {
	padding: 0;
	margin: 0;
	text-decoration: none;
	list-style: none;
	box-sizing: border-box;
}

body {
	font-family: montserrat;
}

nav {
	background: red;
	height: 75px;
	width: 1897px;
}

.bio-link {
	position: relative;
	left: 1750px;
	bottom: 50px;
	font-family: 'lato', sans-serif;
	font-size: 25px;
}

.title {
	position: relative;
	left: 900px;
	font-size: 50px;
}

.main-logo {
	width: 350px;
	position: relative;
	left: 750px;
	top: 20px;
}

.p1 {
	position: relative;
	left: 650px;
	top: 25px;
	width: 500px;
	text-align: center;
	font-family: 'Rubik', sans-serif;
	font-size: 25px;
	box-sizing: content-box;
	border: 5px solid red;
	padding: 10px;
	background-color: white;
	border-radius: 10px;
}

.sub-logo2 {
	width: 200px;
	position: relative;
	bottom: 50px;
	left: 1400px;
}

.p3 {
	position: relative;
	left: 1225px;
	bottom: 25px;
	font-family: 'Rubik', sans-serif;
	width: 500px;
	text-align: center;
	font-size: 20px;
	box-sizing: content-box;
	border: 5px solid deepskyblue;
	padding: 10px;
	background-color: white;
	border-radius: 10px;
}

.sub-logo1 {
	width: 200px;
	position: relative;
	bottom: 448px;
	left: 265px;
}

.p2 {
	position: relative;
	bottom: 425px;
	left: 75px;
	font-family: 'Rubik', sans-serif;
	width: 500px;
	text-align: center;
	font-size: 20px;
	box-sizing: content-box;
	border: 5px solid orange;
	padding: 10px;
	background-color: white;
	border-radius: 10px;
}

.footer {
	padding: 20px;
	text-align: left;
	background: red;
	height: 250px;
	position: relative;
	bottom: 375px;
	width: 1897px;
	padding-right: 900px;
}

.footer-title {
	position: relative;
	left: 750px;
	font-size: 50px;
}

.email {
	position: relative;
	top: 30px;
	letter-spacing: 5px;
}

.gmail-logo {
	width: 50px;
	position: relative;
	left: 610px;
	top: 5px;
}

.phone {
	position: relative;
	top: 15px;
	letter-spacing:5px;
}

.phone-logo {
	width: 33px;
	position: relative;
	left: 375px;
	bottom: 10px;
}

.instagram {
	position: relative;
	top: 10px;
	letter-spacing: 5px;
}

.instagram-logo {
	width: 33px;
	position: relative;
	left: 350px;
	bottom: 15px;
}
