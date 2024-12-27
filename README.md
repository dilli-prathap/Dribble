# Project Responsive Web Design using Bootstrap
## Date:
26-12-2024
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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmacy Company</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-success">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">MEDALL</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" href="#about">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="act2.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="act3.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="container-fluid bg-success text-white text-center p-5">
    <h1>Welcome to MEDALL</h1>
    <p>Your trusted partner for health and wellness</p>
  </div>

  <!-- About Section -->
  <div class="container my-5" id="about">
    <h2>About Us</h2>
    <p>PharmacyCo is dedicated to providing top-quality medicines and healthcare products. Our mission is to enhance the well-being of our customers through trusted products and services.</p>
  </div>

 
  <!-- Footer -->
  <footer class="text-center py-3 bg-light">
    <p>Designed and Developed by Dilli Prathap D</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

<!-- Hero Section -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
<div class="container-fluid bg-danger text-white text-center p-5">
   <h1>Welcome to MEDALL</h1>
   <p>Your trusted partner for health and wellness</p>
 </div>
 <div class="container my-5" id="products">
   <h2>Our Products</h2>
   <div class="row">
     <div class="col-md-4">
       <div class="card">
         <div class="card-body">
           <h5 class="card-title">Product 1</h5>
           <p class="card-text">Description of Product 1.</p>
         </div>
       </div>
     </div>
     <div class="col-md-4">
       <div class="card">
         <div class="card-body">
           <h5 class="card-title">Product 2</h5>
           <p class="card-text">Description of Product 2.</p>
         </div>
       </div>
     </div>
     <div class="col-md-4">
       <div class="card">
         <div class="card-body">
           <h5 class="card-title">Product 3</h5>
           <p class="card-text">Description of Product 3.</p>
         </div>
       </div>
     </div>
   </div>
 </div>

<!-- Hero Section -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
<div class="container-fluid bg-secondary text-white text-center p-5">
   <h1>Welcome to MEDALL</h1>
   <p>Your trusted partner for health and wellness</p>
 </div>
 <div class="container my-5" id="contact">
   <h2>Contact Us</h2>
   <form>
     <div class="mb-3">
       <label for="name" class="form-label">Name</label>
       <input type="text" class="form-control" id="name" placeholder="Your Name">
     </div>
     <div class="mb-3">
       <label for="email" class="form-label">Email</label>
       <input type="email" class="form-control" id="email" placeholder="Your Email">
     </div>
     <div class="mb-3">
       <label for="message" class="form-label">Message</label>
       <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
     </div>
     <button type="submit" class="btn btn-primary">Submit</button>
   </form>
 </div>
```


## OUTPUT:
![Screenshot 2024-12-27 194720](https://github.com/user-attachments/assets/630211a1-a3e5-4985-a226-38ebffd98a4a)
![Screenshot 2024-12-27 211422](https://github.com/user-attachments/assets/057cd84e-7842-496d-a9da-5559e66bd5ba)
![Screenshot 2024-12-27 211457](https://github.com/user-attachments/assets/536865a0-2912-4449-abb0-7c87f55c9e0d)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
