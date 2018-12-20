# coffee
<%@ page language="java" contentType="text/html; charset=ISO-8859-1"
	pageEncoding="ISO-8859-1"%>
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
<style>
#rcorners5 {
    border-radius: 15px 50px;
     padding: 20px; 
    width: 70px;
    height: 50px;    
} 
#rcorners4 {
    border-radius: 15px 50px;
     padding: 20px; 
    width: 300px;
    height: 250px;    
} 
#rcorners3 {
    border-radius: 15px 50px;
     padding: 20px; 
    width: 200px;
    height: 150px;    
} 
h3.one {
    border-top-style: dotted;
    border-right-style: dotted;
    border-bottom-style: dotted;
    border-left-style: dotted;
    border-color: red;
}

ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
}

li a, .dropbtn {
    display: inline-block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
    background-color: red;
}

li.dropdown {
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {background-color: #f1f1f1}

.dropdown:hover .dropdown-content {
    display: block;
}
h1 {
    text-shadow: 2px 2px red;
}

</style>
<meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
<title>Coffee House</title>

</head>

<body bgcolor="black">
<ul>
  <li><a href="google.com">News</a></li>
  <li><a href="#contact">Whats New</a></li>
  <li><a href="Gallery.jsp">Gallery</a></li>
  <li><a href="#about">Home Delivery</a></li>
  <li><a href="#news">Contact Us</a></li>
  <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">Cafe Menu</a>
    <div class="dropdown-content">
      <a href="#">Food</a>
      <a href="#">Beverages</a>
      <a href="#">Combos</a>
    </div>
  </li>
</ul>

	<center>
		<img src="pic4.jpg" id="rcorners4">
		<h1 style="font-size: 300%">
			<font>COFFEE HOUSE</font>
		</h1>
	</center>
	<form action="Xmlservlet" method="post">
		<table style="color:red;">
			<tr>
				<td><h3>${message}</h3>
				<h3>${successmessage}</h3> </td>
			</tr>
			<tr>
				<td><h3 style="color:red;">Login!!!</h3></td>
			</tr>
			<tr>
				<td style="color:red;">UserName:</td><td><input type="text"  name="username"></td>
			</tr>
			<tr>
				<td style="color:red;">Password:</td><td><input type="password"  name="password1"></td>
			</tr>
			<tr>
				<td><input type="submit"  name="submit" value="login"></td><td style="color:red;"><a href="Form.jsp">Registration</a></td>
			</tr>
		</table>
	</form>

	<marquee>
		<img src="pic8.jpg" height="200" width="250" id="rcorners3"><img id="rcorners3"
			src="pic9.jpg" height="200" width="250"><img id="rcorners3" src="pic10.jpg"
			height="200" width="250"><img id="rcorners3" src="pic11.jpg" height="200"
			width="250"><img id="rcorners3" src="pic12.jpg" height="200" width="250">
		<img id="rcorners3" src="pic14.jpg" height="200" width="250"> <img id="rcorners3"
			src="pic16.jpg" height="200" width="250">
	</marquee>

	<h1 class="one" style="font-size: 300%" align="center">
		ABOUT US
		<p style="font-size: 75%" >
			<font>A coffee house is an Italian coffee drink
				which is traditionally prepared with espresso, hot milk and steamed
				milk foam. Cream may be used instead of milk and is often topped
				with cinnamon.It is typically smaller in volume than a caffe latte,
				with a thicker layer of micro foam. The name comes from the Capuchin
				friars, referring to the colour of their habits, and in this context
				referring to the colour of the beverage when milk is added in small
				portion to dark, brewed coffee (today mostly espresso). The physical
				appearance of a modern cappuccino with espresso coffee and steamed
				milk is a result of a long evolution of the drink.</font>
		</p>
		<div>
		Follow Us
		<p><img src="follow1.png" id="rcorners5">
		<img src="follow2.png" id="rcorners5">
		<img src="follow3.png" id="rcorners5">
		<img src="follow4.png" id="rcorners5"></p>
	
		</h1>
</body>
</html>
