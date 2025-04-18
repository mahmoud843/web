<!DOCTYPE html>
<html lang="en" >
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع خدمات احترافي</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <div class="container">
                <a href="#" class="logo">
                    <img src="logo.svg" alt="logo">
                    
                </a>
                <ul class="nav-links">
                    <li><a href="#home">home</a></li>
                    <li><a href="#about">about us</a></li>
                    <li><a href="#services">our services</a></li>
                    <li><a href="#contact">contact</a></li>
                </ul>
                <div class="menu-toggle">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            </div>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-overlay"></div>
        <div class="container">
            <div class="hero-content">
                <h1>Innovative technical solutions to help you start your project</h1>
                <p>We provide integrated services to help you solve web problems.</p>
                <div class="hero-buttons">
                    <a href="#services" class="btn-main">see our services</a>
                    <a href="#contact" class="btn-secondary">contact</a>
                </div>
            </div>
        </div>
        <div class="scroll-down">
            <a href="#about"><i class="fas fa-chevron-down"></i></a>
        </div>
    </section>

  
    <section id="about" class="section">
        <div class="container">
            <div class="section-header">
                <h2>who we are?</h2>
                <p>a pro developers teeam</p>
            </div>
            <div class="about-content">
                <div class="about-text">
                    <h3>our massage</h3>
                    <p>  we are a startup company that start in 2022.</p>
                    <a href="#contact" class="btn-main">contact with us</a>
                </div>
            </div>
        </div>
    </section>


    <section id="services" class="section bg-light">
        <div class="container">
            <div class="section-header">
                <h2>services</h2>
                <p>we will solve all your problem</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-briefcase"></i>
                    </div>
                    <h3>Business consulting</h3>
                    <p>solve your problem in any code</p>
                    <a href="#" class="service-link">more</a><i class="fas fa-arrow-left"></i></a>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-code"></i>
                    </div>
                    <h3>develop website</h3>
                    <p>develop by html,css,js</p>
                    <a href="#" class="service-link">more<i class="fas fa-arrow-left"></i></a>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-paint-brush"></i>
                    </div>
                    <h3>connect to back-end</h3>
                    <p>we will help you to make a stable contact</p>
                    <a href="#" class="service-link">more</a><i class="fas fa-arrow-left"></i></a>
                </div>
            </div>
        </div>
    </section>


    <section id="contact" class="section">
        <div class="container">
            <div class="section-header">
                <h2>contact with us</h2>
                <p>we are here to help you</p>
            </div>
            <div class="contact-content">
                <div class="contact-info">
                    <div class="info-item">
                        <div class="info-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div class="info-text">
                            <h4>address</h4>
                            <p>cairo, egypt</p>
                        </div>
                    </div>
                    
                    
                    <div class="info-item">
                        <div class="info-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="info-text">
                            <h4>email</h4>
                            <p>info@example.com</p>
                        </div>
                    </div>
                    
                    <div class="social-media">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
                
                <div class="contact-form">
                    <form>
                        <div class="form-group">
                            <input type="text" placeholder="name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" placeholder="email" required>
                        </div>
                        <div class="form-group">
                            <input type="tel" placeholder="Number">
                        </div>
                        <div class="form-group">
                            <textarea placeholder="your massage" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn-main">submit</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-col">
                    <h3>our company</h3>
                    <p> a startup company in front-end</p>
                </div>
                
                <div class="footer-col">
                    <h3>quick contact</h3>
                    <ul>
                        <li><a href="#home">home</a></li>
                        <li><a href="#about">about</a></li>
                        <li><a href="#services">our services</a></li>
                        <li><a href="#contact">contact</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>our services</h3>
                    <ul>
                        <li><a href="#">Business consulting</a></li>
                        <li><a href="#">develop website</a></li>
                        <li><a href="#">connect to back-end</a></li>
                    </ul>
                </div>
            </div>
            
        </div>
    </footer>

</body>
</html>
