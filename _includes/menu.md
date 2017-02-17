<!-- The Modal -->
<div id="menuModal" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom"  style="width:90%" >
    <div class="w3-container">
      <span onclick="$('#menuModal').hide();"
      class="w3-closebtn">&times;</span>

<div>
<h1 class="w3-center" style="font-size:50px; color:#5d5b5b;">Aroy-D Menu</h1>
</div>

<div class="noticeFrame">
<div class="notice" style="width:50%; margin-bottom:40px;">
<h4 class="w3-center">PICK UP DEALS</h4>
<ul>
<li>
Order over $30 and receive a free 1.25L bottle of soft drink
</li>
<li>
Order over $70 and receive a free 1.25L bottle of soft drink and 1 x serving of Spring Roll or Money Bag or Curry Puff
</li>
</ul>
</div>
<br>


<button class="w3-btn w3-round-large w3-light-grey notice" onclick="$('#menuModal').hide(); $('#lunchModal').show();">
<h4>ASK US ABOUT OUR  <br> TAKEAWAY LUCNH <br> SPECIALS $12.90 <br></h4>
(Curry and Rice : $7.90)<br> <br>
Click here to see our lunch specials menu
</button>


</div>
<br>
<div class="w3-center">
<h3>Do you have food allergies?
Please let us know when you order.</h3>
</div>

<div class="menuModalDishes" >
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
