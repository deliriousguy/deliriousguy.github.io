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
    background: rgba(1, 11, 26, 0.85) !important; 
    border: 1px solid #00d2ff !important; 
    border-radius: 8px !important;
    box-shadow: 0 0 25px rgba(0, 210, 255, 0.3) !important;
  }

  /* 3. NAVIGATION - CALIBRATED SIZE & NO-WRAP */
  .nav-container {
    display: flex;
    flex-wrap: nowrap; /* Forces a single line on desktop */
    justify-content: center;
    gap: 12px;
    margin-bottom: 35px;
    width: 100%;
  }

  .nav-link {
    font-weight: bold;
    color: #00d2ff !important;
    text-decoration: none !important;
    white-space: nowrap; /* Prevents brackets from breaking */
    padding: 8px 12px; 
    font-family: monospace;
    font-size: 17px; /* Calibrated to fit 5 tabs in 900px */
    transition: all 0.3s ease;
  }

  .nav-link:hover {
    background: rgba(0, 210, 255, 0.1);
    border: 1px solid #00d2ff;
    box-shadow: 0 0 10px rgba(0, 210, 255, 0.4);
    border-radius: 4px;
  }

  /* 4. TEXT VISIBILITY */
  p, li, label, span, em, strong { color: #ffffff !important; }
  h1, h2, h3, a { color: #00d2ff !important; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }

  /* 5. LAYOUT CLEANUP */
  header, .sidebar, #header, aside, footer, .site-footer { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

  /* MOBILE RESPONSIVENESS */
  @media (max-width: 600px) {
    .wrapper { padding: 20px !important; }
    .nav-container { 
      flex-wrap: wrap; /* Allows tabs to stack on small phone screens */
      gap: 8px; 
    }
    .nav-link { 
      font-size: 13px !important; 
      padding: 5px !important; 
    }
    img, video { width: 100% !important; }
  }
</style>

<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=6">

<div class="nav-container">
  <a href="./" class="nav-link">[ HOME ]</a>
  <a href="projects" class="nav-link">[ PROJECTS ]</a>
  <a href="experience" class="nav-link">[ EXPERIENCE ]</a>
  <a href="labs" class="nav-link">[ COLLEGE LABS ]</a>
  <a href="/JEFFERYBAKER_Resume.pdf" target="_blank" class="nav-link">[ RESUME ]</a>
</div>

# 🚀 Engineering & Automation Projects

## 🛰️ Raspberry Pi Ultrasonic Sensor Project
* **Goal:** Develop a real-time distance monitoring system using a Raspberry Pi Zero 2 W.
* **Technical Specs:**
    * **Hardware:** HC-SR04 Ultrasonic Sensor, $1k\Omega$ and $2k\Omega$ resistors (Voltage Divider).
    * **Logic:** Python-based script using `RPi.GPIO` library.

<p align="center">
  <img src="UltrasonicSensor1.jpg" width="48%" style="border: 1px solid #00d2ff; border-radius: 4px; margin: 1%;">
  <img src="UltrasonicSensor2.jpg" width="48%" style="border: 1px solid #00d2ff; border-radius: 4px; margin: 1%;">
</p>

---

## 🔊 Custom ESP32 Bluetooth Speaker
* **Development:** Designed a custom enclosure in SolidWorks and integrated soldered circuitry for high-fidelity audio output.

<p align="center">
  <img src="buzzer_build.jpg" width="80%" style="border: 1px solid #00d2ff; border-radius: 4px; margin-bottom: 20px;">
</p>

---

<p align="center">
  <a href="./" style="font-weight:bold;"> << Back to Main Portfolio</a>
</p>
