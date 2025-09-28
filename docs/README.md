---
home: false
---

<div class="hero-section">
  <nav class="top-nav">
    <a href="#content">Resume</a>
    <a href="#contact" class="contact-btn">Contact</a>
  </nav>
  
  <div class="hero-content">
    <h1 class="hero-title">I'M Majd Samer Askar</h1>
    <p class="hero-subtitle">A Software Engineer</p>
  </div>
  
  <div class="scroll-indicator">
    <a href="#content" class="scroll-arrow">
      <span>↓</span>
    </a>
  </div>
  
  <footer class="hero-footer">
    <div class="footer-content">
      <p class="copyright">© 2024 Majd. All rights reserved.</p>
      <div class="social-icons">
        <a href="https://www.linkedin.com/in/majd-askar-47a141330" target="_blank">💼</a>
        <a href="https://github.com/1Dr4gon" target="_blank">🐙</a>
        <a href="https://www.instagram.com/majd_s_askar" target="_blank">📷</a>
      </div>
    </div>
  </footer>
</div>

<div class="content-section" id="content">

## About

Highly motivated and energetic individual with excellent communication and interpersonal skills, eager to apply a strong passion for customer service in a call center role. Skilled in problem-solving, active listening, and multitasking efficiently. Maintains a positive and adaptable attitude in fast-paced environments, always prioritizing customer satisfaction. Quick to grasp new systems and processes, with a strong enthusiasm for teamwork. Committed to handling customer inquiries effectively and ensuring a seamless service experience.

## Education

**Bachelor's in Software Engineering ,Salahaddin University, Erbil**  
Oct 2022 - Present


## Experience

**CustomerCare Agent**  
AsiaCell | Summer 2024 - present

**Freelance Developer**  
2023 - Present  
Created custom websites for local businesses

## Certificates
**Artificial Intelligence Workshop Certification**(Jul 2024)

**NEBA Entrepreneurship Training**(Oct 2024)


## Skills

**Languages:** JavaScript, Python, HTML, CSS  
**Frameworks:** Vue.js, React, Node.js  
**Tools:** Git, VS Code, Figma


## Contact

**Email:** Majdsamer14@gmail.com  
**Phone:** +964 7721607147 
**Location:** Erbil, Iraq

[Download Resume PDF](/cv.pdf)

</div>

<style>
/* Reset and base styles */
.theme-default-content {
  max-width: none !important;
  padding: 0 !important;
  margin: 0 !important;
}

body, html {
  margin: 0 !important;
  padding: 0 !important;
}

.page {
  padding: 0 !important;
}

/* Hero Section */
.hero-section {
  background: #2c3e50;
  color: white;
  min-height: 100vh;
  position: relative;
  display: flex;
  flex-direction: column;
}

/* Top Navigation */
.top-nav {
  position: fixed;
  top: 0;
  right: 0;
  padding: 2rem;
   width: 100%;
   justify-content: flex-end;
     align-items: center; 
  display: flex;
  gap: 2rem;
  z-index: 100;
  background: #2c3e50;
 
}

.top-nav a {
  color: white;
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 300;
  transition: opacity 0.3s ease;
}

.top-nav a:hover {
  opacity: 0.7;
}

.contact-btn {
  border: 1px solid rgba(255,255,255,0.3) !important;
  padding: 0.5rem 1rem !important;
}

/* Hero Content */
.hero-content {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 2rem;
}

.hero-title {
  font-size: 4rem;
  font-weight: 300;
  letter-spacing: 0.1em;
  margin: 0 0 1rem 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.hero-subtitle {
  font-size: 1.2rem;
  margin: 0;
  opacity: 0.8;
  font-weight: 300;
}

/* Scroll Indicator */
.scroll-indicator {
  position: absolute;
  bottom: 6rem;
  left: 50%;
  transform: translateX(-50%);
  text-align: center;
}

.scroll-arrow {
  color: white;
  text-decoration: none;
  font-size: 2rem;
  opacity: 0.7;
}

.scroll-arrow:hover {
  opacity: 1;
}

/* Hero Footer */
.hero-footer {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  padding: 2rem;
}

.footer-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.copyright {
  font-size: 0.8rem;
  opacity: 0.6;
  margin: 0;
}

.social-icons {
  display: flex;
  gap: 1rem;
}

.social-icons a {
  color: white;
  text-decoration: none;
  font-size: 1.2rem;
  opacity: 0.6;
  transition: opacity 0.3s ease;
}

.social-icons a:hover {
  opacity: 1;
}

/* Content Section */
.content-section {
  max-width: 800px;
  margin: 0 auto;
  padding: 4rem 2rem;
  line-height: 1.7;
  background: white;
  min-height: 100vh;
}

.content-section h2 {
  color: #2c3e50;
  font-size: 1.8rem;
  margin: 3rem 0 1rem 0;
  font-weight: 300;
  letter-spacing: 0.05em;
}

.content-section p {
  margin-bottom: 1.5rem;
  color: #555;
}

.content-section strong {
  color: #2c3e50;
  font-weight: 600;
}

.content-section a {
  color: #3eaf7c;
  text-decoration: none;
}

.content-section a:hover {
  text-decoration: underline;
}

/* Mobile Responsive */
@media (max-width: 768px) {
  .hero-title {
    font-size: 2.5rem;
  }
  
  .hero-subtitle {
    font-size: 1rem;
  }
  
  .top-nav {
    flex-direction: column;
    gap: 1rem;
  }
  
  .footer-content {
    flex-direction: column;
    gap: 1rem;
    text-align: center;
  }
  
  .content-section {
    padding: 2rem 1rem;
  }
}

/* Remove default VuePress styling */
.page {
  padding: 0 !important;
}

.page-edit, .page-nav {
  display: none !important;
}

/* Additional fixes for white space */
.theme-container {
  background: transparent !important;
}

.navbar {
  display: none !important;
}

.sidebar {
  display: none !important;
}
</style>