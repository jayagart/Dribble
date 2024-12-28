# Project Responsive Web Design using Bootstrap
## Date:28/12/2024

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
    <title>Bootstrap Gallery</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold text-white" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse " id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item "><a class="nav-link" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                    
                    <input type="search" class="form-control w-auto" placeholder="Search" style="margin: 5px;">

                
                </ul>
            </div>
        </div>
    </nav>
    <nav class="navbar navbar-expand-lg navbar-light bg-second class">
        <div class="container-fluid">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-center  height" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Popular</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Shots</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Now</a>
                    </li>
                </ul>
            </div>
            <div>
                <button class="btn btn-outline-secondary"><i class="bg-dark bi-grid"></i></button>
            </div>
        </div>
    </nav>


    <section>
    
    <div class="bg-dark text-white py-4">
        <div class="container text-center">
            <h1>What are you working on?</h1>
            <p class="lead">Dribbble is show and tell for designers.</p>
            <button class="btn btn-primary">Learn more</button>
            <button class="btn btn-success">Sign up</button>
            <button class="btn btn-success">Sign in</button>
        </div>
    </div>

    </section>
    <section >
    <div class="container my-5">
        <div class="row">
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card">
                    <img src="im3.webp" class="card-img-top" >
                    <div class="card-body">
                        <p class="card-text">🔗 Fourplus Studio</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card">
                    <img src="im1.webp" class="card-img-top">
                    <div class="card-body">
                        <p class="card-text">🔗 Balkan Brothers</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card">
                    <img src="im2.webp" class="card-img-top" >
                    <div class="card-body">
                        <p class="card-text">🔗 Jan Losert</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card">
                    <img src="im4.webp" class="card-img-top">
                    <div class="card-body">
                        <p class="card-text">🔗 Mattias Johansson</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card">
                    <img src="im7.webp" class="card-img-top" >
                    <div class="card-body">
                        <p class="card-text">🔗 Muti</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card">
                    <img src="im8.webp" class="card-img-top" >
                    <div class="card-body">
                        <p class="card-text">🔗 One week wonders</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card">
                    <img src="im5.webp" class="card-img-top" >
                    <div class="card-body">
                        <p class="card-text">🔗 Dalibor Pajic</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card">
                    <img src="im6.webp" class="card-img-top">
                    <div class="card-body">
                        <p class="card-text">🔗 Illiyin Studio</p>
                    </div>
                </div>
            </div>

            
        </div>
    </div>
</section>

    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2024 All Rights Reserved by Jayagar.T</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


```

## OUTPUT:

![alt text](<jay/navapp/static/Screenshot 2024-12-28 181449.png>)
![alt text](<jay/navapp/static/Screenshot 2024-12-28 181456.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
