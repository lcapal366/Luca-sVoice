<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Luca's Voice | Professional Voice Actor</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #2f3542; /* slate background */
      color: #fff;
    }
    header {
      background: linear-gradient(135deg, #2c3e50, #34495e);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }
    header h1 {
      font-size: 3em;
      margin: 0;
    }
    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }
    .main-container {
      display: flex;
      justify-content: center;
      align-items: flex-start;
      gap: 20px;
      margin: 40px auto;
      max-width: 1400px;
    }
    .left-column {
      flex: 1;
      display: flex;
      flex-direction: column;
      gap: 20px;
      max-width: 300px;
    }
    .side-box {
      padding: 20px;
      border-radius: 8px;
      background: #1a252f;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
    .side-box h2 {
      text-align: center; /* headings centered */
      color: #f1f1f1;
      margin-bottom: 15px;
    }
    .project-item {
      display: flex;
      align-items: center;
      justify-content: flex-start; /* keep links left-aligned */
      margin-bottom: 15px;
    }
    .project-item img {
      width: 28px;
      height: 28px;
      margin-right: 10px;
    }
    .project-item a {
      color: #f1f1f1;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    .project-item a:hover {
      color: #e74c3c;
    }
    .contact {
      text-align: center; /* center contact text and button */
    }
    .contact p {
      margin-bottom: 10px;
    }
    .contact a {
      display: inline-block;
      margin-top: 10px;
      padding: 12px 24px;
      background: #2c3e50;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      transition: background 0.3s ease;
    }
    .contact a:hover {
      background: #000;
    }
    .about-box {
      flex: 2.5; /* bigger center box */
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      background: linear-gradient(135deg, #2c3e50, #34495e);
    }
    .about-box h2 {
      text-align: center;
      color: #f1f1f1;
    }
    .bio {
      line-height: 1.6;
      font-size: 1.1em;
      text-align: center;
    }
    .photo {
      text-align: center;
      margin: 30px 0;
    }
    .photo img {
      max-width: 200px; /* smaller headshot */
      border-radius: 50%;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
    }
    .demos {
      margin-top: 30px;
      text-align: center;
    }
    .demo-item {
      margin-bottom: 20px;
    }
    audio {
      width: 100%;
      outline: none;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #2c3e50;
      color: white;
      margin-top: 40px;
    }
    footer p {
      margin: 0;
      font-size: 0.9em;
    }
 
  </style>
</head>
<body>

  <header>
    <h1>Luca's Voice</h1>
    <p>Theatre-Born Voice Actor & Automotive Engineer</p>
  </header>

  <div class="main-container">
    <!-- Left column with projects and contact stacked -->
    <div class="left-column">
      <div class="side-box">
        <h2>Current Projects</h2>
        <div class="project-item">
          <img src="youtube-icon.png" alt="YouTube Icon">
          <a href="https://www.youtube.com/@AnimeSimplyExplained" target="_blank">Anime Simply Explained</a>
        </div>
        <div class="project-item">
          <img src="youtube-icon.png" alt="YouTube Icon">
          <a href="https://www.youtube.com/@SajaBoysBlox" target="_blank">Saja Boys Blox</a>
        </div>
      </div>

      <div class="side-box">
        <h2>Contact</h2>
        <div class="contact">
          <p>Interested in working together? Reach out to me via email:</p>
          <a href="mailto:lcapal366@gmail.com">lcapal366@gmail.com</a>
        </div>
      </div>
    </div>

    <!-- Center about box -->
    <div class="about-box">
      <h2>About Me</h2>
      <div class="bio">
        <p>Hey! I’m <strong>Luca Capaldi</strong>, a 22-year-old engineer, born in England and high schooled in the U.S., with 8 years of theatre and voice work experience. I’ve performed on stage and behind the mic in lots of productions.</p>
        <p>Having lived and traveled around the world, I bring a flexible accent toolkit (native British, a comfortable American and Australian, as well as conversational Italian) to every role. I'm reliable, creative, and technically minded. My goal is to deliver authentic performances that make your projects shine.</p>
      </div>

      <div class="photo">
        <img src="Headshot.jpg" alt="Photo of Luca Capaldi">
      </div>

      <h2>Voice Demo</h2>
      <div class="demos">
        <div class="demo-item">
          <p>Demo Reel</p>
          <audio controls>
            <source src="Demo Reel.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
          </audio>
        </div>
      </div>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 Luca's Voice | All Rights Reserved</p>
  </footer>


</body>
</html>
