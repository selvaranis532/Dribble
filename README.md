# Project Responsive Web Design using Bootstrap
## Date:27.12.2024

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
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-dark text-light">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#features">Features</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                    <li class="nav-item">
                        <a href="#signup" class="btn btn-success ms-2">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    
    <section class="text-center py-2 bg-secondary">
        <div class="container ">
            <h1 class="display-4 text-light">DISCOVER:WANDER AND WONDER</h1>
            <p class="lead text-light">EXPLORE THE BEAUTY OF TRAVEL THROUGH  CREATIVE DESIGNS</p>
            <img src="trav.jpg" width="300px" height="300px">
            <p>Journey through the art of travel and imagination </p>
        </div>
    </section>
    <section class="py-2 bg-dark">
        <div class="container">
            <h2 class="text-light text-center mb-4"> Featured Journey</h2>
            <div class="row g-4">
                <div class="col-6 col-md-4 col-lg-4">
                    <img src="trav.1.jpg"class="img-fluid rounded" alt="travel 1" >
                </div>
                <div class="col-6 col-md-2 col-lg-2">
                    <img src="trav.2.jpg" class="img-fluid rounded" alt="travel 2">
                </div>
                <div class="col-6 col-md-4 col-lg-5">
                    <img src="trav.3.jpg" class="img-fluid rounded" alt="travel 3">
                </div>
                <div class="col-6 col-md-2 col-lg-2">
                    <img src="trav.4.jpg" class="img-fluid rounded" alt="travel 4">
                </div>
                <div class="col-6 col-md-2 col-lg-2">
                    <img src="trav.5.jpg" class="img-fluid rounded" alt="travel 5">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="trav.6.jpg" class="img-fluid rounded" alt="travel 6">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="trav.7.jpg"class="img-fluid rounded" alt="travel 7" >
                </div>
            </div>
        </div>
    </section>
    
    <footer class="bg-secondary text-light py-3">
        <div class="container text-center">
            <p> Designed and developed by Selvarani</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
 ![alt text](<Screenshot (48).png>)          

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
