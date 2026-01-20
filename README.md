<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Harsh Vardhan Singh | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}

body{
  font-family:Poppins,sans-serif;
  background:linear-gradient(135deg,#e0f2fe,#f8fafc);
  color:#0f172a;
}

/* ===== HEADER ===== */
header{
  background:linear-gradient(120deg,#2563eb,#06b6d4);
  color:#fff;
  text-align:center;
  padding:3.5rem 1rem;
}

header h1{font-size:2.6rem}
header p{margin-top:.6rem;font-size:1.05rem}

/* ===== BUTTONS ===== */
.header-buttons{
  margin-top:1.5rem;
  display:flex;
  justify-content:center;
  gap:1rem;
  flex-wrap:wrap;
}

.btn{
  text-decoration:none;
  padding:0.7rem 1.6rem;
  border-radius:10px;
  font-weight:600;
  display:flex;
  align-items:center;
  gap:0.5rem;
  transition:all .3s ease;
}

.btn.primary{
  background:#facc15;
  color:#1e293b;
}

.resume-btn{
  background:#22c55e;
  color:#fff;
}

.btn:hover{
  transform:translateY(-4px);
  box-shadow:0 10px 25px rgba(0,0,0,.25);
}

.icon{
  font-size:1.15rem;
}

/* ===== SECTIONS ===== */
section{
  max-width:1000px;
  margin:2rem auto;
  background:#fff;
  padding:2rem;
  border-radius:14px;
  box-shadow:0 12px 30px rgba(0,0,0,.08);
}

h2{
  color:#2563eb;
  margin-bottom:1rem;
}

ul li{margin:.4rem 0}

/* ===== PROJECTS ===== */
.projects div{
  background:#f1f5f9;
  padding:1rem;
  border-radius:10px;
  margin-bottom:1rem;
}

/* ===== FOOTER ===== */
footer{
  text-align:center;
  background:#1e3a8a;
  color:#fff;
  padding:1rem;
  margin-top:2rem;
}
</style>
</head>

<body>

<header>
  <h1>Harsh Vardhan Singh</h1>
  <p>MCA Student | Software & AI Enthusiast</p>
  <p>📍 Mathura, Uttar Pradesh | 📧 h706043605008@gmail.com | 📞 +91-9389083905</p>

  <!-- ACTION BUTTONS -->
  <div class="header-buttons">
    <a href="https://www.linkedin.com/in/your-linkedin-id"
       target="_blank"
       class="btn primary">
       🔗 LinkedIn
    </a>

    <a href="harsh_resume_GLAU.pdf"
       download
       class="btn resume-btn">
       <span class="icon">📥</span> Download Resume
    </a>
  </div>
</header>

<section>
  <h2>About Me</h2>
  <p>
    MCA student with strong foundations in software development, artificial intelligence,
    and data analysis. Passionate about building real-world applications using Java,
    Python, and modern tools.
  </p>
</section>

<section>
  <h2>Education</h2>
  <ul>
    <li><b>MCA</b> – GLA University, Mathura (CGPA: 8.22, Present)</li>
    <li><b>BCA</b> – Sanskriti University, Mathura (82.1%, 2020–2023)</li>
  </ul>
</section>

<section>
  <h2>Skills</h2>
  <ul>
    <li>Data Structures & Algorithms</li>
    <li>Artificial Intelligence</li>
    <li>Data Analysis & Visualization</li>
    <li>Languages: Java, Python, JavaScript, HTML</li>
    <li>Databases & Backend: MySQL, SQL, OpenCV</li>
    <li>Tools: VS Code, PyCharm, IntelliJ IDEA</li>
    <li>Soft Skills: Communication, Client Engagement, Problem Solving</li>
  </ul>
</section>

<section class="projects">
  <h2>Projects</h2>

  <div>
    <h3>Attendance Management System with Facial Recognition</h3>
    <p>
      Automated attendance system using Python, OpenCV and MySQL with real-time
      face recognition.
    </p>
  </div>

  <div>
    <h3>MIDI – Musical Instrument Digital Interface</h3>
    <p>
      Hand-gesture based musical system using OpenCV, cvzone and pygame.midi.
    </p>
  </div>

  <div>
    <h3>Cancer Treatment Appointment Scheduler</h3>
    <p>
      Java Swing & MySQL application for managing doctor-patient appointments.
    </p>
  </div>
</section>

<section>
  <h2>Achievements</h2>
  <ul>
    <li>National Creative Writing Winner – 2017 & 2018</li>
    <li>Participated in IET Hackathon & HackMIT Hackathon</li>
  </ul>
</section>

<section>
  <h2>Certifications</h2>
  <ul>
    <li>Ethics in Engineering Practice – NPTEL</li>
    <li>Cyber Security – Cisco</li>
    <li>Python Programming – MSME-PPDC</li>
    <li>Digital Marketing – MSME-PPDC</li>
  </ul>
</section>

<footer>
  <p>© 2026 Harsh Vardhan Singh</p>
</footer>

</body>
</html>
