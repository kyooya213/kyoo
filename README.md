<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astral Comshop - Your PC Build Business</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav class="navbar navbar-dark bg-dark fixed-top">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Astral Comshop</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
            <div class="offcanvas-header">
              <h5 class="offcanvas-title" id="Astral Comshop">Dark Astral</h5>
              <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
              <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="index.html">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Product</a>
                </li>
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    More content
                  </a>
                  <ul class="dropdown-menu dropdown-menu-dark">
                    <li><a class="dropdown-item" href="#">About us</a></li>
                    <li><a class="dropdown-item" href="#">Gallery</a></li>
                    <li>
                      <hr class="dropdown-divider">
                    </li>
                    <li><a class="dropdown-item" href="#">Service Guides</a></li>
                  </ul>
                </li>
              </ul>
              <form class="d-flex mt-3" role="search">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-success" type="submit">Search</button>
              </form>
            </div>
          </div>
        </div>
      </nav>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

    <!-- Astral Section -->
    <section class="Astral">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <h1>Custom PC Builds, Tailored to You</h1>
                    <p>Astral ComShop delivers high-performance custom PCs built with the best components, designed to meet your exact needs.</p>
                    <a href="#" class="btn btn-primary btn-lg">Get a Quote</a>
                </div>
                <div class="col-md-6">
                    <img src="Astral.jpg" alt="Custom PC" class="img-fluid">
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">Our Services</h2>
            <div class="row g-4"> <!--- Added g-4 for spacing between cards -->
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <i class="bi bi-tools"></i>
                            <h3 class="card-title">Custom PC Builds</h3>
                            <p class="card-text">We build custom PCs to your specifications, using the best components available.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <i class="bi bi-gear"></i>
                            <h3 class="card-title">PC Repair & Maintenance</h3>
                            <p class="card-text">We offer fast and reliable PC repair and maintenance services for all brands.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <i class="bi bi-cpu"></i>
                            <h3 class="card-title">Component Upgrades</h3>
                            <p class="card-text">Upgrade your existing PC with new components to enhance its performance.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <i class="bi bi-cloud-download"></i>
                            <h3 class="card-title">Software Installation</h3>
                            <p class="card-text">Need help with software installation? We've got you covered.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <i class="bi bi-shield-check"></i>
                            <h3 class="card-title">Virus Removal</h3>
                            <p class="card-text">Protect your PC from malware with our expert virus removal services.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section class="about py-5">
        <div class="container">
            <h2 class="text-center mb-4">About Us</h2>
            <p class="text-center">Astral ComShop is a team of passionate tech enthusiasts dedicated to providing top-notch PC services. We believe in delivering personalized solutions that empower you to achieve your computing goals.</p>
        </div>
    </section>

    <!-- Contact Us Section -->
    <section class="contact bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <div class="row">
                <div class="col-md-6">
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label">Your Name</label>
                            <input type="text" class="form-control" id="name" placeholder="Enter your name">
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Your Email</label>
                            <input type="email" class="form-control" id="email" placeholder="Enter your email">
                        </div>
                        <div class="mb-3">
                            <label for="message" class="form-label">Your Message</label>
                            <textarea class="form-control" id="message" rows="3" placeholder="Enter your message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
                <div class="col-md-6">
                    <h3 class="mb-3">Our Location</h3>
                    <p>123 Main Street, Cityville, CA 12345</p>
                    <h3 class="mb-3">Contact Information</h3>
                    <p>Phone: (123) 456-7890</p>
                    <p>Email: paditjemar213@gmail.com</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Me Section -->
    <section class="about-me py-5">
        <div class="container">
            <h2 class="text-center mb-4">About the Developer</h2>
            <p class="text-center">I'm a passionate PC Builder with a love for building beautiful and functional PC Tech. I enjoy exploring new technologies and creating innovative solutions.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-light py-3">
        <div class="container text-center">
            <p>&copy; 2025 Astral. All rights reserved.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/dist/js/bootstrap-icons.min.js"></script>
</body>
</html>
