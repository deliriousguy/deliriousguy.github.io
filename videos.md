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
    border: 1px solid transparent !important; 
    border-radius: 4px !important;
    transition: all 0.3s ease;
  }

  .nav-link:hover {
    background: rgba(0, 210, 255, 0.1) !important;
    border-color: #00d2ff !important; 
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
  
  ul { margin-bottom: 20px; padding-left: 20px; }
  li { margin-bottom: 8px; line-height: 1.5; }
  p { line-height: 1.6; margin-bottom: 20px; }
  hr { border: 0; border-top: 1px solid rgba(0, 210, 255, 0.3); margin: 30px 0; }

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

  .youtube-link:hover {
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
  @keyframes pulseGlow {
    0% { text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }
    100% { text-shadow: 0 0 15px rgba(0, 210, 255, 0.9), 0 0 20px rgba(0, 210, 255, 0.4); }
  }
  @keyframes typing { from { width: 0 } to { width: 100% } }
  @keyframes blink-caret { from, to { border-color: transparent } 50% { border-color: #00d2ff; } }

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
  header, .sidebar, #header, aside, footer, .site-footer, .project-name, .project-tagline, .site-title { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

  /* 7. ALIGNED MEDIA ROW BOX DESIGN & DARK BACKGROUND FIX */
  .media-aligned-row img {
    width: 100% !important;
    height: auto !important;
    aspect-ratio: 4/3 !important;
    object-fit: contain !important; 
    background-color: #010b1a !important; 
    border: 1px solid #00d2ff;
    border-radius: 4px;
    box-shadow: 0 0 10px rgba(0, 210, 255, 0.15) !important; 
  }
  .media-aligned-row a {
    display: block;
    width: 100%;
  }

  /* ANIMATED VIDEO CARD FEATURE PROPERTIES */
  .animated-video-card {
    display: block;
    position: relative;
    text-decoration: none !important;
    border: 1px solid #00d2ff !important;
    border-radius: 4px;
    animation: neonBorderPulse 2s infinite alternate ease-in-out;
  }

  /* Removes duplicate styling layout from image inside the link card wrapper */
  .animated-video-card img {
    border: none !important;
    box-shadow: none !important;
  }

  .border-label {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    background: #010b1a; /* Blends box background color over border line */
    color: #00d2ff !important;
    font-family: monospace;
    font-size: 11px;
    font-weight: bold;
    padding: 2px 8px;
    letter-spacing: 0.12em;
    z-index: 5;
    white-space: nowrap;
    border: 1px solid #00d2ff;
    border-radius: 3px;
    animation: labelGlowPulse 1.5s infinite alternate ease-in-out;
  }

  .label-top { top: -11px; }
  .label-bottom { bottom: -11px; }

  @keyframes neonBorderPulse {
    0% {
      border-color: rgba(0, 210, 255, 0.4) !important;
      box-shadow: 0 0 6px rgba(0, 210, 255, 0.2);
    }
    100% {
      border-color: rgba(0, 210, 255, 1) !important;
      box-shadow: 0 0 18px rgba(0, 210, 255, 0.6);
    }
  }

  @keyframes labelGlowPulse {
    0% { text-shadow: 0 0 2px rgba(0, 210, 255, 0.3); box-shadow: 0 0 4px rgba(0, 210, 255, 0.1); }
    100% { text-shadow: 0 0 8px rgba(0, 210, 255, 0.8); box-shadow: 0 0 10px rgba(0, 210, 255, 0.3); }
  }

  /* MOBILE RESPONSIVENESS */
  @media (max-width: 600px) {
    .wrapper { padding: 20px !important; margin: 10px auto !important; }
    .nav-link { font-size: 15px !important; padding: 8px 10px !important; }
    .nav-container { gap: 8px; }
    img, video { width: 100% !important; }

    .media-aligned-row {
      flex-direction: column !important;
      gap: 15px !important;
    }
    .media-aligned-row img, .media-aligned-row a {
      width: 100% !important;
      max-width: 100% !important;
      aspect-ratio: auto !important; 
    }
    .border-label { font-size: 9px !important; }
  }
</style>

<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=6">

<div class="wrapper">

  <div class="nav-container">
    <a href="./" class="nav-link">[ HOME ]</a>
    <a href="projects" class="nav-link">[ PROJECTS ]</a>
    <a href="experience" class="nav-link">[ EXPERIENCE ]</a>
    <a href="videos" class="nav-link active">[ VIDEOS ]</a> 
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

  <div class="media-aligned-row" style="display: flex; justify-content: center; align-items: center; gap: 1.5%; width: 100%; margin: 25px 0;">
    
    <div style="flex: 1; min-width: 0; position: relative; padding: 10px 0;">
      <a href="https://youtu.be/gpvk6R97cx4?si=3UoBg4MYX4fRFkA6" target="_blank" class="animated-video-card">
        <span class="border-label label-top">CLICK HERE</span>
        <img src="ThumbnailYT1 .jpg" alt="Watch Robotic Fundamentals Ep.1">
        <span class="border-label label-bottom">CLICK HERE</span>
      </a>
    </div>

    <div style="flex: 1; min-width: 0;">
      <img src="WhatYouWillLearnRFE1.png" alt="Curriculum Scope: What You Will Learn">
    </div>

    <div style="flex: 1; min-width: 0;">
      <img src="TeachPendant.jpg" alt="Industrial Robot Teach Pendant Unit">
    </div>


  </div>

</div>
