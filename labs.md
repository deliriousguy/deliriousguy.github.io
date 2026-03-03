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
    background: rgba(1, 11, 26, 0.8) !important; 
    border: 1px solid #00d2ff !important; 
    border-radius: 8px !important;
    box-shadow: 0 0 25px rgba(0, 210, 255, 0.3) !important;
  }

  /* 3. TEXT VISIBILITY */
  p, li, label, span, em, strong { 
    color: #ffffff !important; 
  }
  
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
    overflow: hidden; 
    border-right: .15em solid #00d2ff; 
    white-space: nowrap; 
    margin: 0 auto; 
    letter-spacing: .10em; 
    animation: typing 3.5s steps(40, end), blink-caret
