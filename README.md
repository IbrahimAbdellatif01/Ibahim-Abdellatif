<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ibrahim Abdellatif | Autonomous Systems Engineer</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1>Ibrahim Abdellatif</h1>
      <p>Autonomous Vehicles Engineer | Robotics & Control | Researcher</p>
      <a href="Ibrahim_Abdellatif_Resume.pdf" download class="button">Download CV</a>
    </div>
  </header>

  <section id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>
        I'm a master's student in Autonomous Vehicles Engineering at the University of Naples Federico II.
        I’m passionate about systems engineering and robotics, especially in trajectory optimization,
        path planning, and control systems. I aim to pioneer in the field of robotics.
      </p>
    </div>
  </section>

  <section id="education">
    <div class="container">
      <h2>Education</h2>
      <ul>
        <li>
          <strong>University of Naples Federico II</strong>, Italy  
          <br/>MSc in Autonomous Vehicles Engineering (2024–2026)
        </li>
        <li>
          <strong>Nile University</strong>, Egypt  
          <br/>BSc in Mechanical Engineering – Mechatronics & Robotics (2020–2024)  
          <br/>GPA: 3.49/4.0 | Dean’s List (Fall 2023)
        </li>
      </ul>
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2>Selected Projects</h2>
      <ul>
        <li><strong>UGV Motion Control:</strong> Quadruped robot control using RL (Spot Mini Mini based)</li>
        <li><strong>Cruise/Adaptive Cruise Control System:</strong> Multi-PID control with MATLAB simulation</li>
        <li><strong>Robotic Arm Control:</strong> Kinematics and simulation using CoppeliaSim and URDF</li>
      </ul>
    </div>
  </section>

  <section id="publications">
    <div class="container">
      <h2>Publications</h2>
      <ul>
        <li>“Innovations in 3D Printing-Assisted Biopolymers for Biomedical Applications”, Wiley (Book Chapter)</li>
        <li>“Optimization of Solar Tree Performance in Egypt”, SN Applied Sciences, Springer (2023)</li>
        <li>“Modeling and Control of a Self-Balancing Robot”, IEEE NILES 2022</li>
      </ul>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:ab.abdellatif@studenti.unina.it">ab.abdellatif@studenti.unina.it</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/ibrahim-abdellatif-aa6758150/" target="_blank">ibrahim-abdellatif</a></p>
      <p>GitHub: <a href="https://github.com/ibrahim-abdellatif" target="_blank">github.com/ibrahim-abdellatif</a></p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Ibrahim Abdellatif. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>

* {
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  color: #333;
  background: #f4f4f4;
  line-height: 1.6;
}

.container {
  width: 90%;
  max-width: 800px;
  margin: auto;
  padding: 40px 20px;
}

header {
  background: #2c3e50;
  color: white;
  padding: 60px 0;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 2.8em;
}

header p {
  margin: 10px 0 20px;
}

.button {
  background: #e67e22;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 4px;
  font-weight: bold;
}

.button:hover {
  background: #d35400;
}

section {
  margin-top: 30px;
}

section h2 {
  color: #2c3e50;
  margin-bottom: 10px;
}

ul {
  list-style-type: disc;
  padding-left: 20px;
}

a {
  color: #2980b9;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

footer {
  background: #ecf0f1;
  text-align: center;
  padding: 20px 0;
  font-size: 0.9em;
  color: #777;
  margin-top: 40px;
}
