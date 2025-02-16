{% extends "base.html" %}
{% load static %}
{% block content %}

<!-- Navigation Bar (optional) -->
<nav class="navbar">
    <div class="navbar-container">
        <a href="/" class="navbar-logo">CareerOrien</a>
        <ul class="navbar-links">
            <li><a href="#about-us">About Us</a></li>
            <li><a href="#benefits">Benefits</a></li>
            <li><a href="#how-it-works">How It Works</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </div>
</nav>

<header class="hero">
    <div class="hero-container">
        <h1>Empower Your Career Journey</h1>
        <p>Discover your ideal career path, connect with mentors, and gain the skills needed to succeed.</p>
        <button class="button">Get Started</button>
    </div>
    <div class="hero-image">
        <img src="{% static 'images/career_orientation.jpeg' %}" alt="A person navigating their career journey with professional guidance" class="responsive-img">
    </div>
</header>

<section id="about-us" class="about-us">
    <h2>Our Mission</h2>
    <p>
        CareerOrien is committed to guiding individuals in their professional journeys by providing career advice, mentorship, and skills development.
        Our goal is to empower students, job seekers, and professionals with the right knowledge and connections to thrive in their careers.
    </p>
    <p>
        We envision a future where every individual has access to the guidance and resources needed to make informed career choices and achieve professional fulfillment.
    </p>
</section>

<section id="benefits" class="benefits">
    <h2>Why Choose CareerOrien?</h2>
    <div class="benefits-grid">
        <div class="benefit">
            <div class="benefit-image">
                <img src="{% static 'images/career1.jpeg' %}" alt="Career Advice Icon" class="responsive-img">
            </div>
            <div class="benefit-content">
                <h3>Expert Career Advice</h3>
                <p>Get personalized career recommendations from industry professionals and career coaches.</p>
            </div>
        </div>

        <div class="benefit">
            <div class="benefit-image">
                <img src="{% static 'images/career2.jpeg' %}" alt="Mentorship Icon" class="responsive-img">
            </div>
            <div class="benefit-content">
                <h3>Mentorship & Networking</h3>
                <p>Connect with experienced mentors and expand your professional network.</p>
            </div>
        </div>

        <div class="benefit">
            <div class="benefit-image">
                <img src="{% static 'images/career3.jpeg' %}" alt="Skills Training Icon" class="responsive-img">
            </div>
            <div class="benefit-content">
                <h3>Skill Development</h3>
                <p>Access courses and resources to improve your skills and enhance employability.</p>
            </div>
        </div>

        <div class="benefit">
            <div class="benefit-image">
                <img src="{% static 'images/career4.jpeg' %}" alt="Job Opportunities Icon" class="responsive-img">
            </div>
            <div class="benefit-content">
                <h3>Job Opportunities</h3>
                <p>Find job openings and internships that match your career goals.</p>
            </div>
        </div>
    </div>
</section>

<section id="how-it-works" class="how-it-works">
    <h2>How It Works</h2>
    <div class="how-it-works-grid">
        <div class="step">
            <h3>Step 1</h3>
            <p>Sign up to create your profile and access personalized career resources.</p>
        </div>
        <div class="step">
            <h3>Step 2</h3>
            <p>Get matched with mentors and receive career advice tailored to your goals.</p>
        </div>
        <div class="step">
            <h3>Step 3</h3>
            <p>Enhance your skills through curated training and find job opportunities.</p>
        </div>
    </div>
</section>

<footer id="contact">
    <div class="footer-content">
        <div class="contact-info">
            <h4>Contact</h4>
            <p>Email: support@careerorien.com</p>
            <p>Phone: +235 1234 5678</p>
            <p>Address: N'Djamena, Chad</p>
        </div>
    </div>
</footer>

{% endblock %}
