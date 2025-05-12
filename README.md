# Project Responsive Web Design using Bootstrap
## Date: 17.05.25

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Homepage</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-warning">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">SUDARSAN</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Designs</a></li>
          <li class="nav-item"><a class="nav-link" href="#">animes</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Team up!</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Collaboration</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="text-center py-5 bg-primary text-white">
    <h1>Welcome to Our site</h1>
    <p>Explore designs, anime recommendations, and more!</p>
    <a href="#" class="btn btn-warning">Get Started</a>
  </header>

  <!-- Main Content -->
  <div class="container py-5">
    <div class="row text-center">
      <div class="col-12">
        <h2>Featured Anime</h2>
      </div>
      <div class="col-md-4">
        <img src="images (4).jpeg" class="img-fluid" alt="Designer 1">
        <p>TALA</p>
      </div>
      <div class="col-md-4">
        <img src="16aeec16629cabe6728a06b84a523a32.jpg" class="img-fluid" alt="Designer 2">
        <p>KAI</p>
      </div>
      <div class="col-md-4">
        <img src="1062251-y1pynu_1dao16kntyrepx_s_tedturp38wk.jpg" class="img-fluid" alt="Designer 3">
        <p>TYSON</p>
      </div>
      <div class="col-md-4">
        <img src="images (1).jpeg" class="img-fluid" alt="Designer 4">
        <p>RAY</p>
      </div>
      <div class="col-md-4">
        <img src="images (2).jpeg" class="img-fluid" alt="Designer 4">
        <p>MAX</p>
      </div>
      <div class="col-md-4">
        <img src="images (3).jpeg" class="img-fluid" alt="Designer 4">
        <p>BROOKLYN</p>
      </div> 
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4">
    <p>&copy; DESIGNED AND DEVELOPED BY SUDARSAN.A All rights reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:

![Screenshot 2025-05-12 190805](https://github.com/user-attachments/assets/fa9b8933-199e-466b-bf55-3e38dd2a9f2c)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
