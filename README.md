<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
  </head>
  <body>
                         <!-- header top -->
    <div class="container-fluid d-flex flex-column flex-md-row justify-content-around align-items-center bg-dark text-white gap-5 py-4">
        <div> 
           <span class="me-4"> <i class="bi bi-person-fill"></i> My Account </span>
           <span> <i class="bi bi-heart-fill pe-1"></i> Wishlist </span>
        </div>
        <div class="d-flex gap-4" >
            <a href="login.html" class="nav-link"> <i class="bi bi-box-arrow-in-right"></i> Log in </a>
            <a href="sign-up.html" class="nav-link"> <i class="bi bi-person-plus-fill"></i> Resister </a>
        </div>
    </div>
                         <!-- header top -->
                          <!-- Header Start Here -->
    <header class="sticky-top bg-dark-subtle">
        <div class="container">
            <nav class="navbar navbar-expand-lg navbar-dark-subtle">
  <div class="container-fluid">
    <a class="navbar-brand fw-bold fs-1 text-danger" href="#"> E-shOP </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="index.html"> Home </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html"> Product </a>
        </li>
         <li class="nav-item">
          <a class="nav-link" href="products.html"> Product-Details </a>
        </li>
         <li class="nav-item">
          <a class="nav-link" href="sign-up.html"> Sign Up  </a>
        </li>
         <li class="nav-item">
          <a class="nav-link" href="login.html"> Log In  </a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search"/>
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
      <a href="" class="position-relative ms-2">
        <i class="bi bi-cart-fill position-relative fs-4 text-dark">  </i>
        <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
                 3+
                 <span class="visually-hidden"> unread messages</span>
        </span>
      </a>
    </div>
  </div>
</nav>
        </div>
    </header>
                          <!-- Header End Here -->


                
                    <!-- Footer Start Here -->
 <footer class=" container-fluid d-lg-flex justify-content-around align-items-center bg-dark-subtle p-2 mt-3">
    <div class="social-media d-flex flex-column">
        <i class="bi bi-facebook fs-4 text-success"> </i>
        <i class="bi bi-messenger fs-4 text-success"></i>
        <i class="bi bi-whatsapp fs-4 text-success"></i>
        <i class="bi bi-envelope fs-4 text-success"></i>
    </div>
  <div class="quick-links">
        <h4> Product </h4>
        <p>  Menu </p>
        <p>  Review </p>
        <p>  Contact Us </p>
  </div>
  <div class="quick-links">
        <h4> Support  </h4>
        <p> Help Center </p>
        <p>  Report a bug  </p>
        <p>  Our Branches </p>
  </div>
</footer>
 <!-- copyright Section -->
  <div class="container-fluid text-lg-center bg-dark text-white p-3">
    <h6> Developer Team</h6>
Copyright © 2026 Spicy King Restaurant | All Rights Reserved
  </div> 
                    <!--Footer End Here -->


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
  </body>
</html>
