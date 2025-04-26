# SkillScape
//html//

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SkillSpace - Online learning0 Platform</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <!-- Header/Navbar -->
    <header>
        <div class="container">
            <div class="logo">
                <h1><span>Skill</span>Space</h1>
            </div>
            <nav>
                <ul id="nav-menu">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#Roadmap">Roadmap</a></li>
                    <li><a href="#Resouces">Resouces</a></li>
                    <li><a href="#TopSkills">TopSkills</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#" class="btn btn-primary">Sign In</a></li>
                </ul>
                <div class="hamburger" id="hamburger">
                    <div class="bar"></div>
                    <div class="bar"></div>
                    <div class="bar"></div>
                </div>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h1>Learn Without Limits</h1>
                <p>Start, switch, or advance your career with Roadmap & Resouces of the top tech skills.</p>
                <div class="hero-buttons">
                    <a href="#" class="btn btn-primary">Access For Free</a>
                    <a href="#" class="btn btn-secondary">Learn More</a>
                </div>
            </div>
            <div class="hero-image">
                <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Students learning">
            </div>
        </div>
    </section>

    <!-- Courses Section -->
    <section class="courses" id="courses">
        <div class="container">
            <h2 class="section-title">Popular Courses</h2>
            <p class="section-subtitle">Browse our top courses</p>
            
            <div class="course-filter">
                <button class="filter-btn active" data-filter="all">All</button>
                <button class="filter-btn" data-filter="design">Design</button>
                <button class="filter-btn" data-filter="development">Development</button>
                <button class="filter-btn" data-filter="business">Business</button>
                <button class="filter-btn" data-filter="marketing">Marketing</button>
            </div>
            
            <div class="course-grid">
                <!-- Course items will be added dynamically by JavaScript -->
            </div>
            
            <div class="text-center">
                <a href="#" class="btn btn-outline">View All Courses</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <div class="about-image">
                <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="About EduLearn">
            </div>
            <div class="about-content">
                <h2 class="section-title">About SkillSpace</h2>
                <p>EduLearn is an online learning platform that offers anyone, anywhere, access to online courses and degrees from leading universities and companies.</p>
                <p>We partner with more than 275 leading universities and companies to bring flexible, affordable, job-relevant online learning to individuals and organizations worldwide.</p>
                <ul class="about-list">
                    <li><i class="fas fa-check-circle"></i> 5,000+ Online Courses</li>
                    <li><i class="fas fa-check-circle"></i> Expert Instructors</li>
                    <li><i class="fas fa-check-circle"></i> Lifetime Access</li>
                    <li><i class="fas fa-check-circle"></i> Money Back Guarantee</li>
                </ul>
                <a href="#" class="btn btn-primary">Learn More</a>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="features">
        <div class="container">
            <h2 class="section-title">Why Choose Us</h2>
            <p class="section-subtitle">Our Features</p>
            
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-laptop-code"></i>
                    </div>
                    <h3>Learn Anywhere</h3>
                    <p>Access your courses on mobile, desktop, or tablet with our responsive platform.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-chalkboard-teacher"></i>
                    </div>
                    <h3>Expert Teachers</h3>
                    <p>Learn from industry experts who are passionate about teaching.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-certificate"></i>
                    </div>
                    <h3>Certification</h3>
                    <p>Earn recognized certificates upon course completion.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-clock"></i>
                    </div>
                    <h3>Lifetime Access</h3>
                    <p>Get lifetime access to all course materials after enrollment.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-headset"></i>
                    </div>
                    <h3>24/7 Support</h3>
                    <p>Our support team is available round the clock to assist you.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3>Community</h3>
                    <p>Join a community of like-minded learners and grow together.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <h2 class="section-title">What Our Students Say</h2>
            <p class="section-subtitle">Success Stories</p>
            
            <div class="testimonial-slider">
                <div class="testimonial-slide active">
                    <div class="testimonial-content">
                        <div class="testimonial-text">
                            <p>"EduLearn has completely transformed my career. The courses are well-structured and taught by industry experts. I was able to land my dream job after completing the Full Stack Development course."</p>
                        </div>
                        <div class="testimonial-author">
                            <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="Sarah Johnson">
                            <div class="author-info">
                                <h4>Sarah Johnson</h4>
                                <p>Full Stack Developer</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-slide">
                    <div class="testimonial-content">
                        <div class="testimonial-text">
                            <p>"As a working professional, the flexibility of EduLearn's platform allowed me to upskill without compromising my job. The quality of content is exceptional and worth every penny."</p>
                        </div>
                        <div class="testimonial-author">
                            <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="Michael Chen">
                            <div class="author-info">
                                <h4>Michael Chen</h4>
                                <p>Marketing Manager</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-slide">
                    <div class="testimonial-content">
                        <div class="testimonial-text">
                            <p>"I've taken several courses on different platforms, but EduLearn stands out for its practical approach. The hands-on projects helped me build a portfolio that got me hired within weeks."</p>
                        </div>
                        <div class="testimonial-author">
                            <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Emily Rodriguez">
                            <div class="author-info">
                                <h4>Emily Rodriguez</h4>
                                <p>UI/UX Designer</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-controls">
                    <button class="prev-btn"><i class="fas fa-chevron-left"></i></button>
                    <div class="dots">
                        <span class="dot active"></span>
                        <span class="dot"></span>
                        <span class="dot"></span>
                    </div>
                    <button class="next-btn"><i class="fas fa-chevron-right"></i></button>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="newsletter">
        <div class="container">
            <div class="newsletter-content">
                <h2>Subscribe to Our Newsletter</h2>
                <p>Get the latest updates on new courses, special offers, and learning resources.</p>
            </div>
            <form class="newsletter-form">
                <input type="email" placeholder="Enter your email address" required>
                <button type="submit" class="btn btn-primary">Subscribe</button>
            </form>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <h2 class="section-title">Contact Us</h2>
            <p class="section-subtitle">We'd love to hear from you</p>
        
                    
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-phone-alt"></i>
                        </div>
                        <div class="contact-text">
                            <h3>Phone</h3>
                            <p>+91 8239973484</p>
                        </div>
                    </div>
                    
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="contact-text">
                            <h3>Email</h3>
                            <p>info@SkillSpace.com</p>
                        </div>
                    </div>
                    
                    <div class="contact-social">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                
                <form class="contact-form">
                    <div class="form-group">
                        <input type="text" placeholder="Your Name" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Your Email" required>
                    </div>
                    <div class="form-group">
                        <input type="text" placeholder="Subject">
                    </div>
                    <div class="form-group">
                        <textarea placeholder="Your Message" required></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>SkillSpace</h3>
                    <p>Empowering individuals and organizations through flexible, affordable, and job-relevant online learning.</p>
                    <div class="footer-social">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
                
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#courses">Courses</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#features">Features</a></li>
                        <li><a href="#testimonials">Testimonials</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Courses</h3>
                    <ul>
                        <li><a href="#">Web Development</a></li>
                        <li><a href="#">App Developer</a></li>
                        <li><a href="#">Blockchain</a></li>
                        <li><a href="#">Cyber Security</a></li>
                        <li><a href="#">UI/UX Design</a></li>
                        <li><a href="#">Data Science</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Support</h3>
                    <ul>
                        <li><a href="#">Help Center</a></li>
                        <li><a href="#">Terms of Service</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">Refund Policy</a></li>
                        <li><a href="#">FAQ</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2025 SkillSpace. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
