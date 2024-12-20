<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Saifah Technologies</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <!-- AOS (Animate on Scroll) -->
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <style>
        .navbar {
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        #scrollToTopBtn {
            display: none;
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #f8d003;
            border: none;
            border-radius: 50%;
            padding: 15px;
            cursor: pointer;
        }
        #scrollToTopBtn i {
            font-size: 20px;
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header class="bg-dark text-white">
        <nav class="navbar navbar-expand-lg navbar-dark">
            <div class="container">
                <a class="navbar-brand" href="#">Saifah Technologies</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item"><a class="nav-link smooth-scroll" href="#about">About Us</a></li>
                        <li class="nav-item"><a class="nav-link smooth-scroll" href="#services">Our Solutions</a></li>
                        <li class="nav-item"><a class="nav-link smooth-scroll" href="#projects">Case Studies</a></li>
                        <li class="nav-item"><a class="nav-link smooth-scroll" href="#testimonials">Testimonials</a></li>
                        <li class="nav-item"><a class="nav-link smooth-scroll" href="#blog">Blog</a></li>
                        <li class="nav-item"><a class="nav-link smooth-scroll" href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Homepage Section -->
    <section class="hero bg-primary text-white text-center py-5" data-aos="fade-up">
        <div class="container">
            <h1 class="display-4">Empowering Innovation with Cutting-Edge Technology Solutions</h1>
            <p class="lead">At Saifah Technologies, we bring your business to the forefront of technological advancement with AI-driven solutions, robust software, and transformative services.</p>
            <a href="#services" class="btn btn-warning btn-lg smooth-scroll">Explore Our Solutions</a>
        </div>
    </section>

    <!-- Image Slider -->
    <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="image1.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Innovative Solutions</h5>
                    <p>Empowering businesses with state-of-the-art technology.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="image2.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>AI & Machine Learning</h5>
                    <p>Revolutionizing industries through data-driven insights.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="image3.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Cloud Solutions</h5>
                    <p>Secure and scalable cloud infrastructure for your business.</p>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-target="#carouselExampleCaptions" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-target="#carouselExampleCaptions" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </button>
    </div>

    <!-- About Us Section -->
    <section id="about" class="about-section py-5 bg-light" data-aos="fade-up">
        <div class="container">
            <h2 class="text-center mb-4">Who We Are</h2>
            <p class="lead text-center">Saifah Technologies is a leading provider of innovative technology solutions, specializing in AI, cloud computing, cybersecurity, and custom software development. We help businesses leverage cutting-edge technology to unlock new opportunities and accelerate growth.</p>
            <div class="row mt-4">
                <div class="col-md-3 text-center">
                    <div class="bg-warning text-white py-4 rounded">
                        <h3>Innovation</h3>
                    </div>
                </div>
                <div class="col-md-3 text-center">
                    <div class="bg-warning text-white py-4 rounded">
                        <h3>Integrity</h3>
                    </div>
                </div>
                <div class="col-md-3 text-center">
                    <div class="bg-warning text-white py-4 rounded">
                        <h3>Customer Focus</h3>
                    </div>
                </div>
                <div class="col-md-3 text-center">
                    <div class="bg-warning text-white py-4 rounded">
                        <h3>Excellence</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services-section py-5" data-aos="fade-up">
        <div class="container">
            <h2 class="text-center mb-4">Innovative Technology Solutions for Your Business</h2>
            <div class="row">
                <div class="col-md-3 mb-4">
                    <div class="card shadow">
                        <div class="card-body text-center">
                            <h5 class="card-title">AI & Machine Learning</h5>
                            <p class="card-text">Harness the power of AI to automate processes, enhance decision-making, and improve customer experiences.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 mb-4">
                    <div class="card shadow">
                        <div class="card-body text-center">
                            <h5 class="card-title">Custom Software Development</h5>
                            <p class="card-text">Develop scalable and secure software solutions tailored to meet your business needs.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 mb-4">
                    <div class="card shadow">
                        <div class="card-body text-center">
                            <h5 class="card-title">Cloud Computing</h5>
                            <p class="card-text">Build and manage secure, flexible cloud environments that enable seamless collaboration.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 mb-4">
                    <div class="card shadow">
                        <div class="card-body text-center">
                            <h5 class="card-title">Cybersecurity</h5>
                            <p class="card-text">Protect your business with state-of-the-art cybersecurity solutions designed to prevent, detect, and respond to threats.</p>
                        </div>
                    </div>
                </div>
            </div>
            <a href="#projects" class="btn btn-warning btn-lg d-block mx-auto smooth-scroll">Explore Case Studies</a>
        </div>
    </section>

    <!-- Client Testimonials Section -->
    <section id="testimonials" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">What Our Clients Say</h2>
            <div id="testimonialCarousel" class="carousel slide" data-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <p class="lead">"Saifah Technologies transformed our operations with their custom software solutions. Their team truly understands our needs!"</p>
                        <footer>- John Doe, CEO of XYZ Corp</footer>
                    </div>
                    <div class="carousel-item">
                        <p class="lead">"Their cloud migration service made our transition seamless and efficient. Highly recommend!"</p>
                        <footer>- Jane Smith, CTO of ABC Ltd.</footer>
                    </div>
                    <div class="carousel-item">
                        <p class="lead">"AI-driven insights from Saifah Technologies helped us make data-backed decisions that significantly boosted our growth."</p>
                        <footer>- Alice Johnson, Marketing Director at DEF Inc.</footer>
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-target="#testimonialCarousel" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-target="#testimonialCarousel" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </button>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section py-5 bg-dark text-white">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <form>
                <div class="form-group">
                    <input type="text" class="form-control" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                    <input type="email" class="form-control" placeholder="Your Email" required>
                </div>
                <div class="form-group">
                    <textarea class="form-control" placeholder="Your Message" rows="4" required></textarea>
                </div>
                <button type="submit" class="btn btn-warning btn-lg d-block mx-auto">Send Message</button>
            </form>
            <div id="map" class="mt-5" style="height: 400px;"></div>
        </div>
    </section>

    <!-- Scroll to Top Button -->
    <button id="scrollToTopBtn" class="btn btn-warning" title="Go to top">
        <i class="fa fa-arrow-up"></i>
    </button>

    <!-- Google Maps API Integration -->
    <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAPS_API_KEY&callback=initMap" async defer></script>
    <script>
        function initMap() {
            var myLocation = { lat: -34.397, lng: 150.644 }; // Replace with your coordinates
            var map = new google.maps.Map(document.getElementById('map'), {
                zoom: 15,
                center: myLocation
            });
            var marker = new google.maps.Marker({
                position: myLocation,
                map: map
            });
        }

        // Scroll to Top Functionality
        window.onscroll = function() {
            var btn = document.getElementById("scrollToTopBtn");
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                btn.style.display = "block";
            } else {
                btn.style.display = "none";
            }
        };

        document.getElementById("scrollToTopBtn").addEventListener("click", function() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
    </script>

    <!-- Bootstrap JS & jQuery -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <!-- AOS (Animate on Scroll) -->
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init();
    </script>
</body>

</html>
