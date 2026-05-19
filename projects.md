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
    flex-wrap: nowrap;
    justify-content: center;
    gap: 12px;
    margin-bottom: 35px;
    width: 100%;
  }

  .nav-link {
    font-weight: bold;
    color: #00d2ff !important;
    text-decoration: none !important;
    white-space: nowrap;
    padding: 8px 12px; 
    font-family: monospace;
    font-size: 17px;
    transition: all 0.3s ease;
  }

  .nav-link:hover {
    background: rgba(0, 210, 255, 0.1);
    border: 1px solid #00d2ff;
    box-shadow: 0 0 10px rgba(0, 210, 255, 0.4);
    border-radius: 4px;
  }

  /* 4. TEXT VISIBILITY & ANIMATION */
  p, li, label, span, em, strong { color: #ffffff !important; }
  h1, h2, h3, a { color: #00d2ff !important; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }
  
  ul { margin-bottom: 20px; padding-left: 20px; }
  li { margin-bottom: 8px; line-height: 1.5; }
  p { line-height: 1.6; margin-bottom: 20px; }
  hr { border: 0; border-top: 1px solid rgba(0, 210, 255, 0.3); margin: 30px 0; }

  .terminal-title {
    display: inline-block;
    animation: pulseGlow 2s infinite alternate;
  }

  @keyframes pulseGlow {
    0% { text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }
    100% { text-shadow: 0 0 15px rgba(0, 210, 255, 0.9), 0 0 20px rgba(0, 210, 255, 0.4); }
  }

  /* 5. LAYOUT CLEANUP */
  header, .sidebar, #header, aside, footer, .site-footer { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

  /* MOBILE RESPONSIVENESS */
  @media (max-width: 600px) {
    .wrapper { padding: 20px !important; }
    .nav-container { 
      flex-wrap: wrap;
      gap: 8px; 
    }
    .nav-link { 
      font-size: 13px !important; 
      padding: 5px !important; 
    }
    /* Allow images to stack on mobile devices natively */
    .image-row {
      flex-direction: column !important;
      gap: 15px !important;
    }
    .image-row img {
      width: 100% !important;
      max-width: 100% !important;
    }
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

  <h1><span class="terminal-title">🚀 Engineering & Automation Projects</span></h1>

  <h2>🛰️ Raspberry Pi Ultrasonic Sensor Project</h2>
  <ul>
    <li><strong>Goal:</strong> Develop a real-time distance monitoring system using a Raspberry Pi Zero 2 W.</li>
    <li><strong>Technical Specs:</strong>
      <ul>
        <li><strong>Hardware:</strong> HC-SR04 Ultrasonic Sensor, 1 kΩ and 2 kΩ resistors (Voltage Divider).</li>
        <li><strong>Logic:</strong> Python-based script using <code>RPi.GPIO</code> library.</li>
      </ul>
    </li>
  </ul>

  <div class="image-row" style="display: flex; justify-content: center; gap: 2%; width: 100%; margin: 20px 0;">
    <img src="UltrasonicSensor1.jpg" style="width: 48% !important; max-width: 48% !important; border: 1px solid #00d2ff; border-radius: 4px;">
    <img src="UltrasonicSensor2.jpg" style="width: 48% !important; max-width: 48% !important; border: 1px solid #00d2ff; border-radius: 4px;">
  </div>

  <hr>

  <h2>🔊 Custom ESP32 Bluetooth Speaker</h2>
  <ul>
    <li><strong>Development:</strong> Designed a custom enclosure in SolidWorks and integrated soldered circuitry for high-fidelity audio output.</li>
  </ul>

  <div class="image-row" style="display: flex; justify-content: center; gap: 2%; width: 100%; margin: 20px 0;">
    <img src="InsideESP32Speaker.jpg" style="width: 48% !important; max-width: 48% !important; border: 1px solid #00d2ff; border-radius: 4px;">
    <img src="ESP32Speaker_On3DPrinter.jpg" style="width: 48% !important; max-width: 48% !important; border: 1px solid #00d2ff; border-radius: 4px;">
  </div>

  <hr>

  <p align="center">
    <a href="./" style="font-weight:bold; text-decoration: none;">&lt;&lt; Back to Main Portfolio</a>
  </p>

</div>
