<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chaitanay Kapoor | GitHub README</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #1f1c2c, #928dab);
      color: #fff;
      overflow-x: hidden;
    }
    .hero {
      text-align: center;
      padding: 50px 20px;
      animation: fadeIn 2s ease-in;
    }
    .hero h1 {
      font-size: 3rem;
      background: linear-gradient(45deg, #00f260, #0575e6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .hero p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    .links a {
      margin: 10px;
      text-decoration: none;
      color: #fff;
      border: 2px solid #fff;
      padding: 10px 20px;
      border-radius: 30px;
      transition: all 0.3s ease-in-out;
    }
    .links a:hover {
      background: #fff;
      color: #1f1c2c;
    }
    .section {
      padding: 40px 20px;
      animation: slideUp 1s ease-in forwards;
      opacity: 0;
    }
    .section:nth-child(even) {
      background: rgba(255, 255, 255, 0.05);
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      text-align: center;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    ul li {
      padding: 10px 0;
      text-align: center;
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(-20px);}
      to {opacity: 1; transform: translateY(0);}
    }
    @keyframes slideUp {
      to {opacity: 1; transform: translateY(0);}
    }
    .github-stats {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 30px;
    }
    .github-stats img {
      width: 300px;
      border-radius: 20px;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
    }
  </style>
</head>
<body>
  <div class="hero">
    <h1>Hi, I'm Chaitanay Kapoor 👋</h1>
    <p>Web Developer | Data Analyst | Cloud Enthusiast</p>
    <div class="links">
      <a href="https://linkedin.com/in/chaitanay-kapoor">LinkedIn</a>
      <a href="https://github.com/chaitanay2004">GitHub</a>
    </div>
  </div>

  <div class="section" style="animation-delay: 0.5s;">
    <h2>🚀 Skills</h2>
    <ul>
      <li>Programming: C, C++, Java, JavaScript</li>
      <li>Web: HTML, CSS, Node.js, Express.js</li>
      <li>Databases: MySQL, MongoDB</li>
      <li>Tools: Git, VS Code, Power BI, R Studio</li>
      <li>Cloud: AWS, Cloudinary</li>
    </ul>
  </div>

  <div class="section" style="animation-delay: 1s;">
    <h2>🛠 Projects</h2>
    <ul>
      <li><a href="https://github.com/chaitanay2004/Task-Manager">Task Manager</a> — Task management system with JWT Auth & Cloudinary uploads.</li>
      <li><a href="https://github.com/chaitanay2004/Simon_game">Simon Game</a> — Fun interactive dice game with animations.</li>
    </ul>
  </div>

  <div class="section" style="animation-delay: 1.5s;">
    <h2>📊 GitHub Stats</h2>
    <div class="github-stats">
      <img src="https://github-readme-stats.vercel.app/api?username=chaitanay2004&show_icons=true&theme=radical" alt="GitHub Stats">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=chaitanay2004&theme=radical" alt="GitHub Streak">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chaitanay2004&layout=compact&theme=radical" alt="Top Languages">
    </div>
  </div>

  <div class="section" style="animation-delay: 2s;">
    <h2>📫 Let's Connect</h2>
    <p>Email: chaitanay.kapoor1206@gmail.com</p>
    <p>LinkedIn: <a href="https://linkedin.com/in/chaitanay-kapoor">chaitanay-kapoor</a></p>
    <p>GitHub: <a href="https://github.com/chaitanay2004">chaitanay2004</a></p>
  </div>
</body>
</html>
