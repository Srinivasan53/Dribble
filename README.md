# Project Responsive Web Design using Bootstrap
## Date:25.12.24

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
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav ml-auto">
          
          <li class="nav-item active">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <nav class="sorting-navbar">
    <div class="container d-flex justify-content-center">
      <ul class="nav">
        <li class="nav-item">
          <a class="nav-link active" href="#">Popular places</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Newest city</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Random place</a>
        </li>
      </ul>
    </div>
  </nav>

  <div class="container my-5">
    <div class="row g-4">
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="image-1.avif" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Taj Mahal</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="image-2.avif" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Mysore Palace</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="image-3.avif" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Ramanujar Temple </h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="image-4.avif" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">India Gate </h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="image-5.avif" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Thanjavur Temple</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="image-6.avif" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Tiruvannamalai Temple</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="image-7.avif" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Ratnagiri Arulmigu Murugan Temple</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="image-8.avif" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Isha Yoga Temple</h6>
          </div>
        </div>
      </div>
    </div>
  </div>

  <footer class="text-center py-3">
    <p>&copy; Developed by Srinivasan S</p>
  </footer>
</body>
</html>



```
## OUTPUT:
![alt text](<Screenshot (728).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
