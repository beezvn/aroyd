<!-- The Lunch Modal -->
<div id="lunchModal" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom"  style="width:90%" >
    <div class="w3-container">
      <span onclick="$('#lunchModal').hide();"
      class="w3-closebtn">&times;</span>

<div class="w3-center">
<h1 style="font-size:50px; color:#5d5b5b;">Aroy-D Lunch Specials</h1>
<h4>TAKEAWAY LUCNH SPECIALS $12.90 <br>  Curry and Rice : ONLY $7.90 </h4>
</div>

<div class="w3-center">
<h3>Do you have food allergies?
Please let us know when you order.</h3>
</div>

<div class="menuModalDishes" >
{% for g in site.data.lunch.groups %}
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
