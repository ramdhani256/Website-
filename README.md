<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IN NEED CHARITY UGANDA - Making a Difference</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* All your CSS styles remain exactly the same */
        :root {
            --primary: #2a7d2e;
            --primary-dark: #1e5c20;
            --secondary: #f9a825;
            --light: #f8f9fa;
            --dark: #343a40;
            --gray: #6c757d;
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: #f5f5f5;
        }

        /* ... (all your existing CSS remains exactly the same) ... */

        @media (max-width: 576px) {
            .hero h1 {
                font-size: 2rem;
            }
            
            .section {
                padding: 60px 0;
            }
            
            .stat-item {
                min-width: 150px;
            }
            
            .stat-number {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <div class="logo">
                <div class="logo-icon">
                    <i class="fas fa-hands-helping" style="color: #2a7d2e; font-size: 2rem;"></i>
                </div>
                <div class="logo-text">In Need Charity Uganda</div>
            </div>
            
            <div class="mobile-toggle">
                <i class="fas fa-bars"></i>
            </div>
            
            <ul class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#programs">Programs</a></li>
                <li><a href="#impact">Impact</a></li>
                <li><a href="#donate" class="btn">Donate Now</a></li>
            </ul>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h1>Transforming Lives in Uganda Through Compassion</h1>
                <p>We provide essential support to vulnerable communities across Uganda through education, healthcare, and sustainable development programs.</p>
                <div class="hero-btns">
                    <a href="#donate" class="btn">Donate Now</a>
                    <a href="#about" class="btn btn-secondary">Learn More</a>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section about" id="about">
        <div class="container">
            <h2 class="section-title">About Our Mission</h2>
            <div class="about-content">
                <div class="about-text">
                    <h2>Bringing Hope to Vulnerable Communities</h2>
                    <p>In Need Charity Uganda is a non-profit organization dedicated to alleviating poverty and promoting sustainable development in Uganda. Founded in 2019, we focus on Education, Qurban sacrifices, Aqiqah sacrifices, Feeding orphans, Masjid construction, Ramadan projects, water wells construction, healthcare, and community empowerment. Our mission is to create lasting change by supporting vulnerable populations with resources funded entirely by generous donations.</p>
                    <p>With the support of donors and volunteers from around the world, we've impacted over 50,000 lives through our various initiatives. Our approach combines immediate relief with long-term development strategies to create lasting change.</p>
                    <a href="#" class="btn">Read Our Story</a>
                </div>
                <div class="about-image">
                    <img src="https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Community in Uganda">
                </div>
            </div>
        </div>
    </section>

    <!-- Programs Section -->
    <section class="section programs" id="programs">
        <div class="container">
            <h2 class="section-title">Our Programs</h2>
            <div class="programs-grid">
                <div class="program-card">
                    <div class="program-image">
                        <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Education Program">
                    </div>
                    <div class="program-content">
                        <h3>Education Support</h3>
                        <p>We provide scholarships, school supplies, and infrastructure improvements to ensure children in rural communities have access to quality education.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
                
                <div class="program-card">
                    <div class="program-image">
                        <img src="https://images.unsplash.com/photo-1576091160399-112ba8d25d1f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Healthcare Program">
                    </div>
                    <div class="program-content">
                        <h3>Healthcare Access</h3>
                        <p>Our mobile clinics and community health workers provide essential medical services to remote areas with limited access to healthcare facilities.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
                
                <div class="program-card">
                    <div class="program-image">
                        <img src="https://images.unsplash.com/photo-1466692476868-aef1dfb1e735?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Agriculture Program">
                    </div>
                    <div class="program-content">
                        <h3>Sustainable Agriculture</h3>
                        <p>We train farmers in modern, sustainable farming techniques and provide resources to improve food security and generate income.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Impact Section -->
    <section class="section impact" id="impact">
        <div class="container">
            <h2 class="section-title">Our Impact</h2>
            
            <div class="impact-stats">
                <div class="stat-item">
                    <div class="stat-number">50,000+</div>
                    <div class="stat-text">Lives Impacted</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">120</div>
                    <div class="stat-text">Communities Served</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">2,500</div>
                    <div class="stat-text">Children Educated</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">50+</div>
                    <div class="stat-text">Projects Completed</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Additional Programs Section -->
    <section class="section programs" id="programs-detailed">
        <div class="container">
            <h2 class="section-title">Our Programs & Services</h2>
            <div class="programs-grid">
                <div class="program-card">
                    <div class="program-content">
                        <i class="fas fa-school" style="font-size: 3rem; color: var(--primary); margin-bottom: 20px;"></i>
                        <h3>Education Initiatives</h3>
                        <p>Providing school supplies, scholarships, and building classrooms for underprivileged children.</p>
                    </div>
                </div>
                <div class="program-card">
                    <div class="program-content">
                        <i class="fas fa-apple-alt" style="font-size: 3rem; color: var(--primary); margin-bottom: 20px;"></i>
                        <h3>Ramadan Projects</h3>
                        <p>Providing iftar and other essentials for needy families during the month of Ramadan.</p>
                    </div>
                </div>
                <div class="program-card">
                    <div class="program-content">
                        <i class="fas fa-cow" style="font-size: 3rem; color: var(--primary); margin-bottom: 20px;"></i>
                        <h3>Qurban Sacrifices</h3>
                        <p>We carry out Qurban sacrifices to supply and share not only meat but also happiness to our needy brothers and sisters.</p>
                    </div>
                </div>
                <div class="program-card">
                    <div class="program-content">
                        <i class="fas fa-heartbeat" style="font-size: 3rem; color: var(--primary); margin-bottom: 20px;"></i>
                        <h3>Healthcare Services</h3>
                        <p>Offering medical camps, vaccinations, and health education in rural areas.</p>
                    </div>
                </div>
                <div class="program-card">
                    <div class="program-content">
                        <i class="fas fa-mosque" style="font-size: 3rem; color: var(--primary); margin-bottom: 20px;"></i>
                        <h3>Masjid Construction</h3>
                        <p>Building places for praising the Almighty Allah to earn rewards.</p>
                    </div>
                </div>
                <div class="program-card">
                    <div class="program-content">
                        <i class="fas fa-baby" style="font-size: 3rem; color: var(--primary); margin-bottom: 20px;"></i>
                        <h3>Aqiqah Sacrifices</h3>
                        <p>Sacrifices done to thank the Almighty Allah for the blessing of a baby.</p>
                    </div>
                </div>
                <div class="program-card">
                    <div class="program-content">
                        <i class="fas fa-water" style="font-size: 3rem; color: var(--primary); margin-bottom: 20px;"></i>
                        <h3>Water Wells Construction</h3>
                        <p>Constructing water wells to provide clean and safe water to needy communities.</p>
                    </div>
                </div>
                <div class="program-card">
                    <div class="program-content">
                        <i class="fas fa-utensils" style="font-size: 3rem; color: var(--primary); margin-bottom: 20px;"></i>
                        <h3>Feeding the Orphans</h3>
                        <p>Providing food and hot meals to the needy and orphans to put smiles on their faces Insha Allah.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Donate Section -->
    <section class="section donate" id="donate">
        <div class="container">
            <h2 class="section-title">Make a Difference Today</h2>
            <p>Your donation helps us continue our vital work in Uganda. Every contribution counts!</p>
            
            <div class="donate-options">
                <div class="donate-option">
                    <div class="donate-amount">$25</div>
                    <div>Feeds a family for a week</div>
                </div>
                <div class="donate-option">
                    <div class="donate-amount">$50</div>
                    <div>School supplies for 5 children</div>
                </div>
                <div class="donate-option">
                    <div class="donate-amount">$100</div>
                    <div>Medical care for 10 people</div>
                </div>
                <div class="donate-option">
                    <div class="donate-amount">$500</div>
                    <div>Contribute to a water well</div>
                </div>
            </div>
            
            <div class="donate-form">
                <form id="donation-form">
                    <div class="form-group">
                        <label for="amount">Donation Amount (USD):</label>
                        <input type="number" id="amount" name="amount" min="1" required>
                    </div>
                    <div class="form-group">
                        <label for="name">Your Name:</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Your Email:</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <button type="submit" class="btn" style="width: 100%;">Donate Now</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section contact" id="contact" style="background-color: white;">
        <div class="container">
            <h2 class="section-title">Contact Us</h2>
            <p style="text-align: center; margin-bottom: 40px;">Get in touch for partnerships, volunteering, or more information.</p>
            
            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 50px;">
                <div>
                    <form id="contact-form">
                        <div class="form-group">
                            <label for="contact-name">Name:</label>
                            <input type="text" id="contact-name" name="name" required style="width: 100%; padding: 12px; border: 1px solid #ddd; border-radius: 4px;">
                        </div>
                        <div class="form-group">
                            <label for="contact-email">Email:</label>
                            <input type="email" id="contact-email" name="email" required style="width: 100%; padding: 12px; border: 1px solid #ddd; border-radius: 4px;">
                        </div>
                        <div class="form-group">
                            <label for="message">Message:</label>
                            <textarea id="message" name="message" required style="width: 100%; padding: 12px; border: 1px solid #ddd; border-radius: 4px; height: 150px;"></textarea>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
                
                <div class="contact-info">
                    <div style="margin-bottom: 25px;">
                        <p><i class="fas fa-map-marker-alt" style="color: var(--primary); margin-right: 10px;"></i> Mbale, Uganda</p>
                    </div>
                    <div style="margin-bottom: 25px;">
                        <p><i class="fas fa-phone" style="color: var(--primary); margin-right: 10px;"></i> +256 752 562067</p>
                    </div>
                    <div style="margin-bottom: 25px;">
                        <p><i class="fas fa-envelope" style="color: var(--primary); margin-right: 10px;"></i> ramadhaningujja@gmail.com</p>
                    </div>
                    <div style="margin-bottom: 25px;">
                        <p><i class="fas fa-envelope" style="color: var(--primary); margin-right: 10px;"></i> info@inneedcharityug.org</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>In Need Charity Uganda</h3>
                    <p>Transforming lives through compassion and sustainable development programs across Uganda.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-whatsapp"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#programs">Programs</a></li>
                        <li><a href="#impact">Our Impact</a></li>
                        <li><a href="#donate">Donate</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Contact Info</h3>
                    <p><i class="fas fa-map-marker-alt"></i> Mbale, Uganda</p>
                    <p><i class="fas fa-phone"></i> +256 752 562067</p>
                    <p><i class="fas fa-envelope"></i> info@inneedcharityug.org</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 In Need Charity Uganda. All rights reserved. | <a href="#" style="color: #adb5bd;">Privacy Policy</a></p>
            </div>
        </div>
    </footer>

    <script>
        // Simple JavaScript for mobile menu toggle
        document.addEventListener('DOMContentLoaded', function() {
            const mobileToggle = document.querySelector('.mobile-toggle');
            const navMenu = document.querySelector('.nav-menu');
            
            mobileToggle.addEventListener('click', function() {
                navMenu.classList.toggle('active');
            });
            
            // Close mobile menu when clicking on a link
            const navLinks = document.querySelectorAll('.nav-menu a');
            navLinks.forEach(link => {
                link.addEventListener('click', function() {
                    navMenu.classList.remove('active');
                });
            });
        });
    </script>
</body>
</html>
