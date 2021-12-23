<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Document</title>
  <link rel="stylesheet" href="css/bootstrap.min.css" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.0/font/bootstrap-icons.css" />
  <link rel="stylesheet" href="css/style.css" />
</head>

<body>
  <nav class="navbar navbar-expand-lg container-fluid">
    <div class="container">
      <a class="navbar-brand" href="#">Arnob Roy</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="banner">
    <div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="./images/img-(1).png" class="d-block w-100" alt="..1.">
        </div>
        <div class="carousel-item">
          <img src="./images/img-(2).png" class="d-block w-100" alt="..2.">
        </div>
        <div class="carousel-item">
          <img src="./images/img-(3).png" class="d-block w-100" alt="..3.">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </section>
  <!-- Portfolio Section -->
  <section class="portfolio-section">
    <div class="container">
      <!--Sortable Galery-->
      <div class="sortable-masonry">
        <!--Filter-->
        <div class="filters">
          <ul class="filter-tabs filter-btns ">
            <li class="filter active" data-role="button" data-filter=".all">All Topics <span class="count">0</span></li>
            <li class="filter" data-role="button" data-filter=".cat-1">Business <span class="count">0</span></li>
            <li class="filter" data-role="button" data-filter=".cat-2">Coaching <span class="count">0</span></li>
            <li class="filter" data-role="button" data-filter=".cat-3">Financial <span class="count">0</span></li>
            <li class="filter" data-role="button" data-filter=".cat-4">Marketing <span class="count">0</span></li>
            <li class="filter" data-role="button" data-filter=".cat-5">Technical <span class="count">0</span></li>
          </ul>
        </div>

        <div class="items-container row">
          <div class="single-portfolio-area masonry-item all cat-1 col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <div class="image">
                <img src="images/gallery-1.png" alt="">
              </div>
              <div class="overlay">
                <div class="title"><span class="icon"><img
                      src="https://res.cloudinary.com/pwdsumon/image/upload/v1623674839/filter/icon.png"
                      alt=""></span>Precision</div>
                <div class="link-btn"><a href="#"><i class="fas fa-angle-right"></i>View</a></div>
                <div class="content">
                  <h5>Marketing</h5>
                  <h4>Business Leadership</h4>
                </div>
              </div>
            </div>
          </div>

          <!-- Case Block -->
          <div class="single-portfolio-area masonry-item all cat-2 col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <div class="image">
                <img src="images/gallery-2.png" alt="">
              </div>
              <div class="overlay">
                <div class="title"><span class="icon"><img
                      src="https://res.cloudinary.com/pwdsumon/image/upload/v1623674839/filter/icon.png"
                      alt=""></span>Precision</div>
                <div class="link-btn"><a href="#"><i class="fas fa-angle-right"></i>View</a></div>
                <div class="content">
                  <h5>Technical</h5>
                  <h4>Market Expansion</h4>
                </div>
              </div>
            </div>
          </div>

          <!-- Case Block -->
          <div class="single-portfolio-area masonry-item all cat-1 cat-2 cat-4 col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <div class="image">
                <img src="images/gallery-3.png" alt="">
              </div>
              <div class="overlay">
                <div class="title"><span class="icon"><img
                      src="https://res.cloudinary.com/pwdsumon/image/upload/v1623674839/filter/icon.png"
                      alt=""></span>Precision</div>
                <div class="link-btn"><a href="#"><i class="fas fa-angle-right"></i>View</a></div>
                <div class="content">
                  <h5>Coaching</h5>
                  <h4>Money Savings</h4>
                </div>
              </div>
            </div>
          </div>

          <!-- Case Block -->
          <div class="single-portfolio-area masonry-item all cat-5 cat-2 col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <div class="image">
                <img src="images/gallery-4.png" alt="">
              </div>
              <div class="overlay">
                <div class="title"><span class="icon"><img
                      src="https://res.cloudinary.com/pwdsumon/image/upload/v1623674839/filter/icon.png"
                      alt=""></span>Precision</div>
                <div class="link-btn"><a href="#"><i class="fas fa-angle-right"></i>View</a></div>
                <div class="content">
                  <h5>Business</h5>
                  <h4>Helthy Solutions</h4>
                </div>
              </div>
            </div>
          </div>

          <!-- Case Block -->
          <div class="single-portfolio-area masonry-item all cat-2 cat-1 col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <div class="image">
                <img src="images/gallery-5.png" alt="">
              </div>
              <div class="overlay">
                <div class="title"><span class="icon"><img
                      src="https://res.cloudinary.com/pwdsumon/image/upload/v1623674839/filter/icon.png"
                      alt=""></span>Precision</div>
                <div class="link-btn"><a href="#"><i class="fas fa-angle-right"></i>View</a></div>
                <div class="content">
                  <h5>Marketing</h5>
                  <h4>Startup Business</h4>
                </div>
              </div>
            </div>
          </div>

          <!-- Case Block -->
          <div class="single-portfolio-area masonry-item all cat-3 cat-5 col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <div class="image">
                <img src="images/gallery-6.png" alt="">
              </div>
              <div class="overlay">
                <div class="title"><span class="icon"><img
                      src="https://res.cloudinary.com/pwdsumon/image/upload/v1623674839/filter/icon.png"
                      alt=""></span>Precision</div>
                <div class="link-btn"><a href="#"><i class="fas fa-angle-right"></i>View</a></div>
                <div class="content">
                  <h5>Technical</h5>
                  <h4>Market Expansion</h4>
                </div>
              </div>
            </div>
          </div>

          <!-- Case Block -->
          <div class="single-portfolio-area masonry-item all cat-1 cat-3 col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <div class="image">
                <img src="images/gallery-7.png" alt="">
              </div>
              <div class="overlay">
                <div class="title"><span class="icon"><img
                      src="https://res.cloudinary.com/pwdsumon/image/upload/v1623674839/filter/icon.png"
                      alt=""></span>Precision</div>
                <div class="link-btn"><a href="#"><i class="fas fa-angle-right"></i>View</a></div>
                <div class="content">
                  <h5>Marketing</h5>
                  <h4>Business Leadership</h4>
                </div>
              </div>
            </div>
          </div>

          <!-- Case Block -->
          <div class="single-portfolio-area masonry-item all cat-1 col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <div class="image">
                <img src="images/gallery-8.png" alt="">
              </div>
              <div class="overlay">
                <div class="title"><span class="icon"><img
                      src="https://res.cloudinary.com/pwdsumon/image/upload/v1623674839/filter/icon.png"
                      alt=""></span>Precision</div>
                <div class="link-btn"><a href="#"><i class="fas fa-angle-right"></i>View</a></div>
                <div class="content">
                  <h5>Financial</h5>
                  <h4>Capital Management</h4>
                </div>
              </div>
            </div>
          </div>

          <!-- Case Block -->
          <div class="single-portfolio-area masonry-item all cat-4 cat-5 col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <div class="image">
                <img src="images/gallery-9.png" alt="">
              </div>
              <div class="overlay">
                <div class="title"><span class="icon"><img
                      src="https://res.cloudinary.com/pwdsumon/image/upload/v1623674839/filter/icon.png"
                      alt=""></span>Precision</div>
                <div class="link-btn"><a href="#"><i class="fas fa-angle-right"></i>View</a></div>
                <div class="content">
                  <h5>Financial</h5>
                  <h4>Capital Management</h4>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="link-btn text-center">
          <a href="#" class="theme-btn btn-style-one"><span class="btn-title">Load More</span></a>
        </div>
      </div>
    </div>
  </section>


  <!--Js Links Part Start-->
  <script src="js/jquery3.6.0.js"></script>
  <script src="js/popper.js"></script>
  <script src="js/bootstrap.bundle.min.js"></script>
  <script src="js/isotope.pkgd.min.js"></script>
  <script src="js/main.js"></script>
</body>

</html>
