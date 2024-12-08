fitness goals
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Bodybuilding Journey | Personal Training</title>
    <!-- Google Fonts -->
    <link href="https://i.pinimg.com/474x/d4/f1/db/d4f1dba04d22f1360ee212126bfc605c.jpg" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }

        body {
            background: #f8f9fa;
            color: #333;
        }

        /* Header Section */
        header {
            background: linear-gradient(to right, #1e1e2e, #3b3b58);
            color: white;
            text-align: center;
            padding: 4rem 1rem;
            position: relative;
            overflow: hidden;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            animation: slideDown 1s ease-out;
        }

        header p {
            font-size: 1.2rem;
            animation: fadeIn 1.5s ease-out;
        }

        .cta-btn {
            display: inline-block;
            margin-top: 2rem;
            padding: 1rem 2rem;
            background: #e63946;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s ease;
        }

        .cta-btn:hover {
            background: #d62828;
        }

        /* Keyframe Animations */
        @keyframes slideDown {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* Section Styling */
        section {
            padding: 4rem 2rem;
            text-align: center;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            color: #1e1e2e;
        }

        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
        }

        .card {
            background: white;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            flex: 1 1 300px;
            text-align: left;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0px 8px 12px rgba(0, 0, 0, 0.2);
        }

        .card h3 {
            margin-bottom: 1rem;
            color: #e63946;
        }

        .card p {
            line-height: 1.6;
            color: #555;
        }

        /* Contact Section */
        #contact {
            background: linear-gradient(to right, #3b3b58, #1e1e2e);
            color: white;
            padding: 4rem 2rem;
            text-align: center;
        }

        #contact h2 {
            margin-bottom: 1rem;
        }

        #contact p {
            margin-bottom: 1.5rem;
        }

        footer {
            background: #1e1e2e;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        /* Image Gallery Section */
/* Gallery Section */
#gallery {
    text-align: center;
    padding: 4rem 2rem;
    background: #f4f4f4;
}

#gallery h2 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
    color: #333;
}

/* Image Grid Container */
.image-gallery {
    display: grid;
    grid-template-columns: repeat(6, 1fr); /* 6 equal-width columns */
    grid-gap: 1rem; /* Reduce spacing */
    justify-items: center;
    max-width: 900px; /* Restrict gallery width */
    margin: 0 auto; /* Center the gallery */
}

/* Individual Image Cards */
.image-card {
    position: relative;
    overflow: hidden;
    border-radius: 10px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s ease;
    max-width: 280px; /* Set a fixed max-width for smaller images */
}

.image-card img {
    width: 100%;
    height: auto;
    display: block;
    object-fit: cover;
    transition: transform 0.4s ease;
}

.image-card:hover img {
    transform: scale(1.1); /* Subtle zoom effect */
}

.overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: rgba(0, 0, 0, 0.7);
    color: white;
    padding: 0.8rem;
    opacity: 0;
    transform: translateY(100%);
    transition: opacity 0.3s ease, transform 0.3s ease;
    text-align: center;
    font-size: 0.9rem;
}

.image-card:hover .overlay {
    opacity: 1;
    transform: translateY(0);
}

/* Adjust Layout for Staggered Images */
.image-card:nth-child(1) {
    grid-column: span 2; /* Small but wide */
    grid-row: span 1;
}

.image-card:nth-child(2) {
    grid-column: span 2; /* Medium height */
    grid-row: span 2;
}

.image-card:nth-child(3) {
    grid-column: span 2; /* Small but wide */
    grid-row: span 1;
}
/* Contact Section */
#contact {
    text-align: center;
    padding: 2rem;
    background: #f4f4f4;
}

#contact h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: #333;
}

/* Social Links Container */
.social-links {
    display: flex;
    justify-content: center; /* Center icons */
    gap: 1.5rem; /* Spacing between icons */
    flex-wrap: wrap; /* Wrap to new line on small screens */
}

/* Social Icons */
.social-icon img {
    width: 50px; /* Adjust icon size */
    height: 50px;
    transition: transform 0.3s ease;
}

.social-icon img:hover {
    transform: scale(1.1); /* Zoom effect on hover */
}
@media (max-width: 600px) {
    .social-icon img {
        width: 40px; /* Smaller icons on mobile screens */
        height: 40px;
    }
}
.tip-box {
    background: #f4f4f4;
    border-left: 5px solid #007bff;
    padding: 1rem;
    margin: 1.5rem 0;
    font-size: 1rem;
    color: #333;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.tip-box h3 {
    margin: 0;
    font-size: 1.2rem;
    color: #007bff;
}
.image-container {
    position: relative;
    display: inline-block;
    text-align: center;
}

.image-container img {
    width: 100%;
    border-radius: 10px;
}

.caption {
    position: absolute;
    bottom: 10%;
    left: 50%;
    transform: translate(-50%, 0);
    background: rgba(0, 0, 0, 0.6);
    color: #fff;
    padding: 0.5rem 1rem;
    font-size: 1rem;
    border-radius: 5px;
}
.highlight-tip {
    position: absolute;
    top: 500px; /* Distance from the top */
    right: 20px; /* Distance from the right */
    width: 250px;
    background: #fff8e1;
    padding: 1rem;
    border: 1px solid #ffd54f;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.floating-tip {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #007bff;
    color: #fff;
    padding: 0.8rem;
    border-radius: 10px;
    font-size: 0.9rem;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
}
/* Gallery Section Styling */
#gallery {
    text-align: center;
    padding: 2rem 1rem;
    background: #f9f9f9;
}

#gallery h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: #333;
}

/* Image Grid Layout */
.image-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); /* Responsive grid */
    gap: 1rem; /* Space between images */
    margin: 1 auto;
    max-width: 1200px; /* Limit gallery width */
}

.image-item {
    position: relative;
    overflow: hidden;
    border-radius: 10px; /* Smooth corners */
    box-shadow: 0 4px 4px rgba(0, 0, 0, 0.1);
}

.image-item img {
    width: 100%; /* Make images responsive */
    height: 100%; /* Fixed height for uniformity */
    object-fit: cover; /* Ensure images fit nicely */
    transition: transform 0.3s ease;
}

.image-item:hover img {
    transform: scale(1.05); /* Slight zoom on hover */
}
#bodybuilding-journey {
    background: #1c1c1c;
    padding: 3rem;
    text-align: center;
    color: #fff;
    border-radius: 10px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
    position: relative;
    z-index: 1;
}

/* Title - Interactive with Hover Effect */
.journey-title h2 {
    font-size: 2.5rem;
    font-weight: bold;
    text-transform: uppercase;
    color: #f0f0f0;
    letter-spacing: 2px;
    transition: all 0.3s ease-in-out;
}

.journey-title h2:hover {
    color: #007bff; /* Blue color on hover */
    transform: scale(1.1); /* Slightly enlarge on hover */
}

/* Text - Animated Appearance */
.journey-text p {
    font-size: 1.2rem;
    line-height: 1.5;
    color: #ccc;
    opacity: 0;
    animation: fadeIn 2s forwards;
    animation-delay: 0.5s;
}

/* Animated Quote */
.quote {
    font-size: 1.5rem;
    font-style: italic;
    color: #ffcc00; /* Yellow color for emphasis */
    opacity: 0;
    animation: fadeIn 2s forwards;
    animation-delay: 1.5s;
}

/* Fade-In Animation */
@keyframes fadeIn {
    0% {
        opacity: 0;
        transform: translateY(20px);
    }
    100% {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Hover Effect on Text */
.journey-text p:hover {
    color: #80caff; /* Light blue color on hover */
    cursor: pointer;
    transform: translateY(-5px); /* Slightly lifts the text on hover */
    transition: all 0.2s ease-in-out;
}

/* Responsive adjustments */
@media (max-width: 768px) {
    #bodybuilding-journey {
        padding: 2rem;
    }
    .journey-title h2 {
        font-size: 2rem;
    }
    .journey-text p {
        font-size: 1rem;
    }
}


footer {
    background-color: #333;
    padding: 10px;
    text-align:left;
}

.footer-logo .logo {
    width: 100px; /* Adjust logo size for footer */
    margin-top: 10px;
    padding: 10px;
    border-radius: 25%;
}


    </style>
</head>
<body>
    

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Bodybuilding Journey</h1>
        <p>Your Transformation Starts Here</p>
        <a href="#contact" class="cta-btn">Start Your Journey</a>
    </header>
    

    <section id="gallery">
        <h2>My Fitness Highlights</h2>
        <div class="image-gallery">
            <!-- Image 1 -->
            <div class="image-item">
                <img src="food.jpg" alt="Healthy Food">
            </div>
            <div class="image-container">
                <img src="nut.jpg" alt="Healthy Food">
                <div class="caption">🥗 *"Nutrition is 80% of your results. Eat clean, train hard!"*</div>
            </div>
            
            <!-- Image 2 -->
            <div class="image-item">
                <img src="Fitness men and women.jpg" alt="Gym Scene">
            </div>
            <div class="tip-box">
                <h3>🔥 Quick Tip:</h3>
                <p>Consistency beats intensity. Start small, but stay consistent!</p>
            </div>
            
            <!-- Image 3 -->
            <div class="image-item">
                <img src="chris.jpg" alt="Workout Progress">
            </div>
            
            </section>
            <section id="bodybuilding-journey">
                <div class="journey-title">
                    <h2>My Bodybuilding Journey</h2>
                </div>
                <div class="journey-text">
                    <p>Starting from humble beginnings, my fitness journey is proof that consistency leads to results.</p>
                    <p class="quote">💪 <em>"Every expert was once a beginner. Keep pushing!"</em></p>
                </div>
            </section>
            
            <!-- Image 4 -->
            
            
            <p>Customized plans to suit your fitness goals.</p>
            <!-- Tip -->
            <div class="highlight-tip">
                <p>💡 *Tip: Always warm up before lifting to prevent injury and maximize your performance!*</p>
            </div>
        </section>
        
    </section>
    
    
    

    <!-- Personal Training Section -->
    <section id="training">
        <h2>Personal Training Program</h2>
        <p>Let me help you achieve your fitness goals with tailored training and nutrition guidance.</p>
        <div class="content">
            <div class="card">
                <h3>Customized Plans</h3>
                <p>Programs tailored to your fitness level and goals—whether it's muscle building, weight loss, or strength training.</p>
            </div>
            <div class="card">
                <h3>Holistic Approach</h3>
                <p>Combining physical workouts, nutrition, recovery, and mental health for sustainable results.</p>
            </div>
            <div class="card">
                <h3>Ongoing Support</h3>
                <p>Weekly check-ins, progress tracking, and motivation to keep you on track.</p>
            </div>
        </div>
        <a href="#contact" class="cta-btn">Get Started Today</a>
    </section>

    <section id="contact">
        <h2>Connect With Me</h2>
        <div class="social-links">
            <!-- Email -->
            <a href="mailto:your-email@example.com" target="_blank" class="social-icon">
                <img src="google.png" alt="Email">
            </a>
            <!-- Instagram -->
            <a href="https://instagram.com/leul_my2" target="_blank" class="social-icon">
                <img src="instagram.png" alt="Instagram">
            </a>
            <!-- YouTube -->
            <a href="https://youtube.com/imagine-x1y" target="_blank" class="social-icon">
                <img src="youtube.png" alt="YouTube">
            </a>
            <!-- Telegram -->
            <a href="https://t.me/dive2" target="_blank" class="social-icon">
                <img src="telegram.png" alt="Telegram">
            </a>
        </div>
    </section>
    

<!-- Icons -->
<div class="social-links">
    <a href="mailto:leulabiti98@gmail.com" target="_blank" class="social-icon">
        <i class="fa-solid fa-envelope"></i>
    </a>
    <a href="https://instagram.com/yourprofile" target="_blank" class="social-icon">
        <i class="fa-brands fa-instagram"></i>
    </a>
    <a href="https://youtube.com/yourchannel" target="_blank" class="social-icon">
        <i class="fa-brands fa-youtube"></i>
    </a>
    <a href="https://t.me/yourprofile" target="_blank" class="social-icon">
        <i class="fa-brands fa-telegram"></i>
    </a>
</div>

    </section>
    

    <!-- Footer -->
    <footer>
        
            <div class="footer-logo">
                <img src="logo.jpg" alt="Leul Logo" class="logo">
            </div>
        
        <p>&copy; 2024 Leul. All Rights Reserved.</p>
    </footer>
</body>
</html>
