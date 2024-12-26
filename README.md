# Project Responsive Web Design using Bootstrap
## Date:26/12/2024

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
<html>
<head>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>


<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
 <div class="container">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
            
</button>
<div class="collapse navbar-collapse" id="navbarNav">
<ul class="navbar-nav ml-auto">
<li class="nav-item active" >
<a class="nav-link" href="#">Home</a>
</li>
<li class="nav-item ">
<a class="nav-link" href="#">Explore</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#">Sign in</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#">Sign up</a>
</li>
</ul>
</div>
</div>
</nav>

    
    <section class="bg-info text-darkest text-center py-5">
        <div class="container">
            <h1 class="display-4">Mingle</h1>
            <p class="lead">Here you can see stunning visual pictures and many arts, articles.</p>
            <a href="#" class="btn btn-light btn-lg">Mingle with us</a>
        </div>
    </section>

    
    <section class="py-5 bg-light">
    <div class="container text-center">
    <h2 class="mb-4 text-dark">Explore...</h2>
    <p class="lead mb-4 text-muted">Mingle is a versatile, multi-purpose platform designed to bring people, ideas, and opportunities together. Whether you're looking to connect with others, explore new content, promote your business, or access valuable tools, Mingle has something for everyone..</p>
    <div class="row">
            
    <div class="col-md-4 mb-4">
    <div class="card shadow-sm border-light">
    <img src="im2.jpeg" class="card-img-top" alt="Shot 1">
    <div class="card-body">
    <h5 class="card-title text-primary">Super cars</h5>
    <p class="card-text text-muted"> From roaring engines to sleek aerodynamics, supercars ignite passion and command attention on every road they grace...</p>
    </div>
    </div>
    </div>
    
    <div class="col-md-4 mb-4">
    <div class="card shadow-sm border-dark">
    <img src="im3.jpg" class="card-img-top" alt="Shot 2">
    <div class="card-body">
    <h5 class="card-title text-primary">Universe News</h5>
    <p class="card-text text-muted">Stay updated with the wonders of the cosmos with the latest universe news. From groundbreaking discoveries in astronomy to the mysteries of distant galaxies, we bring you the most fascinating stories about our ever-expanding universe...</p>
    </div>
    </div>
    </div>
            
        <div class="col-md-4 mb-4">
        <div class="card shadow-sm border-light">
        <img src="im1.jpg" class="card-img-top" alt="Shot 3">
        <div class="card-body">
        <h5 class="card-title text-primary ">World visuals</h5>
        <p class="card-text text-muted">Experience the beauty of our planet through stunning world visuals. From breathtaking landscapes and vibrant cityscapes to cultural moments and natural wonders, each image tells a story of Earth's diversity and splendor...</p>
        </div>
        </div>
        </div>
        </div>
        </div>
    </section>


    <footer class="bg-dark text-white py-4 text-center">
        <p class="mb-0">&copy;Desingned & Developed by Jayagar.T</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

   
</body>
</html>



```

## OUTPUT:

![alt text](<jay/navapp/static/Screenshot 2024-12-26 184200.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
