<!doctype html>
<html>
<head>
<title>Bootstrap</title>
<link	rel="stylesheet"	href="https://cdnjs.cloudflare.com/ajax/libs/font- awesome/6.4.0/css/all.min.css" integrity="sha512- iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eN BvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384- DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script	src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384- 9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384- w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
<link	rel="stylesheet"
href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384- TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">

</head>
<body>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
<a class="navbar-brand" href="#">Navbar</a>
<button class="navbar-toggler" type="button" data-toggle="collapse" data- target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria- expanded="false" aria-label="Toggle navigation">
<span class="navbar-toggler-icon"></span>
</button>

<div class="collapse navbar-collapse" id="navbarSupportedContent">
<ul class="navbar-nav mr-auto">
<li class="nav-item active">
<a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a> </li>
<li class="nav-item">
 
<a class="nav-link" href="#">Link</a>
</li>
<li class="nav-item dropdown">
<a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"> Dropdown
</a>
<div class="dropdown-menu" aria-labelledby="navbarDropdown">
<a class="dropdown-item" href="#">Action</a>
<a class="dropdown-item" href="#">Another action</a>
<div class="dropdown-divider"></div>
<a class="dropdown-item" href="#">Something else here</a> </div>
</li>
<li class="nav-item">
<a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
</li>
</ul>
<form class="form-inline my-2 my-lg-0">
<input	class="form-control	mr-sm-2"	type="search"	placeholder="Search"	aria- label="Search">
<button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
</form>
</div>
</nav>
<div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
<ol class="carousel-indicators">
<li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
<li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
<li data-target="#carouselExampleCaptions" data-slide-to="2"></li> </ol>
<div class="carousel-inner">
<div class="carousel-item active">
<img src="flower1.jpg" class="d-block w-100" alt="img">
<div class="carousel-caption d-none d-md-block">
<h5>First slide label</h5>
<p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p> </div>
</div>
<div class="carousel-item">
<img src="flower2.jpg" class="d-block w-100" alt="img">
<div class="carousel-caption d-none d-md-block">
<h5>Second slide label</h5>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p> </div>
</div>
<div class="carousel-item">
<img src="flower3.jpg" class="d-block w-100" alt="img">
 
<div class="carousel-caption d-none d-md-block">
<h5>Third slide label</h5>
<p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
</div>
</div>
</div>
<a	class="carousel-control-prev"	href="#carouselExampleCaptions"	role="button"	data- slide="prev">
<span class="carousel-control-prev-icon" aria-hidden="true"></span>
<span class="sr-only">Previous</span>
</a>
<a	class="carousel-control-next"	href="#carouselExampleCaptions"	role="button"	data- slide="next">
<span class="carousel-control-next-icon" aria-hidden="true"></span>
<span class="sr-only">Next</span>
</a>
</div>
<!-- Footer -->
<footer class="text-center text-lg-start bg-light text-muted">
<!-- Section: Social media -->
<section class="d-flex justify-content-center justify-content-lg-between p-4 border-bottom">
<!-- Left -->
<div class="me-5 d-none d-lg-block">
<span>Get connected with us on social networks:</span>
</div>
<!-- Left -->

<!-- Right -->
<div>
<a href="" class="me-4 text-reset">
<i class="fab fa-facebook-f"></i>
</a>
<a href="" class="me-4 text-reset">
<i class="fab fa-twitter"></i>
</a>
<a href="" class="me-4 text-reset">
<i class="fab fa-google"></i>
</a>
<a href="" class="me-4 text-reset">
<i class="fab fa-instagram"></i>
</a>
<a href="" class="me-4 text-reset">
 
<i class="fab fa-linkedin"></i>
</a>
<a href="" class="me-4 text-reset">
<i class="fab fa-github"></i>
</a>
</div>
<!-- Right -->
</section>
<!-- Section: Social media -->

<!-- Section: Links -->
<section class="">
<div class="container text-center text-md-start mt-5">
<!-- Grid row -->
<div class="row mt-3">
<!-- Grid column -->
<div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
<!-- Content -->
<h6 class="text-uppercase fw-bold mb-4">
<i class="fas fa-gem me-3"></i>Company name
</h6>
<p>
Here you can use rows and columns to organize your footer content. Lorem ipsum dolor sit amet, consectetur adipisicing elit.
</p>
</div>
<!-- Grid column -->

<!-- Grid column -->
<div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
<!-- Links -->
<h6 class="text-uppercase fw-bold mb-4"> Products
</h6>
<p>
<a href="#!" class="text-reset">Angular</a>
</p>
<p>
<a href="#!" class="text-reset">React</a>
</p>
<p>
<a href="#!" class="text-reset">Vue</a>
</p>
 
<p>
<a href="#!" class="text-reset">Laravel</a>
</p>
</div>
<!-- Grid column -->

<!-- Grid column -->
<div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
<!-- Links -->
<h6 class="text-uppercase fw-bold mb-4"> Useful links </h6>
<p>
<a href="#!" class="text-reset">Pricing</a>
</p>
<p>
<a href="#!" class="text-reset">Settings</a>
</p>
<p>
<a href="#!" class="text-reset">Orders</a>
</p>
<p>
<a href="#!" class="text-reset">Help</a>
</p>
</div>
<!-- Grid column -->

<!-- Grid column -->
<div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
<!-- Links -->
<h6 class="text-uppercase fw-bold mb-4">Contact</h6>
<p><i class="fas fa-home me-3"></i> New York, NY 10012, US</p>
<p>
<i class="fas fa-envelope me-3"></i> info@example.com
</p>
<p><i class="fas fa-phone me-3"></i> + 01 234 567 88</p>
<p><i class="fas fa-print me-3"></i> + 01 234 567 89</p>
</div>
<!-- Grid column -->
</div>
<!-- Grid row -->
</div>
 
</section>
<!-- Section: Links -->

<!-- Copyright -->
<div class="text-center p-4" style="background-color: rgba(0, 0, 0, 0.05);"> ©
2021 Copyright:
<a class="text-reset fw-bold" href="https://mdbootstrap.com/">MDBootstrap.com</a>
</div>
<!-- Copyright -->
</footer>
<!-- Footer -->
</body>
</html>
