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
    <a href="projects" class="nav-link">[ PROJECTS ]</a>
    <a href="experience" class="nav-link active">[ EXPERIENCE ]</a>
    <a href="videos" class="nav-link">[ VIDEOS ]</a>
    <a href="JEFFERY_BAKER_Resume_Orange.pdf" target="_blank" class="nav-link">[ RESUME ]</a>
  </div>
  
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
