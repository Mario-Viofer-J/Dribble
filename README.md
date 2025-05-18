# Project Responsive Web Design using Bootstrap
## Date:18/05/2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background-color: #f8f9fa;
      padding: 80px 0;
      text-align: center;
    }
    .gallery {
      padding: 60px 0;
    }
    .gallery img {
      height: 200px;
      object-fit: cover;
    }
    footer {
      background-color: #343a40;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold text-dark" href="#">DribbbleClone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link text-dark" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link text-dark" href="#">Hire Designers</a></li>
          <li class="nav-item"><a class="nav-link text-dark" href="#">Learn</a></li>
          <li class="nav-item"><a class="nav-link btn btn-dark text-white ms-3" href="#">Sign up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="hero">
    <div class="container">
      <h1 class="display-4 fw-bold">Explore the best design work on the web</h1>
      <p class="lead mt-3">Join the community of designers and creative professionals showcasing their work.</p>
      <a href="#" class="btn btn-dark btn-lg mt-4">Start Exploring</a>
    </div>
  </section>

<section class="gallery">
  <div class="container">
    <div class="row g-4">
      <div class="col-6 col-md-4 col-lg-3">
        <div class="card">
          <img src="img1.png" class="card-img-top" alt="design1" />
          <div class="card-body">
            <h5 class="card-title">Modern Dashboard</h5>
            <p class="card-text text-muted">A sleek and responsive admin UI dashboard for SaaS platforms.</p>
          </div>
        </div>
      </div>

      <div class="col-6 col-md-4 col-lg-3">
        <div class="card">
          <img src="img2.png" class="card-img-top" alt="design2" />
          <div class="card-body">
            <h5 class="card-title">Mobile App UI</h5>
            <p class="card-text text-muted">Creative and user-friendly mobile interface for eCommerce.</p>
          </div>
        </div>
      </div>

      <div class="col-6 col-md-4 col-lg-3">
        <div class="card">
          <img src="img3.png" class="card-img-top" alt="design3" />
          <div class="card-body">
            <h5 class="card-title">Portfolio Website</h5>
            <p class="card-text text-muted">Minimalist portfolio template ideal for freelancers and designers.</p>
          </div>
        </div>
      </div>

      <div class="col-6 col-md-4 col-lg-3">
        <div class="card">
          <img src="img4.png" class="card-img-top" alt="design4" />
          <div class="card-body">
            <h5 class="card-title">Landing Page</h5>
            <p class="card-text text-muted">Conversion-focused landing page with bold typography and CTA.</p>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>


  <footer>
    <div class="container">
      <p class="mb-0">Designed by Mario Viofer</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

~~~


## OUTPUT:
![alt text](dribbbleweb.png)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
