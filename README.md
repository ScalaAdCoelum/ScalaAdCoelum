<!-- Dynamic animated constellation SVG header -->
<div align="center">
  <svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
    <style>
      @keyframes twinkle {
        0% { opacity: 0.2; }
        50% { opacity: 1; }
        100% { opacity: 0.2; }
      }
      @keyframes shooting-star {
        0% { transform: translateX(-50px) translateY(-50px); opacity: 0; }
        10% { opacity: 1; }
        90% { opacity: 1; }
        100% { transform: translateX(850px) translateY(250px); opacity: 0; }
      }
      .star {
        fill: #ffffff;
        animation: twinkle 3s infinite;
      }
      .shooting-star {
        animation: shooting-star 6s infinite linear;
      }
      .star:nth-child(2n) {
        animation-delay: 0.4s;
      }
      .star:nth-child(3n) {
        animation-delay: 0.8s;
      }
      .star:nth-child(4n) {
        animation-delay: 1.2s;
      }
      .star:nth-child(5n) {
        animation-delay: 1.6s;
      }
      .constellation-line {
        stroke: rgba(255, 255, 255, 0.3);
        stroke-width: 1;
      }
      .title-text {
        font-family: 'Arial', sans-serif;
        font-size: 36px;
        font-weight: bold;
        fill: #ffffff;
      }
      .subtitle-text {
        font-family: 'Arial', sans-serif;
        font-size: 18px;
        fill: #cccccc;
      }
    </style>
    
    <!-- Background constellation -->
    <rect width="100%" height="100%" fill="#111122" />
    
    <!-- Twinkling stars - random distribution -->
    <circle class="star" cx="50" cy="30" r="1.5" />
    <circle class="star" cx="120" cy="45" r="1" />
    <circle class="star" cx="220" cy="75" r="1.2" />
    <circle class="star" cx="320" cy="35" r="1.7" />
    <circle class="star" cx="450" cy="90" r="1.3" />
    <circle class="star" cx="550" cy="40" r="1" />
    <circle class="star" cx="630" cy="65" r="1.5" />
    <circle class="star" cx="720" cy="25" r="1.2" />
    <circle class="star" cx="730" cy="120" r="1.7" />
    <circle class="star" cx="670" cy="160" r="1" />
    <circle class="star" cx="540" cy="150" r="1.5" />
    <circle class="star" cx="370" cy="170" r="1.2" />
    <circle class="star" cx="280" cy="140" r="1" />
    <circle class="star" cx="180" cy="160" r="1.4" />
    <circle class="star" cx="70" cy="130" r="1.3" />
    
    <!-- Kim Dokja Constellation - simplified shape -->
    <path class="constellation-line" d="M400,60 L450,90 L500,70 L530,110 L480,130 L410,110 L400,60" />
    <circle class="star" cx="400" cy="60" r="2.5" />
    <circle class="star" cx="450" cy="90" r="2" />
    <circle class="star" cx="500" cy="70" r="2.2" />
    <circle class="star" cx="530" cy="110" r="2.5" />
    <circle class="star" cx="480" cy="130" r="2" />
    <circle class="star" cx="410" cy="110" r="2.2" />
    
    <!-- Shooting star animation -->
    <path class="shooting-star" d="M0,0 L15,0" stroke="#ffffff" stroke-width="2" stroke-linecap="round">
      <animateMotion dur="4s" repeatCount="indefinite" 
        path="M100,50 C200,100 600,120 700,170" />
    </path>
    
    <!-- Title and Subtitle -->
    <text x="400" y="100" class="title-text" text-anchor="middle">Yun | 윤</text>
    <text x="400" y="130" class="subtitle-text" text-anchor="middle">Game Developer & Fullstack Engineer</text>
  </svg>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Lover_of-Kim_Dokja-7E58C2?style=for-the-badge&logo=bookstack&logoColor=white" alt="Kim Dokja Fan"/>
  <img src="https://img.shields.io/badge/Top-Languages-F6CF71?style=for-the-badge&logo=dev.to&logoColor=white" alt="Top Languages"/>
  <img src="https://img.shields.io/badge/Game-Developer-47CF73?style=for-the-badge&logo=unity&logoColor=white" alt="Game Developer"/>
  <img src="https://img.shields.io/badge/Fullstack-Developer-4D94FF?style=for-the-badge&logo=javascript&logoColor=white" alt="Fullstack Developer"/>
</div>

## 📖 About Me

<img align="right" width="300" src="https://i.imgur.com/your-kdj-image-here.jpg" alt="Kim Dokja illustration"/>

Greetings, fellow reader of the ⭐ Star Stream ⭐! I'm **Yun**, a passionate game developer and fullstack engineer who believes in crafting digital worlds that tell meaningful stories.

Just as Kim Dokja navigated through countless scenarios with his knowledge, I navigate through code and design to create immersive experiences. My journey in development is driven by a desire to blend creativity with technical excellence.

### 🌟 My Developer Stats

```javascript
const yun = {
  languages: ["JavaScript", "TypeScript", "C#", "Python", "Java"],
  gamedev: ["Unity", "Unreal Engine", "Godot", "WebGL"],
  frontend: ["React", "Vue", "Angular", "Three.js"],
  backend: ["Node.js", "Express", "Django", "Spring Boot"],
  database: ["MongoDB", "PostgreSQL", "Firebase", "MySQL"],
  currentlyReading: "Omniscient Reader's Viewpoint - Episode 3",
  favoriteCharacter: "Kim Dokja (가장오래된꿈)"
};
```

## 🎮 Featured Projects

<div align="center">
  <table>
    <tr>
      <td width="50%">
        <h3 align="center">Project 1</h3>
        <p align="center">
          <a href="https://github.com/yourusername/project1">
            <img src="https://via.placeholder.com/300x180?text=Scenario+Simulator" alt="Project 1"/>
          </a>
          <p align="center">A narrative-driven game inspired by choice-based scenarios</p>
        </p>
      </td>
      <td width="50%">
        <h3 align="center">Project 2</h3>
        <p align="center">
          <a href="https://github.com/yourusername/project2">
            <img src="https://via.placeholder.com/300x180?text=Constellation+Viewer" alt="Project 2"/>
          </a>
          <p align="center">Interactive visualization of star constellations with mythology</p>
        </p>
      </td>
    </tr>
  </table>
</div>

## 💫 My Development Philosophy

Just as the Fourth Wall protects and guides, my code aims to be:

- **Resilient**: Handles edge cases gracefully
- **Transparent**: Well-documented and readable
- **Adaptable**: Ready for changing requirements
- **Performant**: Optimized for the best user experience

## 🔮 Let's Connect

<div align="center">
  <a href="mailto:your.email@example.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://twitter.com/yourusername">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
  <a href="https://linkedin.com/in/yourusername">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://discordapp.com/users/yourusername">
    <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/>
  </a>
</div>

<div align="center">
  <svg width="800" height="100" viewBox="0 0 800 100" xmlns="http://www.w3.org/2000/svg">
    <style>
      @keyframes flowing-stars {
        0% { transform: translateX(800px); }
        100% { transform: translateX(-800px); }
      }
      .star-stream {
        animation: flowing-stars 20s linear infinite;
      }
      .footer-text {
        font-family: 'Arial', sans-serif;
        font-size: 14px;
        fill: #999999;
      }
    </style>
    
    <!-- Star Stream footer -->
    <rect width="100%" height="100%" fill="#111122" />
    
    <!-- Flowing stars -->
    <g class="star-stream">
      <circle cx="50" cy="20" r="1" fill="white" />
      <circle cx="120" cy="40" r="1.2" fill="white" />
      <circle cx="190" cy="60" r="0.8" fill="white" />
      <circle cx="250" cy="30" r="1" fill="white" />
      <circle cx="310" cy="70" r="1.3" fill="white" />
      <circle cx="380" cy="20" r="0.9" fill="white" />
      <circle cx="450" cy="50" r="1.1" fill="white" />
      <circle cx="520" cy="30" r="0.8" fill="white" />
      <circle cx="590" cy="60" r="1" fill="white" />
      <circle cx="660" cy="25" r="1.2" fill="white" />
      <circle cx="730" cy="45" r="0.9" fill="white" />
      <circle cx="800" cy="70" r="1.1" fill="white" />
      <circle cx="870" cy="20" r="0.8" fill="white" />
      <circle cx="940" cy="50" r="1" fill="white" />
      <circle cx="1010" cy="30" r="1.2" fill="white" />
      <circle cx="1080" cy="60" r="0.9" fill="white" />
      <circle cx="1150" cy="25" r="1.1" fill="white" />
      <circle cx="1220" cy="45" r="0.8" fill="white" />
      <circle cx="1290" cy="70" r="1" fill="white" />
      <circle cx="1360" cy="20" r="1.2" fill="white" />
      <circle cx="1430" cy="50" r="0.9" fill="white" />
      <circle cx="1500" cy="30" r="1.1" fill="white" />
    </g>
    
    <text x="400" y="50" class="footer-text" text-anchor="middle">"The story was over but it wasn't over. The story wouldn't end unless the reader gave up on the story."</text>
  </svg>
</div>

<!-- GitHub stats -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ScalaAdCoelum&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ScalaAdCoelum&layout=compact&theme=tokyonight" alt="Top Languages" />
</div>
