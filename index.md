---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults

---

<title>AroyD Thai restaurant</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://www.w3schools.com/lib/w3.css">
<link rel="stylesheet" href="/assets/aroyd.css">
<link rel="stylesheet" href="/assets/font-awesome/css/font-awesome.min.css">
<script src="/assets/jquery-3.1.1.min.js"></script>

<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <ul class="w3-navbar w3-white w3-wide w3-padding-8 w3-card-2">
    <li>
      <h4 class="w3-margin-left">AroyD Thai restaurant</h4>
    </li>
    <!-- Right-sided navbar links. Hide them on small screens -->
    <li class="w3-right w3-hide-small">
      <a href="#menu" class="w3-left" onclick="$('#menuModal').show();">Menu</a>
      <a href="#food" class="w3-left">Our food</a>
	  <a href="#reviews" class="w3-left">Reviews</a>
      <a href="#contact" class="w3-left w3-margin-right">Contact</a>
    </li>
  </ul>
</div>

<!-- Header -->
<header class="w3-display-container w3-content w3-wide" style="max-width:1600px;min-width:500px" id="home">
  <div class="w3-display-bottomleft w3-padding-xlarge w3-opacity">
    <h1 class="w3-xxlarge">AroyD Thai restaurant</h1>
  </div>
</header>

<!-- Page content -->
<div class="w3-content" style="max-width:1100px">

  <!-- About Section -->
  <div class="w3-row" id="about">
    <div class="w3-padding-small w3-hide-small">
     <img src="/assets/images/main.jpg" class="w3-round" alt="main" width="1100px" height="400px">
    </div>

    <div class="w3-center">
      <h1 class="w3-center">About AroyD Thai</h1>
      <h5 class="w3-center">Authentic Thai Food</h5>           
    </div>
  </div>
  
  <hr>
  
  <!-- Menu Section -->
  <div class="w3-row w3-padding-32" id="menu">
    <div class="w3-col l6 w3-padding-large w3-center" style="margin-top:10%;">
      <h1 class="w3-center">
	<button class="w3-btn w3-round-xlarge w3-light-grey" onclick="$('#menuModal').show();"><span style="font-size:40px;"><i class="fa fa-spinner" aria-hidden="true"></i> See our menu</span></button></h1>
	Phone: (02) 4732 2362 to order
    </div>
    <div class="w3-col l6 w3-padding-large">
      <img src="/assets/images/chichencashew.jpg" class="w3-round w3-image" alt="Menu" width="500" height="750">
    </div>
  </div>

  <hr>
  
  <!-- Our food -->
  <div class="w3-row w3-padding-32" id="food">
    <div class="w3-col s5 w3-padding-large">
    <img src="/assets/images/freshingredients03.jpg" class="w3-round w3-image" style="margin-top:40%" alt="Menu" width="500" height="500"><br>
	<h3 class="w3-center">Fresh ingredients</h3>
   </div>
   <div class="w3-col s1 w3-padding-large" style="margin-top:20%">
   <i class="fa fa-angle-double-right" style="font-size:50px; color:grey;" aria-hidden="true"></i>
   </div>
   <div class="w3-col l6 w3-padding-large">
	<h1 class="w3-center">Our food</h1><br> 	
    <img src="/assets/images/gallery.jpg" class="w3-round w3-image" alt="Menu" width="500" height="750">
   </div>
 
  </div>
	
   <hr style="font-weight:bold">
  
   <div class="w3-row w3-padding-32" id="reviews"> 
   <div class="w3-col l7 w3-padding-large">
   <img src="/assets/images/truelocal.png" class="w3-round w3-image" alt="Menu" width="800" height="750">
   </div>
    <div class="w3-col l5 w3-padding-large" style="box-shadow: 5px 5px 2px #888888">
	 <h1 class="w3-center">Reviews</h1><br> 
    <img src="/assets/images/truelocalReviews.png" class="w3-round w3-image" alt="Menu" width="400" height="750">
   </div>
   
  </div>
  
  <hr>

  <!-- Contact Section -->
  <div class="w3-container w3-padding-32" id="contact">
  <div class="w3-col l6 w3-padding-large">
   <h1 class="w3-center">Contact us</h1><br>  
	<ul class="w3-ul w3-card-4">
    <li><h4>Business Hours</h4></li>
            <li>Lunch : Mon - Fri : 11h30 - 2h30 pm</li>
            <li>Dinner:  <br>
			Sun - Thurs : 5pm - 9h30  pm <br>
			Fri - Sat   : 5pm - 10h30 pm </li>            
            <li>251 High Street, Penrith, NSW 2750 </li>
            <li>Phone:  (02) 4732 2362 </li>
            <li>Mobbile: 04 2212 8165 </li>
            <li>Email: aroydthai@aroyd.com.au</li>
	</ul>
  </div>
  
<div class="w3-col l6 w3-padding-large">
<iframe
  width="500"
  height="450"
  frameborder="0" style="border:0"
  src="https://www.google.com/maps/embed/v1/place?key=AIzaSyALt8P7E-i6V5nzptu0FdhA_sf0foRG7tk&q=251+High+St,+Penrith+NSW+2750" allowfullscreen>
</iframe>
</div>  
   
<!-- End page content -->
</div>


<!-- The Modal -->
<div id="menuModal" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom"  style="width:80%" >
    <div class="w3-container">
      <span onclick="$('#menuModal').hide();"
      class="w3-closebtn">&times;</span>

<div>
<h1 class="w3-center" style="font-size:50px; color:#5d5b5b;">Aroy-D Menu</h1>
</div>

<div class="w3-center noticeFrame">
<div class="notice">
<h4>PICK UP DEALS</h4> <br>
Orders over $30
Receive a free 1.25L bottle of soft drink <br>

Orders over $70
Receive a free 1.25L bottle of soft drink and
1x serving of Spring Roll or Money Bag or Curry Puff <br>
</div>
<br>
<div class="notice">
<h4>ASK US ABOUT OUR TAKEAWAY LUCNH SPECIALS</h4><br>
Do you have food allergies?<br> 
Please let us know when you order.<br>
</div>
</div>


<div id="menuModalDishes" >
{% for g in site.data.menu.groups %}
<h2>{{g.description}}</h2>
{% for title in g.subTitles %}
<h6>{{title.name}}</h6>
{% endfor %}
<ul>
<!--each item-->
{% for item in g.items %}
{% assign price = {{item.price}}|lstrip  %}
<li>{{item.name}} <span class="w3-right">{% if price != '' %}  {{price}} {% endif %} </span> <br>
<span style="font-size:18px;">{{item.description}}</span>
</li>
{% endfor %}
</ul>
{% endfor %}
</div>	
</div>
</div>
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-12">
  <p><i class="fa fa-copyright" aria-hidden="true"></i> ARoy-D Thai Restaurant - 251 High street, Penrith, NSW 2750</p>
</footer>


