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

  /* 3. TEXT VISIBILITY */
  p, li, label, span, em, strong { color: #ffffff !important; }
  h1, h2, h3, a { color: #00d2ff !important; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }

  /* 4. LAYOUT CLEANUP (Hides the 'deliriousguy' sidebar) */
  header, .sidebar, #header, aside, footer, .site-footer { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

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
    .terminal-title { font-size: 16px !important; white-space: normal !important; border-right: none !important; animation: none !important; display: block !important; }
    img, video { width: 100% !important; margin-bottom: 15px !important; }
  }
</style>

<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=6">

<p align="center">
  <a href="index.html" style="font-weight:bold; color:#00d2ff; text-decoration:none;">[ HOME ]</a> &nbsp;&nbsp; 
  <a href="projects.html" style="font-weight:bold; color:#00d2ff; text-decoration:none;">[ PROJECTS ]</a> &nbsp;&nbsp; 
  <a href="experience.html" style="font-weight:bold; color:#00d2ff; text-decoration:none;">[ EXPERIENCE ]</a> &nbsp;&nbsp; 
  <a href="labs.html" style="font-weight:bold; color:#00d2ff; text-decoration:none;">[ COLLEGE LABS ]</a> &nbsp;&nbsp;
  <a href="JEFFERYBAKER_Resume.pdf" target="_blank" style="font-weight:bold; color:#00d2ff; text-decoration:none;">[ RESUME ]</a>
</p>

<div class="wrapper">

# <span class="terminal-title">Robotics & Programming Projects</span>

## 🚀 Raspberry Pi Ultrasonic Sensor Project
* **The Goal:** Develop a real-time distance monitoring system using a Raspberry Pi Zero 2 W.
* **Technical Specs:**
    * **Hardware:** HC-SR04 Ultrasonic Sensor, 1kΩ and 2kΩ resistors (Voltage Divider).
    * **Logic:** Python-based script using `RPi.GPIO` library.
<p align="center">
  <img src="UltrasonicSensor1.jpg" width="45%" alt="Sensor Build" style="border: 1px solid #00d2ff; border-radius: 4px;">
  <img src="UltrasonicSensor2.jpg" width="45%" alt="Sensor in Action" style="border: 1px solid #00d2ff; border-radius: 4px;">
</p>
<p align="center">
  <video src="UltrasonicSensor.mp4" width="70%" style="border: 1px solid #00d2ff; border-radius: 4px;" controls></video>
</p>

---

## 🚀 Raspberry Pi Active Buzzer System
* **Goal:** Create a programmable audible alert system.
* **Specs:** Raspberry Pi Zero 2 W, GPIO Pins, 5V Active Buzzer, PWM frequency control.

<p align="center">
  <img src="buzzer_build.jpg" width="48%" style="border: 1px solid #00d2ff; border-radius: 4px; vertical-align: middle;">
  <video src="buzzer_build.mp4" width="48%" style="max-height: 240px; border: 1px solid #00d2ff; border-radius: 4px; vertical-align: middle;" controls></video>
</p>

---

<p align="center">
  <a href="index.html" style="font-weight:bold;"> << Back to Main Portfolio</a>
</p>

</div>
