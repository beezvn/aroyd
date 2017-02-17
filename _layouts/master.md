<!doctype html>
<html lang="en">
<head>

<title>{{ site.title }}</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="{{ site.url }}/assets/w3.css">
<link rel="stylesheet" href="{{ site.url }}/assets/aroyd.css">
<link rel="stylesheet" href="{{ site.url }}/assets/font-awesome/css/font-awesome.min.css">
<script src="{{ site.url }}/assets/jquery-3.1.1.min.js"></script>

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
{{ content }}

<!-- Footer -->

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-12">
  <p><i class="fa fa-copyright" aria-hidden="true"></i> ARoy-D Thai Restaurant - 251 High street, Penrith, NSW 2750</p>
</footer>


</body>

</html>
