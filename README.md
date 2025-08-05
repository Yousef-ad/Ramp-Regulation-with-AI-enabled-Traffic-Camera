<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ramp Regulation with AI</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f6f8;
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }
    h1, h2, h3 {
      color: #003366;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      background: white;
      padding: 30px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    ul {
      margin-top: 0;
    }
    table {
      border-collapse: collapse;
      width: 100%;
      margin: 20px 0;
    }
    th, td {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: left;
    }
    img {
      display: block;
      margin: 20px auto;
      max-width: 90%;
      border: 1px solid #ccc;
    }
    a {
      color: #0066cc;
      text-decoration: none;
    }
    .section {
      margin-top: 40px;
    }
    .author {
      margin-top: 60px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Ramp Regulation with AI-Enabled Traffic Camera</h1>

    <div class="section">
      <h2>Overview</h2>
      <p>This project implements an Automatic Ramp Regulation system targeting ramp traffic congestion. By leveraging advanced video processing techniques, the system analyzes live freeway traffic conditions at ramp entry points, estimates congestion levels, and dynamically regulates traffic flow via a traffic light mechanism.</p>
    </div>

    <div class="section">
      <h2>Key Features</h2>
      <ul>
        <li><strong>AI-Powered Video Analytics:</strong> Detects, tracks, and estimates the speed of vehicles using OpenCV and custom logic.</li>
        <li><strong>Automatic Ramp Metering:</strong> Dynamically adjusts traffic light timing based on real-time traffic flow and density.</li>
        <li><strong>Simple, Stand-Alone Deployment:</strong> Requires only a single camera. No cloud dependency. Works offline in edge environments.</li>
        <li><strong>Reliable under all conditions:</strong> Supports standard 3-lane roads, low-light/nighttime operation, and adverse weather conditions.</li>
      </ul>
    </div>

    <div class="section">
      <h2>Tech Stack</h2>
      <table>
        <tr><th>Tool/Language</th><th>Role</th></tr>
        <tr><td>Python</td><td>Core logic, AI processing, traffic analytics</td></tr>
        <tr><td>OpenCV</td><td>Frame analysis, vehicle tracking</td></tr>
        <tr><td>YOLO</td><td>Deep learning-based vehicle detection</td></tr>
        <tr><td>Arduino IDE</td><td>Microcontroller integration for controlling traffic light/gate</td></tr>
        <tr><td>PTV VISSIM</td><td>Traffic simulation during development/testing</td></tr>
      </table>
    </div>

    <div class="section">
      <h2>Development Environment</h2>
      <ul>
        <li>OS: Windows 10 (21H2)</li>
        <li>Mode: Local/offline operation (no cloud dependency)</li>
        <li>Simulation: VISSIM for validation before real-world application</li>
      </ul>
    </div>

    <div class="section">
      <h2>System Architecture</h2>
      <img src="https://i.imgur.com/CsnjOjn.png" alt="System Architecture" />
    </div>

    <div class="section">
      <h2>Real-Time Verification</h2>
      <h3>No Traffic</h3>
      <img src="https://i.imgur.com/a1s4M1I.png" alt="No Traffic State" />

      <h3>Heavy Traffic</h3>
      <img src="https://i.imgur.com/DGg9FNW.png" alt="Heavy Traffic State" />
    </div>


    <div class="author">
      <p><strong>Yousef Aldahash</strong><br/>
      Computer Engineer<br/>
      <a href="mailto:dahash.yousef@gmail.com">dahash.yousef@gmail.com</a></p>
    </div>
  </div>
</body>
</html>
