<style>
  /* 1. BACKGROUND & LAYOUT FIX */
  html, body { 
    background-image: url('tech-bg.jpg') !important;
    background-size: cover !important;
    background-position: center !important;
    background-attachment: fixed !important;
    background-color: #010b1a !important; 
    color: #ffffff !important;
  }

  /* 2. HIDE THEME SIDEBAR, FOOTER, AND "DELIRIOUSGUY" HEADER */
  header, .sidebar, #header, aside, footer, .site-footer { display: none !important; }
  h1:first-of-type { display: none !important; }

  /* 3. CENTER CONTENT BOX WITHOUT BREAKING THE THEME */
  .wrapper { 
    max-width: 900px !important; 
    margin: 40px auto !important; 
    padding: 30px !important;
    background: rgba(1, 11, 26, 0.85) !important; 
    border: 1px solid #00d2ff !important; 
    border-radius: 8px !important;
    float: none !important;
    display: block !important;
  }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

  /* 4. TERMINAL TYPING ANIMATION (BLINKING FIX) */
  .terminal-title {
    display: inline-block !important;
    overflow: hidden; 
    border-right: .15em solid #00d2ff; 
    white-space: nowrap; 
    color: #00d2ff !important;
    font-family: 'Courier New', Courier, monospace !important;
    animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite !important;
  }

  @keyframes typing { from { width: 0 } to { width: 100% } }
  @keyframes blink-caret { from, to { border-color: transparent } 50% { border-color: #00d2ff; } }
</style>
<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=12">

<div class="wrapper">

<h1 align="center"><span class="terminal-title">Jeffery Baker | Robotics & Manufacturing</span></h1>

### Bridging Precision Fabrication with Automated Systems
I am a Robotics and Automated Manufacturing student at Lone Star College with a background in aerospace-grade welding. My work focuses on the intersection of physical builds and digital logic. [A.A.S Degree Path](https://www.lonestar.edu/programs-of-study/Engineering-Technician-AAS-Automated-Manufacturing.htm)

---

## 🛠️ Technical Skillset
* **Manufacturing:** Aluminum Mig Welding, Automated Machining, 3D Printing (Bambu Lab P2S), Industry 4.0
* **Electronics:** Raspberry Pi, Micro Sensors/Actuators, AC/DC Circuits
* **Robotics:** PLC Programming, Automated Manufacturing Systems, Hydraulics/Pneumatics, Universal Robots
* **Software:** CAD, Git/GitHub, Python3, Bambu/Creality/Cura Object Slicers, SolidWorks, VSCode/IDE's

---

## 🚀 Featured Projects

### <span class="terminal-title">[Raspberry Pi Ultrasonic Sensor Project]</span>
* **Goal:** Develop a real-time distance monitoring system using a Raspberry Pi Zero 2 W.

<p align="center">
  <img src="ultrasonic1.jpg" width="45%" alt="Sensor Build">
  <img src="ultrasonic2.jpg" width="45%" alt="Sensor in Action">
</p>

### <span class="terminal-title">[Raspberry Pi Active Buzzer System]</span>
* **Goal:** Create a programmable audible alert system.

<p align="center">
  <img src="buzzer_build.jpg" width="60%" alt="Buzzer Circuit">
</p>

---

## 📫 Connect with Me
* **LinkedIn:** [Jeffery L Baker](https://www.linkedin.com/in/jeffery-baker-15b767218/)
* **Email:** jlb107078@gmail.com
* [📄 View & Download My Full Resume](resume.md)

### ✉️ Send Me a Message
<form action="https://formspree.io/f/mpqjeoyw" method="POST" style="max-width: 500px;">
  <label>Your Email:</label><br>
  <input type="email" name="email" style="width: 100%; padding: 8px; margin-bottom: 10px;" required><br>
  <label>Your Message:</label><br>
  <textarea name="message" style="width: 100%; height: 100px; padding: 8px;" required></textarea><br>
  <button type="submit" style="background-color: #00d2ff; color: #010b1a; padding: 10px 20px; border: none; margin-top: 10px; cursor: pointer; font-weight: bold;">Send Message</button>
</form>

</div>

</div>
