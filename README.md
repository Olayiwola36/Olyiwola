<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Website Design</title>
    <!-- Link To CSS -->
    <link rel="stylesheet" href="style.css">
    <!-- Box Icons -->
    <link rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">
</head>
<body>
    <!-- Navbar -->
    <header>
        <div class="nav container">
            <a href="#" class="logo">Logo<span>.</span></a>
             <!-- Menu-Icon -->
             <input type="checkbox" name="" id="menu">
             <label for="menu" <i class='bx bx-menu' id="menu-icon"></i></label>
            <!-- Nav List -->
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Prices</a></li>
                <li><a href="#">Reviews</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
           
        </div>
    </header>
    <!-- Home -->
    <section class="home container" id="home">
        <div class="home-img">
            <img src="img/home.svg" alt="">
        </div>
        <div class="home-text">
            <h1>Responsive Website Design</h1>
            <p>Lorem ipsum dolor sit amet consectetur <br>adipisicing elit. Officia, earum!</p>
            <a href="#" class="btn">Sign Up</a>
        </div>
    </section>
    <!-- Services -->
    <section class="services" id="Services">
        <div class="heading">
            <h2>Services We Provides</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A <br> deserunt quas dolorum reiciendis totam accusamus?</p>
        </div>
        <!-- Content -->
        <div class="services-container container">
            <div class="box">
                <img src="img/services1.svg" alt="">
                <h2>HTML CSS Website</h2>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium porro dolorum deserunt nisi sunt unde.</p>
                <a href="#" class="s-btn">Get Service</a>
            </div>
            <div class="box">
                <img src="img/services2.svg" alt="">
                <h2>Design To Code</h2>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium porro dolorum deserunt nisi sunt unde.</p>
                <a href="#" class="s-btn">Get Service</a>
            </div>
            <div class="box">
                <img src="img/services3.svg" alt="">
                <h2>Clean Optimized Code</h2>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium porro dolorum deserunt nisi sunt unde.</p>
                <a href="#" class="s-btn">Get Service</a>
            </div>
            <div class="box">
                <img src="img/services4.svg" alt="">
                <h2>All Devices Responsive</h2>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium porro dolorum deserunt nisi sunt unde.</p>
                <a href="#" class="s-btn">Get Service</a>
            </div>
        </div>
    </section>
    <section class="contact container" id="contact">
        <div class="contact-img">
            <img src="img/contact.svg" alt="">
        </div>
        <a href="#" class="btn">Contact Us</a>
    </section>
    <!-- Copyright -->
    <div class="copyright container">
        <p>&#169; CarpoolVenom All Right Reserved</p>
        <div class="social">
            <a href="#"><i class='bx bxl-facebook' ></i></a>
            <a href="#"><i class='bx bxl-twitter' ></i></a>
            <a href="#"><i class='bx bxl-instagram' ></i></a>
        </div>
    </div>
    
</body>
</html>
