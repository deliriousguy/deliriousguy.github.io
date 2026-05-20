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

  /* 3. NAVIGATION - FORCED BORDERS & HOVER GLOW */
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
    border: 1px solid transparent !important; /* Force transparent bounding box */
    border-radius: 4px !important;
    transition: all 0.3s ease;
  }

  .nav-link:hover {
    background: rgba(0, 210, 255, 0.1) !important;
    border: 1px solid #00d2ff !important; /* Force cyan box line on hover */
    box-shadow: 0 0 10px rgba(0, 210, 255, 0.4) !important;
  }

  /* 4. TEXT VISIBILITY */
  p, li, label, span, em, strong { color: #ffffff !important; }
  h1, h2, h3, a { color: #00d2ff !important; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }

  ul { margin-bottom: 20px; padding-left: 20px; }
  li { margin-bottom: 8px; line-height: 1.5; }
  p { line-height: 1.6; margin-bottom: 20px; }
  hr { border: 0; border-top: 1px solid rgba(0, 210, 255, 0.3); margin: 30px 0; }

  /* 5.1 PERMANENT ACTIVE TAB GLOW */
  .nav-link.active {
    background: rgba(0, 210, 255, 0.15) !important;
    border: 1px solid #00d2ff !important; /* Force permanent border */
    box-shadow: 0 0 15px rgba(0, 210, 255, 0.4) !important;
    border-radius: 4px !important;
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

  /* 5. LAYOUT CLEANUP - AGGRESSIVELY HIDING THEME THEME INJECTIONS */
  header, .sidebar, #header, aside, footer, .site-footer, .project-name, .project-tagline, .site-title { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

  /* MOBILE RESPONSIVENESS */
  @media (max-width: 600px) {
    .wrapper { padding: 20px !important; }
    .nav-container { flex-wrap: wrap; gap: 8px; }
    .nav-link { font-size: 13px !important; padding: 5px !important; }
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
  }
</style>

<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=6">

  <div class="nav-container">
    <a href="./" class="nav-link">[ HOME ]</a>
    <a href="projects" class="nav-link">[ PROJECTS ]</a>
    <a href="experience" class="nav-link active">[ EXPERIENCE ]</a>
    <a href="videos" class="nav-link">[ VIDEOS ]</a>
    <a href="JEFFERY_BAKER_Resume_Orange.pdf" target="_blank" class="nav-link">[ RESUME ]</a>
  </div>
  
<div class="wrapper">
  
  <h1><span class="terminal-title">Professional Experience</span></h1>

  <h3>Aerospace-Grade Fabrication</h3>
  <ul>
    <li>Role: Welder at Communications and Power Industries (CPI).</li>
    <li>Expertise: High-precision Aluminum MIG Welding within the communications industry.</li>
    <li>Focus: Maintaining structural integrity and metallurgy standards for aerospace-grade equipment.</li>
  </ul>

  <div class="image-row" style="display: flex; justify-content: center; gap: 2%; width: 100%; margin: 20px 0;">
    <img src="AluWeld.jpg" style="width: 48% !important; max-width: 48% !important; aspect-ratio: 4/3; object-fit: cover; border-radius: 4px; border: 1px solid #00d2ff;" alt="Aluminum Weld Detail">
    <img src="20241213_092023.jpg" style="width: 48% !important; max-width: 48% !important; aspect-ratio: 4/3; object-fit: cover; border-radius: 4px; border: 1px solid #00d2ff;" alt="Welding Fabrication">
  </div>

  <hr>

  <h3>Industrial Maintenance & Infrastructure</h3>
  <ul>
    <li>General Technician I (TxDOT): Technical maintenance and operational support for state-level infrastructure.</li>
  </ul>

  <div style="text-align: center; margin-top: 40px; font-family: monospace;">
    <p style="margin-bottom: 10px;">Scan to view my portfolio on mobile</p>
    <img src="jlb_portfolio_qr.png" width="180" style="border: 2px solid #00d2ff; border-radius: 8px;" alt="Portfolio QR Code">
  </div>

  <hr>

  <p align="center">
    <a href="JEFFERY_BAKER_Resume_Orange.pdf" target="_blank" style="font-weight:bold; text-decoration: none;">[ DOWNLOAD FULL RESUME PDF ]</a>
  </p>

</div>
