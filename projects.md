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

  /* 2. CONTENT BOX */
  .wrapper { 
    max-width: 900px !important; 
    margin: 40px auto !important; 
    padding: 40px !important;
    background: rgba(1, 11, 26, 0.85) !important; 
    border: 1px solid #00d2ff !important; 
    border-radius: 8px !important;
    box-shadow: 0 0 25px rgba(0, 210, 255, 0.3) !important;
  }

  /* 3. NAVIGATION - FORCED BORDERS & HOVER GLOW */
  .nav-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 12px;
    margin-bottom: 35px;
  }

  .nav-link {
    font-weight: bold;
    color: #00d2ff !important;
    text-decoration: none !important;
    white-space: nowrap;
    padding: 12px 20px;
    font-family: monospace;
    font-size: 15px;
    border: 1px solid transparent !important; /* Force transparent bounding box */
    border-radius: 4px !important;
    transition: all 0.3s ease;
  }

  .nav-link:hover {
    background: rgba(0, 210, 255, 0.1) !important;
    border-color: #00d2ff !important; /* Force cyan box line on hover */
    box-shadow: 0 0 10px rgba(0, 210, 255, 0.4) !important;
  }

  /* 4. TEXT VISIBILITY & ANIMATION */
  p, li, label, span, em, strong { color: #ffffff !important; }
  h1, h2, h3, a { color: #00d2ff !important; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }

  /* 5.1 PERMANENT ACTIVE TAB GLOW */
  .nav-link.active {
    background: rgba(0, 210, 255, 0.15) !important;
    border-color: #00d2ff !important;
    box-shadow: 0 0 15px rgba(0, 210, 255, 0.4) !important;
    border-radius: 4px !important;
  }
  
  /* Give the lists some clean spacing */
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

  /* 5. MATCHING DARK INPUT FIELDS */
  input, textarea {
    background: rgba(1, 11, 26, 0.6) !important;
    border: 1px solid #00d2ff !important;
    color: #ffffff !important;
    border-radius: 4px;
    font-family: monospace;
  }
  input::placeholder, textarea::placeholder {
    color: rgba(255, 255, 255, 0.4) !important;
  }

  /* 6. HIDE THEME ELEMENTS */
  header, .sidebar, #header, aside, footer, .site-footer { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

  /* MOBILE RESPONSIVENESS */
  @media (max-width: 600px) {
    .wrapper { padding: 20px !important; margin: 10px auto !important; }
    .nav-link { font-size: 15px !important; padding: 8px 10px !important; }
    .nav-container { gap: 8px; }
    img, video { width: 100% !important; }
  }
</style>

<link rel="icon" type="image/png" href="/favicon.png?v=7">

<div class="wrapper">

  <div class="nav-container">
    <a href="./" class="nav-link">[ HOME ]</a>
    <a href="projects" class="nav-link active">[ PROJECTS ]</a>
    <a href="experience" class="nav-link">[ EXPERIENCE ]</a>
    <a href="videos" class="nav-link">[ VIDEOS ]</a>
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
    <img src="UltrasonicSensor1.jpg" style="width: 48% !important; max-width: 48% !important; aspect-ratio: 4/3; object-fit: cover; border: 1px solid #00d2ff; border-radius: 4px;" alt="Ultrasonic Sensor Assembly">
    <img src="UltrasonicSensor2.jpg" style="width: 48% !important; max-width: 48% !important; aspect-ratio: 4/3; object-fit: cover; border: 1px solid #00d2ff; border-radius: 4px;" alt="Hardware Setup Analysis">
  </div>

  <hr>

  <h2>🔊 Custom ESP32 Bluetooth Speaker</h2>
  <ul>
    <li><strong>Development:</strong> Designed a custom enclosure in SolidWorks and integrated soldered circuitry for high-fidelity audio output.</li>
  </ul>

  <div style="margin: 20px 0 30px 20px; font-family: monospace;">
    <h4 style="color: #00d2ff; margin-bottom: 10px;">📋 Bill of Materials & Technical Layout:</h4>
    
    <p style="margin-bottom: 5px; font-weight: bold; color: #00d2ff;">🔹 Core Electronics & Audio</p>
    <ul>
      <li>Microcontroller: Elegoo ESP32 (CP2102).</li>
      <li>Digital-to-Analog Converter (DAC): PCM5102 I2S IIS DAC.</li>
      <li>Amplifier: PAM8610 2x15W Class D Power Amplifier Board with Control Knob.</li>
      <li>Speakers: Dual 4-Ohm 20W Full-Range Speakers.</li>
    </ul>

    <p style="margin-top: 15px; margin-bottom: 5px; font-weight: bold; color: #00d2ff;">🔹 Power & Control System</p>
    <ul>
      <li>Main Power Source: 12.6V 3A max 2600mAh Li-ion Battery (Rapthor brand).</li>
      <li>Voltage Step-Down: LM2596 Buck Converter (drops battery voltage to 5V to safely power the ESP32 and DAC).</li>
      <li>Power Switch: 12V 20A Round Blue LED Toggle Switch.</li>
      <li>System Monitor: Battery Monitor / Capacity Indicator.</li>
    </ul>

    <p style="margin-top: 15px; margin-bottom: 5px; font-weight: bold; color: #00d2ff;">🔹 Wiring, Hardware & Enclosure</p>
    <ul>
      <li>Electrical Wire: 16 Gauge Solid Core Wire.</li>
      <li>Audio Patching: 3.5mm Aux Cable.</li>
      <li>Outer Shell: Custom 3D-Printed Enclosure (designed in SolidWorks over 2 days and printed on my Bambu Lab P2S over 3 days).</li>
    </ul>
  </div>

  <div class="image-row" style="display: flex; justify-content: center; gap: 2%; width: 100%; margin: 20px 0;">
    <img src="ESP32Speaker_On3DPrinter.jpg" style="width: 48% !important; max-width: 48% !important; aspect-ratio: 4/3; object-fit: cover; border: 1px solid #00d2ff; border-radius: 4px;" alt="Enclosure Printing Process">
    <img src="InsideESP32Speaker.jpg" style="width: 48% !important; max-width: 48% !important; aspect-ratio: 4/3; object-fit: cover; border: 1px solid #00d2ff; border-radius: 4px;" alt="Internal Circuitry Integration">
  </div>

  <hr>

  <p align="center">
    <a href="./" style="font-weight:bold; text-decoration: none;">&lt;&lt; Back to Main Portfolio</a>
  </p>

</div>
