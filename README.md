<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="style1.css"><!--external css-->  
<!--internal css-->  
<style> 

* {box-sizing: border-box;}

body { 
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.header {
  overflow: hidden;
  background-color: #221d1d;
  padding: 20px 10px;
}

.header a {
  float: left;
  color: rgb(231, 221, 221);
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px; 
 
  border-radius: 4px;
}

.logo {
 position: absolute;

}

.header a:hover {
  background-color: rgb(221, 106, 12);
  color: black;
}

.header a.active {
  background-color: rgb(194, 96, 16);
  color: white;
}

.header-right {
  float: right;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: rgb(221, 106, 12);
  color: black;
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

.dropdown-content a:hover {background-color: #f1f1f1;}

.dropdown:hover .dropdown-content {
  display: block;
}

}
</style>
</head>
<body>

<div class="header">
 <img src="poorvika_logo-01.png" width="310" height="100" style="margin-top: -20px ; margin-left: -10px; margin-bottom: -22px;" /></a>
  <div class="header-right">
    <ul>
      <li><a href="#home">Home</a></li>
      <li class="dropdown">
        <a href="javascript:void(0)" class="dropbtn">Service</a>
        <div class="dropdown-content">
          <a href="#">Repairs</a>
          <a href="#">Water damage</a>
          <a href="#">Display repairs</a>
        </div>
      </li>
      <li><a href="#news">News</a></li>
      
    </ul>
    </div>
  </div>
</div>
<h2 style="color:orange">ABOUT US</h2> <!---inline css-->
<h3 >
  Poorvika is the Largest Tech Retailer in India, spanning across 460+ showrooms in and around Tamil Nadu, Karnataka, Pondicherry, Mumbai, Pune and Trivandrum, famous for their touch & feel experience. Poorvika sells a wide category of devices in its showrooms and Online portal, ranging from the Best Smartphones, Laptops, Computers, Smart Devices, Smart TVs to Accessories. Poorvika's E-Commerce platform www.poorvika.com caters to customers across India where Customers can Comfortably Order their devices with just a tap and get them delivered Safely with delivery options such as 2 Hours Delivery, Same Day Delivery, Next Day Delivery, and a Pickup at the Store option based on their location. Having served over 5 Crore+ Happy Customers, Poorvika takes pride in being India's leading retailer for Top Brands like Apple, Samsung, Oppo, Vivo, Xiaomi, OnePlus, Redmi, Realme, Nokia, etc.
</h3>
<h2 style="color:orange">THE SECRET BEHIND OUR SUCCESS</h2> <!---inline css-->
<h3>Customer Satisfaction and Upholding their Trust has always been the priority for the Poorvika Brand. It is this Mission & Vision that all Poorvikans work towards, ensuring the highest standards of quality across all Poorvika Platforms, and there is no doubt that Poorvika will soon be the No.1 Online Retailer in the Country.</h3>
<img src="hj.jpg"  width="1350" height="600"/>

</html>
