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

  /* 3. NAVIGATION - CALIBRATED FOR ONE LINE */
  .nav-container {
    display: flex;
    flex-wrap: nowrap; /* Forces one line on desktop */
    justify-content: center;
    gap: 12px; /* Balanced spacing to stay inside the border */
    margin-bottom: 35px;
    width: 100%;
  }

  .nav-link {
    font-weight: bold;
    color: #00d2ff !important;
    text-decoration: none !important;
    white-space: nowrap; /* Keeps [ COLLEGE LABS ] together */
    padding: 8px 12px;
    font-family: monospace;
    font-size: 17px; /* Calibrated size to fit all 5 tabs */
    transition: all 0.3s ease;
  }

  .nav-link:hover {
    background: rgba(0, 210, 255, 0.1);
    box-shadow: 0 0 10px rgba(0, 210, 255, 0.4);
    border-radius: 4px;
  }

  /* 4. TEXT VISIBILITY & THEME CLEANUP */
  p, li, label, span, em, strong { color: #ffffff !important; }
  h1, h2, h3, a { color: #00d2ff !important; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }
  header, .sidebar, #header, aside, footer, .site-footer { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

  /* TERMINAL ANIMATION */
  .terminal-title {
    display: inline-block;
    overflow: hidden; 
    border-right: .15em solid #00d2ff; 
    white-space: nowrap; 
    letter-spacing: .10em; 
    animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
  }
  @keyframes typing { from { width: 0 } to { width: 100% } }
  @keyframes blink-caret { from, to { border-color: transparent } 50% { border-color: #00d2ff; } }

  /* MOBILE RESPONSIVENESS */
  @media (max-width: 600px) {
    .wrapper { padding: 20px !important; margin: 10px auto !important; }
    .nav-container { flex-wrap: wrap; gap: 8px; }
    .nav-link { font-size: 13px !important; padding: 5px !important; }
    .terminal-title { font-size: 16px !important; white-space: normal !important; border-right: none !important; animation: none !important; display: block !important; }
    img, video { width: 100% !important; }
  }
</style>

<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=6">

<div class="nav-container">
  <a href="./" class="nav-link">[ HOME ]</a> 
  <a href="projects" class="nav-link">[ PROJECTS ]</a> 
  <a href="experience" class="nav-link">[ EXPERIENCE ]</a> 
  <a href="labs" class="nav-link">[ COLLEGE LABS ]</a> 
  <a href="/JEFFERY_BAKER_Resume_Orange.pdf" target="_blank" class="nav-link">[ RESUME ]</a>
</div>

# <span class="terminal-title">Jeffery Baker | Robotics & Automated Manufacturing</span>

### ⚡ The Bridge Between Precision & Automation
I am a specialized technician transitioning from **aerospace-grade welding** into **Robotics/Automated Manufacturing Systems**. My unique value is the ability to combine heavy industrial fabrication with modern digital logic and PLC programming.

---

## 🛠️ Core Competencies
* **Automation:** PLC Programming (Fanuc, Festo), UR Integration, Industry 4.0.
* **Electronics:** Circuit Analysis, Raspberry Pi (Python3), Micro-Sensor logic.
* **Fabrication:** Aluminum MIG Welding, Automated Machining.
* **Systems:** Electro-Hydraulics & Pneumatics, 3D Printing (Bambu Labs P2S), SolidWorks.

---

## 🚀 Recent Highlights
* **Current Project:** Creating a custom ESP32 Bluetooth speaker.
* **Latest Personal Project:** Real-time distance monitoring system using Raspberry Pi Zero 2 W.
* **Credentials:** Pursuing my AAS at Lone Star College (Expected Graduation: Dec 2026).

---

## 📬 Quick Connect
* **LinkedIn:** [Jeffery L Baker](https://www.linkedin.com/in/jeffery-baker-15b767218/)
* **Email:** Jlb107078@gmail.com
* **Location:** Spring, Texas

<form action="https://formspree.io/f/mpqjeoyw" method="POST" style="max-width: 500px;">
  <label>Send a Quick Message:</label><br>
  <input type="email" name="email" placeholder="Your Email" style="width: 100%; padding: 8px; margin-bottom: 10px;" required><br>
  <textarea name="message" placeholder="Your Message" style="width: 100%; height: 80px; padding: 8px;" required></textarea><br>
  <button type="submit" style="background-color: #00d2ff; color: #010b1a; padding: 10px 20px; border: none; cursor: pointer; font-weight: bold;">SEND MESSAGE</button>
</form>
