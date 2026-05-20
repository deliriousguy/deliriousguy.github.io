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

  /* 3. NAVIGATION - BIGGER & CLEANER */
  .nav-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-bottom: 40px;
  }

  .nav-link {
    font-weight: bold;
    color: #00d2ff !important;
    text-decoration: none !important;
    white-space: nowrap;
    padding: 12px 20px;
    font-family: monospace;
    font-size: 15px;
    border: 1px solid transparent;
    border-radius: 4px;
    transition: all 0.3s ease;
  }

  .nav-link:hover {
    background: rgba(0, 210, 255, 0.1);
    border-color: #00d2ff;
    box-shadow: 0 0 10px rgba(0, 210, 255, 0.4);
  }

  /* 4. TEXT VISIBILITY & ANIMATION */
  p, li, label, span, em, strong { color: #ffffff !important; }
  h1, h2, h3, a { color: #00d2ff !important; text-shadow: 0 0 5px rgba(0, 210, 255, 0.5); }

  /* 5.1 PERMANENT ACTIVE TAB GLOW */
  .nav-link.active {
    background: rgba(0, 210, 255, 0.15) !important;
    border-color: #00d2ff !important;
    box-shadow: 0 0 15px rgba(0, 210, 255, 0.4) !important;
    border-radius: 4px;
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

<div class="wrapper">

  <div class="nav-container">
    <a href="./" class="nav-link active">[ HOME ]</a>
    <a href="projects" class="nav-link">[ PROJECTS ]</a>
    <a href="experience" class="nav-link">[ EXPERIENCE ]</a>
    <a href="videos" class="nav-link">[ VIDEOS ]</a>
    <a href="JEFFERY_BAKER_Resume_Orange.pdf" target="_blank" class="nav-link">[ RESUME ]</a>
  </div>

  <h1><span class="terminal-title">Jeffery Baker | Robotics & Automated Manufacturing</span></h1>

  <h3>⚡ The Bridge Between Precision & Automation</h3>
  <p>As a dedicated A.A.S. Robotics and Automated Manufacturing student graduating in December 2026, I bridge the gap between hands-on electro-mechanical hardware and smart automation. My technical training includes practical experience with industrial robots, cobots, PLC programming, industrial motor controls, sensor circuit integration, industrial welding, and SolidWorks design. I am currently seeking high-impact roles in Robotics Maintenance, Automation, Systems Integration, or Sensor Maintenance, where I can immediately deploy my self-directed troubleshooting skills to optimize operations and drive industrial efficiency.</p>

  <hr>

  <h2>🛠️ Core Competencies</h2>
  <ul>
    <li><strong>Automation:</strong> PLC Programming (Rockwell), Universal Robots, Fanuc Robots, Industry 4.0.</li>
    <li><strong>Electronics:</strong> Circuit Analysis, Sensors.</li>
    <li><strong>Fabrication:</strong> Aluminum MIG Welding, Automated Machining.</li>
    <li><strong>Systems:</strong> Electro-Hydraulics & Pneumatics, 3D Printing (Bambu Labs P2S), Bambu/Creality/Cura Slicers.</li>
    <li><strong>Design & Tools:</strong> CAD/SolidWorks, GitHub, VSCode/IDEs.</li>
    <li><strong>Methodology:</strong> Proactive problem solver / Analytical troubleshooter.</li>
  </ul>

  <hr>

  <h2>🚀 Recent Highlights</h2>
  <ul>
    <li><strong>Current Project:</strong> Creating a custom ESP32 bluetooth speaker. (Completed)</li>
    <li><strong>Latest Personal Project:</strong> Real-time distance monitoring system using Raspberry Pi Zero 2 W.</li>
    <li><strong>Credentials:</strong> Pursuing my <a href="https://www.lonestar.edu/programs-of-study/Engineering-Technician-AAS-Automated-Manufacturing-Technician.htm" target="_blank">A.A.S.</a> at Lone Star College (Expected Graduation: Dec 2026).</li>
  </ul>

  <hr>

  <h2>📬 Quick Connect</h2>
  <ul>
    <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/jeffery-baker-15b767218/" target="_blank">Jeffery L Baker</a></li>
    <li><strong>Email:</strong> Jlb107078@gmail.com</li>
    <li><strong>Location:</strong> Spring, Texas</li>
  </ul>

  <form action="https://formspree.io/f/mpqjeoyw" method="POST" style="max-width: 500px; margin-top: 25px;">
    <label style="font-weight: bold; font-family: monospace; color: #00d2ff !important;">Send a Quick Message:</label><br><br>
    <input type="email" name="email" placeholder="Your Email" style="width: 100%; padding: 10px; margin-bottom: 15px;" required><br>
    <textarea name="message" placeholder="Your Message" style="width: 100%; height: 100px; padding: 10px; margin-bottom: 15px;" required></textarea><br>
    <button type="submit" style="background-color: #00d2ff; color: #010b1a; padding: 12px 24px; border: none; cursor: pointer; font-weight: bold; font-family: monospace; border-radius: 4px; box-shadow: 0 0 10px rgba(0, 210, 255, 0.3);">SEND MESSAGE</button>
  </form>

</div>
