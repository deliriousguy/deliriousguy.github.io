<style>
  /* 1. GLOBAL RESET: FORCE BACKGROUND & HIDE THEME UI */
  html, body { 
    background-image: url('tech-bg.jpg') !important;
    background-size: cover !important;
    background-position: center !important;
    background-attachment: fixed !important;
    background-color: #010b1a !important; 
    margin: 0 !important;
    padding: 0 !important;
  }
  header, .sidebar, footer, .site-footer, h1:first-of-type { display: none !important; }

  /* 2. MAIN CONTAINER: SHIELDS CONTENT FROM THEME JUMBLE */
  .portfolio-container {
    max-width: 900px;
    margin: 40px auto;
    padding: 35px;
    background: rgba(1, 11, 26, 0.92); /* Darker for crisp text contrast */
    border: 2px solid #00d2ff;
    border-radius: 12px;
    color: #ffffff;
    font-family: 'Segoe UI', Arial, sans-serif;
    box-shadow: 0 0 30px rgba(0, 210, 255, 0.2);
    line-height: 1.6;
  }

  /* 3. TERMINAL TYPING ANIMATION (BLINKING FIX) */
  .terminal-title {
    display: inline-block;
    overflow: hidden; 
    border-right: .15em solid #00d2ff; 
    white-space: nowrap; 
    color: #00d2ff;
    font-family: 'Courier New', Courier, monospace;
    animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
  }

  @keyframes typing { from { width: 0 } to { width: 100% } }
  @keyframes blink-caret { from, to { border-color: transparent } 50% { border-color: #00d2ff; } }

  /* 4. CONTENT STYLING */
  h2, h3 { color: #00d2ff; border-bottom: 1px solid rgba(0, 210, 255, 0.3); padding-bottom: 8px; margin-top: 30px; }
  a { color: #00d2ff; text-decoration: none; font-weight: bold; }
  a:hover { text-decoration: underline; }
  .skill-list { list-style: none; padding-left: 0; }
  .skill-list li { margin-bottom: 10px; }
  .skill-list li b { color: #00d2ff; }
</style>

<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=14">

<div class="portfolio-container">

  <h1 align="center"><span class="terminal-title">Jeffery Baker | Robotics & Manufacturing</span></h1>
  
  <p align="center"><i>Lone Star College | Robotics & Automated Manufacturing Technology</i></p>
  
  <p>I am a robotics student and former aerospace-grade welder focused on the intersection of physical fabrication and automated systems logic. My expertise spans from high-precision metallurgy to Python-integrated circuit design.</p>

  <hr style="border: 0.5px solid #00d2ff; margin: 30px 0;">

  <h2>🛠️ Technical Skillset</h2>
  <ul class="skill-list">
    <li><b>Manufacturing:</b> Aluminum MIG Welding, Automated Machining, 3D Printing (Bambu Lab P2S)</li>
    <li><b>Electronics:</b> Raspberry Pi, Micro Sensors/Actuators, AC/DC Circuit Analysis</li>
    <li><b>Robotics:</b> PLC Programming, Automated Systems, Universal Robots, Hydraulics/Pneumatics</li>
    <li><b>Software:</b> Python3, CAD (SolidWorks), Git/GitHub, Object Slicing (Bambu/Cura)</li>
  </ul>

  <h2>🚀 Featured Projects</h2>
  
  <h3><span class="terminal-title">[Raspberry Pi Ultrasonic Sensor Project]</span></h3>
  <p>Real-time distance monitoring using a Raspberry Pi Zero 2 W and HC-SR04 sensor.</p>
  <div align="center">
    <img src="ultrasonic1.jpg" width="48%" style="border: 1px solid #00d2ff; border-radius: 4px; margin: 1%;">
    <img src="ultrasonic2.jpg" width="48%" style="border: 1px solid #00d2ff; border-radius: 4px; margin: 1%;">
  </div>

  <h3><span class="terminal-title">[Raspberry Pi Active Buzzer System]</span></h3>
  <p>Programmable audible alert system with transistor-based current amplification.</p>
  <div align="center">
    <img src="buzzer_build.jpg" width="70%" style="border: 1px solid #00d2ff; border-radius: 4px;">
  </div>

  <hr style="border: 0.5px solid #00d2ff; margin: 30px 0;">

  <h2>📫 Connect & Message</h2>
  <p><b>LinkedIn:</b> <a href="https://www.linkedin.com/in/jeffery-baker-15b767218/">Jeffery L Baker</a></p>
  <p><b>Email:</b> jlb107078@gmail.com | <a href="resume.md">📄 View Resume</a></p>

  <form action="https://formspree.io/f/mpqjeoyw" method="POST" style="margin-top: 20px;">
    <label>Your Email:</label><br>
    <input type="email" name="email" style="width: 100%; padding: 12px; margin: 8px 0; border: 1px solid #00d2ff; border-radius: 4px; background: #010b1a; color: white;" required><br>
    <label>Your Message:</label><br>
    <textarea name="message" style="width: 100%; height: 120px; padding: 12px; border: 1px solid #00d2ff; border-radius: 4px; background: #010b1a; color: white;" required></textarea><br>
    <button type="submit" style="background-color: #00d2ff; color: #010b1a; padding: 14px; border: none; border-radius: 4px; width: 100%; cursor: pointer; font-weight: bold; font-size: 16px;">SEND SYSTEM COMMAND</button>
  </form>

</div>
