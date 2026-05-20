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
  p, li, label, span, em, strong { color: #ffffff !important; }
  h1, h2, h3, a { color: #00d2ff !important; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }

  ul { margin-bottom: 20px; padding-left: 20px; }
  li { margin-bottom: 8px; line-height: 1.5; }
  p { line-height: 1.6; margin-bottom: 20px; }
  hr { border: 0; border-top: 1px solid rgba(0, 210, 255, 0.3); margin: 30px 0; }

  /* 4. LAYOUT CLEANUP - AGGRESSIVELY HIDING THEME THEME INJECTIONS */
  header, .sidebar, #header, aside, footer, .site-footer, .project-name, .project-tagline, .site-title { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

  /* 5. BIGGER NAVIGATION SETUP */
  .nav-container {
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    gap: 20px; 
    margin-bottom: 40px;
  }
  
  .nav-link {
    white-space: nowrap; 
    font-weight: bold;
    color: #00d2ff !important;
    text-decoration: none !important;
    font-family: monospace;
    font-size: 15px; 
    padding: 12px 20px; 
    border: 1px solid transparent;
    border-radius: 4px;
    transition: all 0.3s ease;
  }

  /* Glow effect on hover */
  .nav-link:hover {
    background: rgba(0, 210, 255, 0.1);
    border-color: #00d2ff;
    box-shadow: 0 0 15px rgba(0, 210, 255, 0.4);
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
    .nav-link { font-size: 15px !important; padding: 8px 10px !important; }
    .nav-container { gap: 8px; flex-wrap: wrap; }
    .terminal-title { font-size: 16px !important; white-space: normal !important; border-right: none !important; animation: none !important; display: block !important; }
    
    .image-row {
      flex-direction: column !important;
      gap: 15px !important;
    }
    .image-row img {
      width: 100% !important;
      max-width: 100% !important;
      aspect-ratio: auto !important;
    }
    video { width: 100% !important; }
  }
</style>

<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=6">

<div class="wrapper">

  <div class="nav-container">
    <a href="./" class="nav-link">[ HOME ]</a>
    <a href="projects" class="nav-link">[ PROJECTS ]</a>
    <a href="experience" class="nav-link">[ EXPERIENCE ]</a>
    <a href="labs" class="nav-link">[ COLLEGE LABS ]</a>
    <a href="JEFFERY_BAKER_Resume_Orange.pdf" target="_blank" class="nav-link">[ RESUME ]</a>
  </div>

  <h1><span class="terminal-title">

<h3>Current Coursework: Robotics & Automated Manufacturing</h3>
  <p>This section contains documented technical results from my circuit analysis and robotics labs at the North Harris campus.</p>
  
  <p style="font-family: monospace;">Find more videos on my YouTube channel: 
    <a href="https://www.youtube.com/@JlbRobotics" target="_blank" style="text-decoration: none;">@Jeffery's Knowledge</a>
  </p>

  <hr>

  <h2>⚡ AC/DC Circuits Lab</h2>
  <ul>
    <li>Project: Combined Series-Parallel Circuits</li>
    <li>Focus: Measuring voltage drops and verifying Ohm's Law in complex resistor networks.</li>
  </ul>

  <div class="image-row" style="display: flex; justify-content: center; gap: 2%; width: 100%; margin: 20px 0;">
    <img src="ACDC_Lab_1.jpg" style="width: 48% !important; max-width: 48% !important; aspect-ratio: 4/3; object-fit: cover; border: 1px solid #00d2ff; border-radius: 4px;" alt="AC/DC Lab Bench Setup">
    <img src="ACDC_Lab_2.jpg" style="width: 48% !important; max-width: 48% !important; aspect-ratio: 4/3; object-fit: cover; border: 1px solid #00d2ff; border-radius: 4px;" alt="Circuit Analysis Testing">
  </div>

  <hr>

  <h2>🤖 PLC & Automation Lab</h2>
  <ul>
    <li>Focus: Programming logic for automated manufacturing systems and Universal Robots (UR) integration.</li>
    <li>Current Task: Troubleshooting ladder logic for synchronized industrial arm movements.</li>
  </ul>

  <p align="center" style="margin-top: 25px;">
    <video src="RoboticsLab.mp4" width="80%" style="border: 1px solid #00d2ff; border-radius: 4px; box-shadow: 0 0 15px rgba(0, 210, 255, 0.2);" controls>
      Your browser does not support the video tag.
    </video>
  </p>

  <hr>

  <p align="center">
    <a href="./" style="font-weight:bold; text-decoration: none;">&lt;&lt; Back to Main Portfolio</a>
  </p>

</div>
