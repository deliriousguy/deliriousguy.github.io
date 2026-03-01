<style>
  /* 1. TECH BACKGROUND SETUP */
  html, body { 
    background-image: url('tech-bg.jpg') !important;
    background-size: cover !important;
    background-position: center !important;
    background-attachment: fixed !important;
    background-color: #010b1a !important; 
    color: #ffffff !important; /* Forces primary text to white */
  }

  /* 2. SEMI-TRANSPARENT CONTENT BOX */
  .wrapper { 
    max-width: 900px !important; 
    margin: 40px auto !important; 
    padding: 40px !important;
    float: none !important;
    display: block !important;
    background: rgba(1, 11, 26, 0.8) !important; /* Darker blue with transparency */
    border: 1px solid #00d2ff !important; 
    border-radius: 8px !important;
    box-shadow: 0 0 25px rgba(0, 210, 255, 0.3) !important;
  }

  /* 3. FIXING TEXT VISIBILITY (The Gray Words) */
  p, li, label, span, em, strong { 
    color: #ffffff !important; /* Changes all body/gray text to crisp white */
  }
  
  /* NEON BLUE ACCENTS FOR HEADINGS & LINKS */
  h1, h2, h3, a { 
    color: #00d2ff !important; 
    text-shadow: 0 0 5px rgba(0, 210, 255, 0.5);
  }

  /* 4. LAYOUT CLEANUP */
  header, .sidebar, #header, aside, footer, .site-footer { display: none !important; }
  h1:first-of-type { display: none !important; }
  section { width: 100% !important; float: none !important; margin: 0 !important; }

  /* TERMINAL TYPING ANIMATION */
.terminal-title {
  display: inline-block;
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: .15em solid #00d2ff; /* The typewriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; 
  letter-spacing: .10em; 
  animation: 
    typing 3.5s steps(40, end),
    blink-caret .75s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: #00d2ff; }
}
/* MOBILE RESPONSIVENESS FIXES */
@media (max-width: 600px) {
  /* 1. Reduces padding so the box has more room on small screens */
  .wrapper {
    padding: 20px !important;
    margin: 10px auto !important;
  }

  /* 2. Shrinks the text and allows it to wrap so it stays inside the blue box */
  .terminal-title {
    font-size: 16px !important; 
    white-space: normal !important; /* Allows text to wrap to the next line */
    border-right: none !important;  /* Hides the blinking cursor on mobile to avoid layout bugs */
    animation: none !important;     /* Disables the typing animation on mobile for better readability */
    display: block !important;
  }

  /* 3. Ensures the images scale down properly */
  img, video {
    width: 100% !important;
    margin-bottom: 15px !important;
  }
}
</style>

<link rel="icon" type="image/png" href="https://jlb-robotics.me/favicon.png?v=6">

# Jeffery Baker | Robotics & Advanced Manufacturing

### Bridging Precision Fabrication with Automated Systems
I am a Robotics and Automated Manufacturing student at Lone Star College with a background in aerospace-grade welding. My work focuses on the intersection of physical builds and digital logic.
[A.A.S Degree Path](https://www.lonestar.edu/programs-of-study/Engineering-Technician-AAS-Automated-Manufacturing-Technician.htm)
---

## 🛠️ Technical Skillset
* **Manufacturing:** Aluminum Mig Welding, Automated Machining, 3D Printing (Bambu Lab P2S), Industry 4.0
* **Electronics:** Raspberry Pi, Micro Sensors/Actuators, AC/DC Circuits
* **Robotics:** PLC Programming, Automated Manufacturing Systems, Electro-Hydraulics/Pnuematics, Universal Robots
* **Software:** CAD, GitHub, Python3, Bumbu/Creality/Cura Object Slicers, SolidWorks, VSCode/IDE's (Integrated Development Environment)
 

---

## 🚀 Featured Projects

### <span class="terminal-title">[Raspberry Pi Ultrasonic Sensor Project]</span>
* **The Goal:** Develop a real-time distance monitoring system using a Raspberry Pi Zero 2 W.
* **Technical Specs:**
    * **Hardware:** HC-SR04 Ultrasonic Sensor, 1kΩ and 2kΩ resistors (Voltage Divider for GPIO safety).
    * **Logic:** Python-based script using the `RPi.GPIO` library to trigger 10µs sonic bursts.
    * **Pins Used:** GPIO 23 (Trigger), GPIO 24 (Echo).
<p align="center">
  <img src="UltrasonicSensor1.jpg" width="45%" alt="Sensor Build Close-up">
  <img src="UltrasonicSensor2.jpg" width="45%" alt="Sensor in Action">
</p>
<p align="center">
  <video src="UltrasonicSensor.mp4" width="45%" controls>
    Your browser does not support the video tag.
  </video>
</p>

### <span class="terminal-title">[Raspberry Pi Active Buzzer System]</span>
* **The Goal:** Create a programmable audible alert system.
* **Technical Specs:**
    * **Hardware:** 5V Active Buzzer, PN2222 Transistor (for current amplification).
    * **Logic:** Pulse Width Modulation (PWM) frequency control to manage alert tones.
    * **Pins Used:** GPIO 18 (PWM Output).
<p align="center">
  <img src="buzzer_build.jpg" width="45%" alt="Active Buzzer Circuit">
</p>
<p align="center">
  <video src="buzzer_build.mp4" width="45%" controls>
    Your browser does not support the video tag.
  </video>
</p>
---



### [Aerospace Welding Portfolio]
* High-precision fabrication experience within the Communications industry, focusing on metallurgy and structural integrity.
<p align="center">
  <img src="AluWeld.jpg" width="45%" />
  <img src="20241213_092023.jpg" width="45%" />
</p>

---

## 📬 Connect with Me
* **Location:** Spring, Texas
* **LinkedIn:** [Jeffery L Baker](https://www.linkedin.com/in/jeffery-baker-15b767218/)
* **Email:** [Jlb107078@gmail.com](Jlb107078@gmail.com)
* [📄 View & Download My Full Resume](resume.md)
* ### ✉️ Send Me a Message
<form action="https://formspree.io/f/mpqjeoyw" method="POST" style="max-width: 500px;">
  <label>Your Email:</label><br>
  <input type="email" name="email" style="width: 100%; padding: 8px; margin-bottom: 10px;" required><br>
  
  <label>Your Message:</label><br>
  <textarea name="message" style="width: 100%; height: 100px; padding: 8px;" required></textarea><br>
  
  <button type="submit" style="background-color: #333; color: white; padding: 10px 20px; border: none; margin-top: 10px; cursor: pointer;">Send Message</button>
</form>
</div>
