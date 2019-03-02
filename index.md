---
layout: master
title: AroyD Thai restaurant
menuModal: menu.md
lunchModal: lunch.md
---
<!-- Page content -->
<div class="w3-content" style="max-width:1100px">

  <!-- About Section -->
  <div class="w3-row" id="about">
    <div class="w3-padding-small w3-hide-small">
     <img src="{{ site.url }}/assets//images/main.jpg" class="w3-round" alt="main" width="1100px" height="400px">
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
	<button class="w3-btn w3-round-xlarge w3-light-grey" onclick="$('#menuModal').show();" style="margin-bottom:20px;"><span style="font-size:40px;"><i class="fa fa-spinner" aria-hidden="true"></i> See our menu</span></button>
	<button class="w3-btn w3-round-large w3-light-grey" onclick="$('#lunchModal').show();"><span style="font-size:35px;"> Lunch specials <i class="fa fa-spinner" aria-hidden="true"></i></span></button></h1>
	Phone: (02) 4732 2362 to order <br/> or <br/>
	<a href="https://online.kaarot.com.au/aroyd-Penrith" class="w3-button w3-medium w3-white w3-border w3-round-xlarge" style="font-size:20px;text-decoration: none;">Order Online Now</a>
    </div>
    <div class="w3-col l6 w3-padding-large">
      <img src="{{ site.url }}/assets//images/chichencashew.jpg" class="w3-round w3-image" alt="Menu" width="500" height="750">
    </div>
  </div>

  <hr>

  <!-- Our food -->
  <div class="w3-row w3-padding-32" id="food">
    <div class="w3-col s5 w3-padding-large">
    <img src="{{ site.url }}/assets//images/freshingredients03.jpg" class="w3-round w3-image" style="margin-top:40%" alt="Menu" width="500" height="500"><br>
	<h3 class="w3-center">Fresh ingredients</h3>
   </div>
   <div class="w3-col s1 w3-padding-large" style="margin-top:20%">
   <i class="fa fa-angle-double-right" style="font-size:50px; color:grey;" aria-hidden="true"></i>
   </div>
   <div class="w3-col l6 w3-padding-large">
	<h1 class="w3-center">Our food</h1><br> 	
    <img src="{{ site.url }}/assets//images/gallery.jpg" class="w3-round w3-image" alt="Menu" width="500" height="750">
   </div>

  </div>

   <hr style="font-weight:bold">

   <div class="w3-row w3-padding-32" id="reviews">
   <div class="w3-col l7 w3-padding-large">
   <img src="{{ site.url }}/assets//images/truelocal.png" class="w3-round w3-image" alt="Menu" width="800" height="750">
   </div>
    <div class="w3-col l5 w3-padding-large" style="box-shadow: 5px 5px 2px #888888">
	 <h1 class="w3-center">Reviews</h1><br>
    <img src="{{ site.url }}/assets//images/truelocalReviews.png" class="w3-round w3-image" alt="Menu" width="400" height="750">
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
            <li>Mobile: 04 2212 8165 </li>
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

{% include {{page.menuModal}} %}
{% include {{page.lunchModal}} %}
