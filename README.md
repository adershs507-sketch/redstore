# redstore
redstore website



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>RedStore</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
  
  <link rel="stylesheet" href="style .css"><style>
    
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-transparent px-4">
  
  <a class="navbar-brand" href="#">
    <img src="images/logo.png" alt="RedStore Logo"> <!-- Replace with your logo -->
  </a>
  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item mx-2"><a class="nav-link" href="#">Home</a></li>
      <li class="nav-item mx-2"><a class="nav-link" href="products.html">Products</a></li>
      <li class="nav-item mx-2"><a class="nav-link" href="#">About</a></li>
      <li class="nav-item mx-2"><a class="nav-link" href="#">Contact</a></li>
      <li class="nav-item mx-2"><a class="nav-link" href="#">Account</a></li>
      <li class="nav-item mx-2"><a class="nav-link" href="#"><i class="bi bi-bag"></i></a>
      <li> <a href="cartred.html" class="cart"> <img src="images/cart.png" alt="" style="width: 20px; margin-right: 20%;"></a></li> 
    </ul>

  </div>
</nav>

<!-- Hero Section -->
<div class="container hero">
  <div class="row align-items-center">
    <div class="col-md-6 hero-text">
      <h1>Give Your Workout<br>A New Style !</h1>
      <p>Success isn't always about greatness. It's about consistency. Consistent<br>
         hard work gain success. Gretness will come.</p>
      <a href="#" class="btn btn-explore">Explore Now →</a>
    </div>
    <div class="col-md-6 hero-image text-center">
      <img src="images/image1.png" alt="Football Players"> <!-- Replace with your image -->
    </div>
  </div>
</div>



<div class="container mb-5">
  <div class="row text-center">
    <div class="col-md-4 col-12 mb-4 mb-md-0">
      <img src="images/category-1.jpg" class="img-fluid rounded" alt="Red Shoes">
    </div>
    <div class="col-md-4 col-12 mb-4 mb-md-0">
      <img src="images/category-2.jpg" class="img-fluid rounded" alt="Adidas Shoes">
    </div>
    <div class="col-md-4 col-12">
      <img src="images/category-3.jpg" class="img-fluid rounded" alt="White Hoodie">
    </div>
  </div>
</div>

<!-- Featured Products Heading -->
<div class="container">
  <h2 class="featured-heading">Featured Products</h2>

  <!-- Products Grid -->
  <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 g-4">

    <!-- Product 1 -->
    <div class="col" id="aa">
      <div class="product-card">
        <img src="images/product-1.jpg" alt="Red T-Shirt">
        <h6>Red Printed T-Shirt</h6>
        <div class="stars">★★★★☆</div>
        <div class="price">$50.00</div>
      </div>
    </div>

    <!-- Product 2 -->
    <div class="col">
      <div class="product-card">
        <img src="images/product-2.jpg" alt="Black Shoes">
        <h6>BLACK SHOES</h6>
        <div class="stars">★★★★☆</div>
        <div class="price">$50.00</div>
      </div>
    </div>

    <!-- Product 3 -->
    <div class="col">
      <div class="product-card">
        <img src="images/product-3.jpg" alt="Joggers">
        <h6>JOGGERS</h6>
        <div class="stars">★★★★☆</div>
        <div class="price">$50.00</div>
      </div>
    </div>

    <!-- Product 4 -->
    <div class="col">
      <div class="product-card">
        <img src="images/product-4.jpg" alt="Navy Polo">
        <h6>NAVY</h6>
        <div class="stars">★★★★☆</div>
        <div class="price">$50.00</div>
      </div>
    </div>

  </div>
</div>

<div class="container promo-section">
    <div class="row align-items-center">
      <!-- Image -->
      <div class="col-md-6 promo-image text-center">
        <img src="images/exclusive.png" alt="Smart Band 4">
        <!-- Replace with your actual image path -->
      </div>

      <!-- Text -->
      <div class="col-md-6 promo-text text-md-start text-center mt-4 mt-md-0">
        <p class="text-muted">Exclusive Available on RedStore</p>
        <h2 class="display-5">Smart Band 4</h2>
        <p class="text-muted">
          The Mi Smart Band 4 features a 39.9% larger (than Mi Band 3) AMOLED color full-touch display with adjustable brightness, so everything is clear as can be.
        </p>
        <button class="btn btn-custom mt-3">Buy Now →</button>
      </div>
    </div>
  </div>


<div class="container py-5">

  <!-- Testimonials -->
  <div class="row text-center mb-5">
    <div class="col-md-4 mb-4">
      <div class="testimonial-card">
        <i class="fas fa-quote-left mb-3"></i>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard...</p>
                <div class="stars">★★★☆</div>

        <div class="testimonial-stars">
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star-half-alt"></i>
        </div>
        <img src="images/user-1.png" alt="Sean Parker" class="testimonial-avatar">
        <div class="testimonial-name">Sean Parker</div>
      </div>
    </div>
    <div class="col-md-4 mb-4">
      <div class="testimonial-card">
        <i class="fas fa-quote-left mb-3"></i>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard...</p>
                <div class="stars">★★</div>

        <div class="testimonial-stars">
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star-half-alt"></i>
        </div>
        <img src="images/user-2.png" alt="Mike Smith" class="testimonial-avatar">
        <div class="testimonial-name">Mike Smith</div>
      </div>
    </div>
    <div class="col-md-4 mb-4">
      <div class="testimonial-card">
        <i class="fas fa-quote-left mb-3"></i>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard...</p>
                <div class="stars">★★★★</div>

        <div class="testimonial-stars">
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star-half-alt"></i>
        </div>
        <img src="images/user-3.png" alt="Mabel Joe" class="testimonial-avatar">
        <div class="testimonial-name">Mabel Joe</div>
      </div>
    </div>
  </div>

  <!-- Brand Logos -->
  <div class="row justify-content-center text-center brands-logos g-4">
    <div class="col-4 col-md-2">
      <img src="images/logo-godrej.png" alt="Godrej" class="img-fluid">
    </div>
    <div class="col-4 col-md-2">
      <img src="images/logo-oppo.png" alt="Oppo" class="img-fluid">
    </div>
    <div class="col-4 col-md-2">
      <img src="images/logo-coca-cola.png" alt="CocaCola" class="img-fluid">
    </div>
    <div class="col-4 col-md-2">
      <img src="images/logo-paypal.png" alt="PayPal" class="img-fluid">
    </div>
    <div class="col-4 col-md-2">
      <img src="images/logo-philips.png" alt="Philips" class="img-fluid">
    </div>
  </div>
</div>

<footer class="footer text-center text-md-start">
  <div class="container">
    <div class="row">
      
      <!-- App Download -->
      <div class="col-md-3 mb-4">
        <h6 class="fw-bold">Download our App</h6>
        <p>Download App for Android and iOS mobile phone.</p>
        <div class="d-flex justify-content-center justify-content-md-start gap-2">
          <img src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" alt="Google Play" width="120">
        </div>
      </div>

      <!-- Logo & Description -->
      <div class="col-md-6 mb-4 text-center">
        <div class="footer-logo">RED<span>STORE</span></div>
        <p class="mt-2">Our purpose is to sustainably make the pleasure and benefits of sports accessible to the many.</p>
      </div>
      <!-- Useful Links -->
      <div class="col-md-3 mb-4">
        <h6 class="fw-bold">Useful Links</h6>
        <ul class="list-unstyled">
          <li><a href="#">Coupons</a></li>
          <li><a href="#">Blog Post</a></li>
          <li><a href="#">Return Policy</a></li>
          <li><a href="#">Join Affiliate</a></li>
        </ul>
      </div>
    </div>

    <!-- Social Links -->
    <div class="row mt-4">
      <div class="col text-center">
        <h6 class="fw-bold">Follow us</h6>
        <div class="d-flex justify-content-center gap-3">
          <a href="#">Facebook</a>
          <a href="#">Twitter</a>
          <a href="#">Instagram</a>
          <a href="#">Youtube</a>
        </div>
      </div>
    </div>

    <!-- Copyright -->
    <div class="text-center mt-4">
      <small>Copyright 2025 - adersh.s</small>
    </div>
  </div>
</footer>

</body>
</html>
