<style>
  /* 1. TECH BACKGROUND SETUP */
  html, body { 
    background-image: url('tech-bg.jpg') !important;
    background-size: cover !important;
    background-position: center !important;
    background-attachment: fixed !important;
    background-color: #010b1a !important; 
    color: #ffffff !important;
  }

  /* 2. SEMI-TRANSPARENT CONTENT BOX */
  .wrapper { 
    max-width: 900px !important; 
    margin: 40px auto !important; 
    padding: 40px !important;
    float: none !important;
    display: block !important;
    background: rgba(1, 11, 26, 0.85) !important; 
    border: 1px solid #00d2ff !important; 
    border-radius: 8px !important;
    box-shadow: 0 0 25px rgba(0, 210, 255, 0.3) !important;
  }

  /* 3. FIXING TEXT VISIBILITY */
  p, li, label, span, em, strong { 
    color: #ffffff !important; 
  }
  
  h1, h2, h3, a { 
    color: #00d2ff !important; 
    text-shadow: 0 0 5px rgba(0, 210, 255, 0.5);
  }

  /* 4. LAYOUT CLEANUP */
  header, .sidebar, #header, aside, footer, .site-footer { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

/* NEW FLEXBOX NAVIGATION - Stops the bracket break */
  .nav-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
    margin-bottom: 30px;
  }
  
  .nav-container a {
    white-space: nowrap; /* Forces [ COLLEGE LABS ] to stay together */
    font-weight: bold;
    color: #00d2ff !important;
    text-decoration: none;
    font-family: monospace;
  }

  @media (max-width: 600px) {
    .nav-container a {
      font-size: 13px; /* Smaller text ensures 3-4 tabs fit per row */
    }
  }

  /* TERMINAL TYPING ANIMATION */
  .terminal-title {
    display: inline-block;
    overflow: hidden; 
    border-right: .15em solid #00d2ff; 
    white-space: nowrap; 
    margin: 0 auto; 
    letter-spacing: .10em; 
    animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
  }
  @keyframes typing { from { width: 0 } to { width: 100% } }
  @keyframes blink-caret { from, to { border-color: transparent } 50% { border-color: #00d2ff; } }

  /* MOBILE RESPONSIVENESS FIXES */
  @media (max-width: 600px) {
    .wrapper { padding: 20px !important; margin: 10px auto !important; }
    .nav-container a { font-size: 14px; padding: 5px; }
    .terminal-title { font-size: 16px !important; white-space: normal !important; border-right: none !important; animation: none !important; display: block !important; }
    img, video { width: 100% !important; margin-bottom: 15px !important; }
  }
</style>

<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=6">

<div class="nav-container">
  <a href="./">[ HOME ]</a>
  <a href="projects">[ PROJECTS ]</a>
  <a href="experience">[ EXPERIENCE ]</a>
  <a href="labs">[ COLLEGE LABS ]</a>
  <a href="/JEFFERYBAKER_Resume.pdf" target="_blank" class="nav-link">[ RESUME ]</a>
</div>

# <span class="terminal-title">Lone Star College | Robotics Lab Media</span>

### Current Coursework: Robotics & Automated Manufacturing
This section contains documented technical results from my circuit analysis and robotics labs at the North Harris campus.

<p>Find more videos on my YouTube channel 
  <a href="https://www.youtube.com/@JlbRobotics" target="_blank">@Jeffery's Knowledge</a>
</p>

---

## ⚡ AC/DC Circuits Lab
* **Project:** Combined Series-Parallel Circuits
* **Focus:** Measuring voltage drops and verifying Ohm's Law in complex resistor networks.

<p align="center">
  <img src="ACDC_Lab_1.jpg" width="48%" style="border: 1px solid #00d2ff; border-radius: 4px; margin: 1%;">
  <img src="ACDC_Lab_2.jpg" width="48%" style="border: 1px solid #00d2ff; border-radius: 4px; margin: 1%;">
</p>

---

## 🤖 PLC & Automation Lab (Coming Soon)
* **Focus:** Programming logic for automated manufacturing systems and Universal Robots (UR) integration.
* **Current Task:** Troubleshooting ladder logic for synchronized industrial arm movements.

<p align="center">
  <video src="RoboticsLab.mp4" width="80%" controls>
    Your browser does not support the video tag.
  </video>
</p>
---

<p align="center">
  <a href="./" style="font-weight:bold;"> << Back to Main Portfolio</a>
</p>>
