<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bootstrap5</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css">
  <link rel="stylesheet" href="style.css">

</head>

<body>
  <!-- nav bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark ps-5 py-1 fixed-top">
    <div class="container-fluid">
      <a class="navbar-brand fs-2 text-white my-2 me-5" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mb-2 mb-lg-0 ms-auto fs-4 px-3 me-auto text-center">
          <li class="nav-item px-4">
            <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item px-4">
            <a class="nav-link text-white" href="#">About</a>
          </li>
          <li class="nav-item px-4">
            <a class="nav-link text-white" href="#">Pages</a>
          </li>
          <li class="nav-item px-4">
            <a class="nav-link text-white" href="#">Contact</a>
          </li>

          <li class="nav-item dropdown px-4">
            <a class="nav-link dropdown-toggle text-white" href="#" id="navbarDropdown" role="button"
              data-bs-toggle="dropdown" aria-expanded="false">
              Services
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Action</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- carousel -->
  <div class="container-fluid mt-5 py-5 bg-dark">
    <div class="row">
      <div class="col">
        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">

          <!-- Indicators -->
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
              aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
              aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
              aria-label="Slide 3"></button>
          </div>

          <!-- Slides -->
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="./image/10016.jpg" class="d-block w-100 img-fluid" alt="First Slide">
              <div class="carousel-caption d-none d-sm-block">
                <h2 class="title">First Slide Label</h2>
                <p>Some representative placeholder content for the first slide.</p>
              </div>
            </div>

            <div class="carousel-item">
              <img src="./image/10014.jpg" class="d-block w-100 img-fluid" alt="Second Slide">
              <div class="carousel-caption d-none d-md-block">

                <h2 class="title">Second Slide Label</h2>
                <p>Some representative placeholder content for the second slide.</p>
              </div>
            </div>

            <div class="carousel-item">
              <img src="./image/10015.jpg" class="d-block w-100 img-fluid" alt="Third Slide">
              <div class="carousel-caption d-none d-lg-block">

                <h2 class="title">Third Slide Label</h2>
                <p>Some representative placeholder content for the third slide.</p>
              </div>
            </div>
          </div>

          <!-- Controls -->
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>

        </div>
      </div>
    </div>
  </div>
  <!-- para -->
  <div class="container">
    <div class="row mt-5">
      <div class="col">
        <h5 class="text-danger text-center">HOW</h5>
        <h1 class="fs-1 text-dark px-4 text-center my-3 ">We Provide The Quality With <br>Perfect Credibility</h1>
      </div>


    </div>
  </div>
  <!-- Para 2 -->
  <!-- section-1 -->
  <div class="container ps-5 py-4 text-dark mt-3">
    <div class="row">
      <div class="col-lg-4 col-md-6 col-sm-12 p-3">
        <i class="bi bi-chat-right-text-fill fs-1 p-3 ms-5"></i>
        <h2 class="title text-white">Perfext Planing</h2>
        <h5 class="fs-6 ">Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque officiis laboriosam ducimus
          repellendus. Impedit,.</h5>
        <h6 class="fs-4 mt-3">Read More <i class="bi bi-arrow-right-circle-fill ms-2"></i></h6>
      </div>
      <!-- section-2 -->
      <div class="col-lg-4 col-md-6 col-sm-12 p-3">
        <i class="bi bi-box-fill fs-1 ms-5 p-3"></i>
        <h2 class="title text-white">Perfext Planing</h2>
        <h5 class="fs-6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque officiis laboriosam ducimus
          repellendus. Impedit,.</h5>
        <h6 class="fs-4 mt-3">Read More <i class="bi bi-arrow-right-circle-fill ms-2"></i></h6>
      </div>
      <!-- section-3 -->
      <div class="col-lg-4 col-md-6 col-sm-12 p-3">
        <i class="bi bi-cloud-fill ms-5 p-3 fs-1"></i>
        <h2 class="title text-white">Perfext Planing</h2>
        <p class="fs-6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque officiis laboriosam ducimus
          repellendus. Impedit,.</p>
        <h6 class="fs-4 mt-3">Read More <i class="bi bi-arrow-right-circle-fill ms-2"></i></h6>
      </div>

    </div>
  </div>
  <!-- card section -->


  <div class="container py-4">
    <h5 class="title text-danger text-center p-3 mb-5"> Our Capability WHat We Do</h5>
    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 g-5">
      <!-- Card 1 -->
      <div class="col">
        <div class="card h-100">
          <img src="./image/10004.jpg" class="card-img-top" alt="">
          <div class="card-body bg-dark">
            <h5 class="card-title text-center mt-5 text-light mb-5">Perfect Planing</h5>
          </div>
        </div>
      </div>

      <!-- Duplicate the .col block for more cards -->
      <div class="col">
        <div class="card h-100">
          <img src="./image/10001.jpg" class="card-img-top" alt="">
          <div class="card-body bg-dark">
            <h5 class="card-title text-center text-light mt-5">Perfect Design</h5>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="card h-100">
          <img src="./image/10002.jpg" class="card-img-top" alt="">
          <div class="card-body bg-dark">
            <h5 class="card-title text-center text-light mt-5">Best Interior</h5>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="card h-100">
          <img src="./image/10005.jpg" class="card-img-top" alt="">
          <div class="card-body bg-dark">
            <h5 class="card-title text-center text-light mt-5">Furniture Design</h5>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- para and pic  -->
  <div class="container mt-3">
    <div class="row align-items-center">
      <!-- Left Section -->
      <div class="col-12 col-md-6">
        <h5 class="title text-danger p-2">------WHY US</h5>
        <h2 class="text-dark">We Offer You Professional Interior Design</h2>
        <p class="text-dark">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore nam assumenda sint architecto fugiat,
          accusantium, velit facilis esse, quas odit mollitia! Facere laboriosam quae voluptates ab. Voluptates laborum
          eos amet.
        </p>
        <button type="button" class="btn bg-danger px-3 text-light">Read More</button>
      </div>

      <!-- Right Section -->
      <div class="col-lg-3 col-md-6 col-sm-12">
        <img src="./image/10004.jpg" class="" style="width: 90%; height: 90; border-radius: 10px;" alt="Main Design">
      </div>

      <div class="col-lg-3 col-md-6 col-sm-12">
        <div class="row row-cols-1">
          <img src="./image/10018.jpg" class="mt-3" style="border-radius:20px;" alt="Design 1">
          <img src="./image/10003.jpg" class="mt-4" alt="Design 2" style="border-radius:20px;">
        </div>
      </div>
    </div>
  </div>
  </div>

  <!--Gallery  -->
  <div class="container mt-3 mb-2">
    <h5 class="text-center p-3 text-danger">----- Our Gallery</h5>
    <h2 class="fs-1 mb-4 text-center text-dark">Latest Project</h2>
    <div class="row g-3 p-3">
      <div class="col-12 col-sm-6 col-md-4">
        <img src="./image/10017.jpg" class="img-fluid rounded shadow" alt="Gallery 1">
      </div>
      <div class="col-12 col-sm-6 col-md-4">
        <img src="./image/10018.jpg" class="img-fluid rounded shadow" alt="Gallery 2">
      </div>
      <div class="col-12 col-sm-6 col-md-4">
        <img src="./image/10003.jpg" class="img-fluid rounded shadow" alt="Gallery 3">
      </div>
    </div>
    <div class="row g-3 p-3">
      <div class="col-12 col-sm-6 col-md-4">
        <img src="./image/10019.jpg" class="img-fluid rounded shadow" alt="Gallery 1">
      </div>
      <div class="col-12 col-sm-6 col-md-4">
        <img src="./image/10020.jpg" class="img-fluid rounded shadow" alt="Gallery 2">
      </div>
      <div class="col-12 col-sm-6 col-md-4">
        <img src="./image/10021.jpg" class="img-fluid rounded shadow" alt="Gallery 3">
      </div>
    </div>
    <div class="row g-3 p-3">
      <div class="col-12 col-sm-6 col-md-4">
        <img src="./image/10022.jpg" class="img-fluid rounded shadow" alt="Gallery 1">
      </div>
      <div class="col-12 col-sm-6 col-md-4">
        <img src="./image/10023.jpg" class="img-fluid rounded shadow" alt="Gallery 2">
      </div>
      <div class="col-12 col-sm-6 col-md-4">
        <img src="./image/10024.jpg" class="img-fluid rounded shadow" alt="Gallery 3">
      </div>
    </div>
  </div>
  <div class="container">
    <div class="row">
    <h6 class="text-danger mt-5 p-2">----- UNIQUEUE DESIGN</h6>
      <h1 class="">Create Your Future With Affection</h1>
      
      <div class="col-sm-12 col-lg-6 col-md-6">
        <p class="text-secondary  fw-bold fs4 mt-3">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Optio praesentium, at exercitationem, illo
          placeat est velit quis quod, alias nisi obcaecati ullam culpa quidem! Veniam perspiciatis fugiat nesciunt
          quidem at!</p>
          <div class="d-inline-flex"> 
             <div class="d-flex">
            <div class="d-inline-flex align-items-center">
              <i class="bi bi-images fs-1"></i></div>
            <div class="mt-5 ms-2">
              <p class="fs-1 fw-bold ms-4" style="margin-bottom:5px;">2025
          <p class="text-danger fs-3 fw-bold ms-3 mb-5">Sucessfull Project</p>
          </p>
        </div>
          </div>
           <div class="d-flex px-3">
            <div class="d-inline-flex align-items-center">
              <i class="bi bi-person-lines-fill fs-1"></i></div>
            <div class="mt-5 ms-2">
              <p class="fs-1 fw-bold ms-4" style="margin-bottom:5px;">1060
          <p class="text-danger fs-3 fw-bold ms-3 mb-5">Happy Clients</p>
          </p>
        </div>
      </div>
      </div>
    </div>
     <div class="col-sm-12 col-lg-3 col-md-6">
    <img class="w-100 rounded" src="image/10002.jpg"></div>

     <div class="col-sm-12 col-lg-3 col-md-6">
      <img class="w-100 rounded" src="image/10005.jpg" alt="">
     </div>
      
  </div>
  </div>





  <!-- script -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
    crossorigin="anonymous"></script>
</body>

</html>
