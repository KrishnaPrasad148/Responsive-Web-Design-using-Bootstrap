# Restaurant Website using Bootstrap

### Date: 20/11/2025  

---

## AIM:
To design and develop a Restaurant Website using HTML, CSS, and Bootstrap.



## DESIGN STEPS:

### Step 1:
Create the project folder and include the files  
`index.html` and `styles.css`.

### Step 2:
Link the **Bootstrap 5 CDN** for responsive design and layout components.

### Step 3:
Build a **sticky navigation bar** that collapses into a hamburger menu for smaller screens.

### Step 4:
Create a **full-screen hero section** with background overlays, animated text, and a call-to-action button.

### Step 5:
Add a **three-column Bootstrap card layout** with hover animations for:
- New Menu  
- Book a Table  
- Opening Hours  

### Step 6:
Add **animate.css** library for fade-in and zoom-in animations.

### Step 7:
Design a clean **footer section** and test the website on multiple screen sizes.



## PROGRAM:
```
Developed By: Krishna Prasad S  
Register No.: 212223230108  
```

### index.html :
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MEET n EAT</title>

  <!-- BOOTSTRAP -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  
  <!-- ANIMATIONS -->
  <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>

  <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-dark text-white">

<nav class="navbar navbar-expand-lg navbar-dark bg-black shadow-sm fixed-top">
  <div class="container">
    <a class="navbar-brand fw-bold fs-3" href="#">MEET n EAT</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="menu">
      <ul class="navbar-nav ms-auto gap-3">
        <li class="nav-item"><a class="nav-link" href="#">HOME</a></li>
        <li class="nav-item"><a class="nav-link" href="#">MENU</a></li>
        <li class="nav-item"><a class="nav-link" href="#">BOOK</a></li>
        <li class="nav-item"><a class="nav-link" href="#">ABOUT</a></li>
      </ul>
    </div>
  </div>
</nav>

<header class="hero d-flex align-items-center text-center text-white">
  <div class="container">
    <h1 class="display-3 animate__animated animate__fadeInDown">Juicy Bites, Happy Nights!</h1>
    <p class="lead animate__animated animate__fadeInUp animate__delay-1s">
      Taste the magic at MEET n EAT — the home of premium burgers.
    </p>
    <a href="#" class="btn btn-warning btn-lg mt-3 animate__animated animate__fadeInUp animate__delay-2s">
      Explore Menu
    </a>
  </div>
</header>

<section class="container my-5 pt-5">
  <div class="row g-4">
    <div class="col-md-4">
      <div class="card bg-secondary shadow-lg card-hover animate__animated animate__zoomIn">
        <img src="menu.jpg" class="card-img-top rounded-top">
        <div class="card-body">
          <h3 class="card-title">Our New Menu</h3>
          <p>Discover mouth-watering burgers and sizzling sides!</p>
          <a href="#" class="btn btn-outline-light btn-sm">See Menu</a>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card bg-secondary shadow-lg card-hover animate__animated animate__zoomIn animate__delay-1s">
        <img src="table2.jpg" class="card-img-top rounded-top">
        <div class="card-body">
          <h3 class="card-title">Book a Table</h3>
          <p>Reserve your seat and enjoy the perfect dining experience.</p>
          <a href="#" class="btn btn-outline-light btn-sm">Book Now</a>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card bg-secondary shadow-lg card-hover animate__animated animate__zoomIn animate__delay-2s">
        <img src="chef.jpg" class="card-img-top rounded-top">
        <div class="card-body">
          <h3 class="card-title">Opening Hours</h3>
          <ul>
            <li>Mon–Fri: 2pm – 10pm</li>
            <li>Sat: 2pm – 11pm</li>
            <li>Sun: 2pm – 9pm</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<footer class="text-center py-3 bg-black mt-5">
  <p class="m-0">© 2025 MEET n EAT | Designed with ❤️</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
```

### styles.css :
```css
/* HERO SECTION */
.hero {
  height: 100vh;
  background-image: url('burger.png');
  background-size: cover;
  background-position: center;
  background-blend-mode: darken;
  background-color: rgba(0, 0, 0, 0.6);
}

/* CARD HOVER ANIMATION */
.card-hover {
  transition: transform .3s, box-shadow .3s;
}

.card-hover:hover {
  transform: translateY(-10px);
  box-shadow: 0px 10px 25px rgba(255, 255, 255, 0.2);
}

body {
  color: white;
}

```

## OUTPUT:
<img width="1919" height="915" alt="Screenshot 2025-11-22 220049" src="https://github.com/user-attachments/assets/2c49d832-0a13-41ac-b31b-acf96894103b" />
<img width="1919" height="923" alt="Screenshot 2025-11-22 220058" src="https://github.com/user-attachments/assets/056cebda-af16-4de7-8b7a-c18ea2b5bb0c" />

## RESULT: 
The modern responsive Restaurant Website using Bootstrap was successfully created.
