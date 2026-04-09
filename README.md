<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ritik Kumar | Video Editor</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background: #020617;
  color: white;
}

nav {
  display: flex;
  justify-content: space-between;
  padding: 20px 50px;
  position: fixed;
  width: 100%;
  background: rgba(0,0,0,0.5);
  backdrop-filter: blur(10px);
}

nav h2 {
  color: #22c55e;
}

nav a {
  color: white;
  margin-left: 20px;
  text-decoration: none;
}

.hero {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
}

.hero h1 {
  font-size: 50px;
}

.hero span {
  color: #22c55e;
}

.hero p {
  margin-top: 10px;
  color: #94a3b8;
}

.btn {
  margin-top: 20px;
  padding: 12px 25px;
  border-radius: 25px;
  background: #22c55e;
  color: black;
  text-decoration: none;
  transition: 0.3s;
}

.btn:hover {
  transform: scale(1.1);
}

section {
  padding: 80px 20px;
  max-width: 1000px;
  margin: auto;
}

h2 {
  text-align: center;
  margin-bottom: 30px;
}

.card {
  background: #0f172a;
  padding: 20px;
  border-radius: 15px;
  margin-top: 20px;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-10px);
}

.skills {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px,1fr));
  gap: 20px;
}

footer {
  text-align: center;
  padding: 20px;
  color: #94a3b8;
}
</style>
</head>

<body>

<nav>
  <h2>Ritik</h2>
  <div>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
  </div>
</nav>

<div class="hero">
  <h1>I am <span>Ritik Kumar</span></h1>
  <p>Professional Video Editor 🎬</p>
  <a href="#contact" class="btn">Hire Me</a>
</div>

<section id="about">
  <h2>About Me</h2>
  <div class="card">
    Passionate video editor creating cinematic and engaging content for YouTube & Instagram.
  </div>
</section>

<section id="skills">
  <h2>My Skills</h2>
  <div class="skills">
    <div class="card">Video Editing</div>
    <div class="card">Reels Editing</div>
    <div class="card">YouTube Editing</div>
    <div class="card">Color Grading</div>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="card">Coming Soon 🚀</div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <div class="card">
    Email: your@email.com <br>
    Instagram: @yourhandle
  </div>
</section>

<footer>
  © 2026 Ritik Kumar
</footer>

</body>
</html>
