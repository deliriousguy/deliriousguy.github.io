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

  /* 3. NAVIGATION - UNIFORM SIZE & NO-WRAP */
  .nav-container {
    display: flex;
    flex-wrap: nowrap; /* Forces one line on desktop */
    justify-content: center;
    gap: 12px;
    margin-bottom: 35px;
    width: 100%;
  }

  .nav-link {
    font-weight: bold;
    color: #00d2ff !important;
    text-decoration: none !important;
    white-space: nowrap; /* Stops brackets from jumping lines */
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

  /* 4. TEXT VISIBILITY */
  p, li, label, span, em, strong { color: #ffffff !important; }
  h1, h2, h3, a { color: #00d2ff !important; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }

  /* 5. LAYOUT CLEANUP */
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

  /* MOBILE RESPONSIVENESS */
  @media (max-width: 600px) {
    .wrapper { padding: 20px !important; }
    .nav-container { flex-wrap: wrap; gap: 8px; }
    .nav-link { font-size: 13px !important; padding: 5px !important; }
    .terminal-title { font-size: 16px !important; white-space: normal !important; border-right: none !important; animation: none !important; display: block !important; }
    img, video { width: 100% !important; margin-bottom: 15px !important; }
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

# <span class="terminal-title">Professional Experience</span>

### Aerospace-Grade Fabrication
* **Role:** Welder at Communications and Power Industries (CPI).
* **Expertise:** High-precision Aluminum MIG Welding within the communications industry.
* **Focus:** Maintaining structural integrity and metallurgy standards for aerospace-grade equipment.

<p align="center">
  <img src="AluWeld.jpg" width="45%" alt="Aluminum Weld Detail" style="border-radius: 4px; border: 1px solid #00d2ff; margin: 1%;">
  <img src="20241213_092023.jpg" width="45%" alt="Welding Fabrication" style="border-radius: 4px; border: 1px solid #00d2ff; margin: 1%;">
</p>

---

### Industrial Maintenance & Infrastructure
* **General Technician I (TxDOT):** Technical maintenance and operational support for state-level infrastructure.
* **Floor Staff (Inspire Rock):** Previously managed facility operations and safety in a technical environment.

<div style="text-align: center; margin-top: 40px;">
  <p>Scan to view my portfolio on mobile</p>
  <img src="jlb_portfolio_qr.png" width="180" style="border: 2px solid #00d2ff; border-radius: 8px;">
</div>

---

<p align="center">
  <a href="/JEFFERYBAKER_Resume.pdf" target="_blank" style="font-weight:bold;">[ DOWNLOAD FULL RESUME PDF ]</a>
</p>
