<svg width="800" height="1200" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        @keyframes gradientBG {
          0% { background-position: 0% 50%; }
          50% { background-position: 100% 50%; }
          100% { background-position: 0% 50%; }
        }
        @keyframes fadeIn {
          from { opacity: 0; }
          to { opacity: 1; }
        }
        @keyframes typing {
          from { width: 0 }
          to { width: 100% }
        }
        @keyframes blink {
          50% { border-color: transparent }
        }
        :root {
          --primary-color: #58A6FF;
          --secondary-color: #FF7139;
          --text-color: #333;
          --bg-color: #f0f0f0;
        }
        body {
          font-family: 'Fira Code', monospace;
          background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
          background-size: 400% 400%;
          animation: gradientBG 15s ease infinite;
          color: var(--text-color);
          line-height: 1.6;
        }
        .container {
          max-width: 800px;
          margin: 0 auto;
          padding: 20px;
        }
        .header {
          text-align: center;
          padding: 40px 0;
          animation: fadeIn 2s;
        }
        .title {
          font-size: 2.5em;
          color: var(--primary-color);
          margin-bottom: 10px;
          overflow: hidden;
          white-space: nowrap;
          border-right: .15em solid var(--primary-color);
          width: 0;
          animation: 
            typing 3.5s steps(30, end) forwards,
            blink .75s step-end infinite;
        }
        .subtitle {
          font-size: 1.2em;
          color: var(--secondary-color);
        }
        .social-links {
          display: flex;
          justify-content: center;
          gap: 15px;
          margin-top: 20px;
        }
        .social-links a {
          transition: transform 0.3s ease;
        }
        .social-links a:hover {
          transform: translateY(-5px);
        }
        .stats {
          display: flex;
          justify-content: space-around;
          margin: 40px 0;
        }
        .stats img {
          border-radius: 10px;
          box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
          transition: transform 0.3s ease;
        }
        .stats img:hover {
          transform: scale(1.05);
        }
        .about-section {
          display: flex;
          justify-content: space-between;
          margin: 40px 0;
        }
        .about-column {
          width: 48%;
          background: rgba(255, 255, 255, 0.1);
          backdrop-filter: blur(10px);
          border-radius: 15px;
          padding: 20px;
          box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .about-column h3 {
          color: var(--primary-color);
          border-bottom: 2px solid var(--secondary-color);
          padding-bottom: 10px;
        }
        .tech-stack {
          text-align: center;
          margin: 40px 0;
        }
        .tech-stack img {
          margin: 5px;
          transition: transform 0.3s ease;
        }
        .tech-stack img:hover {
          transform: translateY(-5px);
        }
        .projects {
          display: flex;
          justify-content: space-around;
          flex-wrap: wrap;
          margin: 40px 0;
        }
        .project-card {
          width: 30%;
          background: rgba(255, 255, 255, 0.1);
          backdrop-filter: blur(10px);
          border-radius: 15px;
          padding: 20px;
          margin-bottom: 20px;
          box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
          transition: transform 0.3s ease;
        }
        .project-card:hover {
          transform: translateY(-10px);
        }
        .project-card img {
          width: 100%;
          border-radius: 10px;
          margin-bottom: 10px;
        }
        .connect {
          text-align: center;
          margin: 40px 0;
        }
        .fun-facts {
          background: rgba(255, 255, 255, 0.1);
          backdrop-filter: blur(10px);
          border-radius: 15px;
          padding: 20px;
          margin-top: 40px;
        }
        .fun-facts summary {
          cursor: pointer;
          color: var(--primary-color);
        }
        .footer {
          text-align: center;
          margin-top: 40px;
          padding: 20px 0;
          border-top: 2px solid var(--secondary-color);
        }
      </style>

      <div class="container">
        <header class="header">
          <h1 class="title">⚡ Hello, I'm @hacxk ⚡</h1>
          <p class="subtitle">Full-Stack Developer & Tech Enthusiast</p>
          <div class="social-links">
            <a href="https://twitter.com/hacxk"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" /></a>
            <a href="https://www.linkedin.com/in/razan-mohamed-a67362260/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
            <a href="https://your_website.com"><img src="https://img.shields.io/badge/Portfolio-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white" alt="Portfolio" /></a>
          </div>
        </header>

        <div class="stats">
          <img src="https://github-readme-stats.vercel.app/api?username=hacxk&show_icons=true&count_private=true&theme=react&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=hacxk&theme=black-ice&hide_border=true&stroke=0000&background=0D1117" alt="GitHub Streak" />
        </div>

        <div class="about-section">
          <div class="about-column">
            <h3>🧙‍♂️ About Me</h3>
            <ul>
              <li>🇱🇰 Sri Lankan Full-Stack Developer</li>
              <li>☕ Fueled by coffee and curiosity</li>
              <li>🚀 Always learning and building</li>
              <li>🎓 Computer Science graduate (TODO)</li>
              <li>💼 Open for exciting opportunities</li>
            </ul>
          </div>
          <div class="about-column">
            <h3>💻 Current Focus</h3>
            <ul>
              <li>🌐 Mastering Next.js and React</li>
              <li>🤖 Exploring AI and Machine Learning</li>
              <li>📊 Data visualization with D3.js (TODO)</li>
              <li>🔐 Studying cybersecurity best practices</li>
              <li>📱 Mobile app development with React Native (TODO)</li>
            </ul>
          </div>
        </div>

        <div class="tech-stack">
          <h2>🛠️ Technologies & Tools</h2>
          <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
          <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
          <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
          <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
          <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
          <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
          <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
          <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
          <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
          <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
          <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
          <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
        </div>

        <h2>🚀 Featured Projects</h2>
        <div class="projects">
          <div class="project-card">
            <img src="https://via.placeholder.com/150" alt="Project 1"/>
            <h3>AI-Powered Task Manager</h3>
            <p>A smart task management system using AI to prioritize and optimize your workflow.</p>
          </div>
          <div class="project-card">
            <img src="https://via.placeholder.com/150" alt="Project 2"/>
            <h3>Blockchain Voting System</h3>
            <p>Secure and transparent voting platform built on blockchain technology.</p>
          </div>
          <div class="project-card">
            <img src="https://via.placeholder.com/150" alt="Project 3"/>
            <h3>AR Shopping Experience</h3>
            <p>Augmented Reality app for an immersive online shopping experience.</p>
          </div>
        </div>

        <div class="connect">
          <h2>📫 Let's Connect!</h2>
          <p>I'm always excited to collaborate on innovative projects and discuss the latest in tech. Whether you have a groundbreaking idea or just want to chat, don't hesitate to reach out!</p>
          <div class="social-links">
            <a href="mailto:zaidzeenathe@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
            <a href="https://github.com/hacxk"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
            <a href="https://www.hackerrank.com/zaidzeenathe"><img src="https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white" alt="HackerRank" /></a>
          </div>
        </div>

        <div class="fun-facts">
          <details>
            <summary>🎉 Fun Facts</summary>
            <ul>
              <li>🎵 Coding playlist: A mix of lo-fi beats and 80s synthwave</li>
              <li>🍕 Favorite debugging fuel: Extra cheesy pizza with a side of algorithms</li>
              <li>📚 Currently reading: "Clean Code" by Robert C. Martin</li>
              <li>🎮 When not coding: Exploring virtual worlds or solving Rubik's cubes</li>
              <li>💡 Life motto: "Why use many lines when few line do trick?" - Kevin Malone</li>
            </ul>
          </details>
        </div>

        <footer class="footer">
          <p>
            <img src="https://komarev.com/ghpvc/?username=hacxk&color=blueviolet&style=flat-square&label=Profile+Visitors" alt="Profile Visitors" />
          </p>
          <h4>💖 Crafted with ❤️ in Sri Lanka | Open to exciting opportunities worldwide! 💖</h4>
        </footer>
      </div>
    </div>
  </foreignObject>
</svg>
