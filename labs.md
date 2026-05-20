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
    margin-bottom: 30px;
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

  /* Glow effect on hover for Navigation Links */
  .nav-link:hover {
    background: rgba(0, 210, 255, 0.1);
    border-color: #00d2ff;
    box-shadow: 0 0 15px rgba(0, 210, 255, 0.4);
  }

  /* 6. INTERACTIVE YOUTUBE LINK BUTTON */
  .youtube-container {
    text-align: center;
    margin-bottom: 40px;
  }

  .youtube-link {
    display: inline-block;
    white-space: nowrap;
    font-weight: bold;
    color: #00d2ff !important;
    text-decoration: none !important;
    font-family: monospace;
    font-size: 15px;
    padding: 12px 24px;
    border: 1px solid transparent;
    border-radius: 4px;
    transition: all 0.3s ease;
  }

  /* Glow effect on hover for YouTube Link Button */
  .youtube-link:hover {
    background: rgba(0, 210, 255, 0.1);
    border-color: #00d2ff;
    box-shadow: 0 0 15px rgba(0, 210, 255, 0.4);
  }

  /* TERMINAL TYPING ANIMATION (used for main header) */
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
    .nav-link, .youtube-link { font-size: 14px !important; padding: 8px 10px !important; white-space: normal !important; }
    .nav-container { gap: 8px; flex-wrap: wrap; }
    .terminal-title { font-size: 16px !important; white-space: normal !important; border-right: none !important; animation: none !important; display: block !important; }
    
    .media-aligned-row {
      flex-direction: column !important;
      gap: 15px !important;
    }
    .media-aligned-row img, .media-aligned-row video, .media-aligned-row a {
      width: 100% !important;
      max-width: 100% !important;
      aspect-ratio: auto !important;
    }
    img, video { width: 100% !important; margin-bottom: 15px !important; }
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

  <div class="youtube-container">
    <a href="https://youtube.com/@jlbrobotics?si=rdboNTktWYJEn2gh" target="_blank" class="youtube-link">
      &gt; [ VISIT MY YOUTUBE CHANNEL: Jeffery's Knowledge ] &lt;
    </a>
  </div>

  <h1><span class="terminal-title">Featured Series: Robotic Fundamentals</span></h1>
  
  <h3>🎬 Episode 1: Introduction to Industrial Robotics & Cobots</h3>
  <p>Welcome to my technical video series, <strong>Robotic Fundamentals</strong>. This series focuses on deep-dive demonstrations where I explain how to configure, program, and execute operations on collaborative robots (cobots) like the Universal Robots UR3e, alongside heavy-duty industrial platforms like Fanuc systems.</p>

  <hr>

  <h3><span style="display: inline-block; animation: pulseGlow 2s infinite alternate; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5);">🛠️ Core Learning Objectives & Instrumentation</span></h3>
  
  <p>In this module, I detail curriculum roadmaps alongside real-world hardware integration paths, breaking down safety protocols, layout setups, and deployment structures:</p>

  <div class="media-aligned-row" style="display: flex; justify-content: center; align-items: stretch; gap: 1.5%; width: 100%; margin: 25px 0;">
    <div style="flex: 1; min-width: 0;">
      <img src="WhatYouWillLearnRFE1.png" style="width: 100%; height: auto; border: 1px solid #00d2ff; border-radius: 4px;" alt="Curriculum Scope: What You Will Learn">
    </div>
    <div style="flex: 1; min-width: 0;">
      <img src="TeachPendant.jpg" style="width: 100%; height: auto; border: 1px solid #00d2ff; border-radius: 4px;" alt="Industrial Robot Teach Pendant Unit">
    </div>
    <div style="flex: 1; min-width: 0;">
      <a href="https://youtu.be/gpvk6R97cx4?si=3UoBg4MYX4fRFkA6" target="_blank" style="display: inline-block; width: 100%; height: 100%;">
        <img src="ThumbnailYT1 .jpg" style="width: 100%; height: auto; border: 1px solid #00d2ff; border-radius: 4px; box-shadow: 0 0 10px rgba(0, 210, 255, 0.3);" alt="Watch Robotic Fundamentals Ep.1">
      </a>
    </div>
  </div>

</div>
