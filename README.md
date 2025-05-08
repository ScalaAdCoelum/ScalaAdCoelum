<svg viewBox="0 0 800 250" xmlns="http://www.w3.org/2000/svg">
  <!-- Background with stars effect (Star Stream theme) -->
  <defs>
    <!-- Gradients for background -->
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f2027" />
      <stop offset="50%" stop-color="#203a43" />
      <stop offset="100%" stop-color="#2c5364" />
    </linearGradient>
    
    <!-- Star particle -->
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    
    <!-- Shooting star animation -->
    <linearGradient id="shootingStarGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="rgba(255, 255, 255, 0)" />
      <stop offset="50%" stop-color="rgba(255, 255, 255, 0.8)" />
      <stop offset="100%" stop-color="rgba(255, 255, 255, 0)" />
    </linearGradient>
  </defs>
  
  <!-- Background -->
  <rect width="800" height="250" fill="url(#bgGradient)" />
  
  <!-- Static stars -->
  <g class="stars">
    <circle cx="50" cy="30" r="1" fill="white" filter="url(#glow)" opacity="0.7">
      <animate attributeName="opacity" values="0.7;0.2;0.7" dur="3s" repeatCount="indefinite" />
    </circle>
    <circle cx="120" cy="60" r="1.5" fill="white" filter="url(#glow)" opacity="0.5">
      <animate attributeName="opacity" values="0.5;0.9;0.5" dur="4s" repeatCount="indefinite" />
    </circle>
    <circle cx="200" cy="40" r="1" fill="white" filter="url(#glow)" opacity="0.6">
      <animate attributeName="opacity" values="0.6;0.3;0.6" dur="5s" repeatCount="indefinite" />
    </circle>
    <circle cx="280" cy="70" r="1.2" fill="white" filter="url(#glow)" opacity="0.8">
      <animate attributeName="opacity" values="0.8;0.4;0.8" dur="6s" repeatCount="indefinite" />
    </circle>
    <circle cx="350" cy="30" r="1" fill="white" filter="url(#glow)" opacity="0.7">
      <animate attributeName="opacity" values="0.7;0.3;0.7" dur="4.5s" repeatCount="indefinite" />
    </circle>
    <circle cx="420" cy="50" r="1.2" fill="white" filter="url(#glow)" opacity="0.6">
      <animate attributeName="opacity" values="0.6;0.2;0.6" dur="5.5s" repeatCount="indefinite" />
    </circle>
    <circle cx="500" cy="35" r="1" fill="white" filter="url(#glow)" opacity="0.5">
      <animate attributeName="opacity" values="0.5;0.9;0.5" dur="3.5s" repeatCount="indefinite" />
    </circle>
    <circle cx="580" cy="65" r="1.3" fill="white" filter="url(#glow)" opacity="0.7">
      <animate attributeName="opacity" values="0.7;0.3;0.7" dur="4s" repeatCount="indefinite" />
    </circle>
    <circle cx="650" cy="45" r="1" fill="white" filter="url(#glow)" opacity="0.6">
      <animate attributeName="opacity" values="0.6;0.2;0.6" dur="5s" repeatCount="indefinite" />
    </circle>
    <circle cx="720" cy="25" r="1.2" fill="white" filter="url(#glow)" opacity="0.8">
      <animate attributeName="opacity" values="0.8;0.4;0.8" dur="6s" repeatCount="indefinite" />
    </circle>
    <!-- More stars scattered around -->
    <circle cx="100" cy="130" r="1" fill="white" filter="url(#glow)" opacity="0.7">
      <animate attributeName="opacity" values="0.7;0.3;0.7" dur="5s" repeatCount="indefinite" />
    </circle>
    <circle cx="180" cy="150" r="1.1" fill="white" filter="url(#glow)" opacity="0.5">
      <animate attributeName="opacity" values="0.5;0.9;0.5" dur="4.2s" repeatCount="indefinite" />
    </circle>
    <!-- And more throughout the background -->
  </g>
  
  <!-- Shooting stars -->
  <g class="shooting-stars">
    <!-- First shooting star -->
    <line x1="700" y1="50" x2="600" y2="120" stroke="url(#shootingStarGradient)" stroke-width="2" opacity="0">
      <animate attributeName="opacity" values="0;1;0" dur="2s" begin="1s" repeatCount="indefinite" />
    </line>
    <!-- Second shooting star -->
    <line x1="200" y1="80" x2="300" y2="150" stroke="url(#shootingStarGradient)" stroke-width="2" opacity="0">
      <animate attributeName="opacity" values="0;1;0" dur="2s" begin="3s" repeatCount="indefinite" />
    </line>
    <!-- Third shooting star -->
    <line x1="500" y1="30" x2="400" y2="120" stroke="url(#shootingStarGradient)" stroke-width="2" opacity="0">
      <animate attributeName="opacity" values="0;1;0" dur="2s" begin="5s" repeatCount="indefinite" />
    </line>
  </g>
  
  <!-- Silhouette of Kim Dokja (simplified outline) -->
  <path d="M400,120 C370,120 350,160 350,190 C350,220 370,240 400,240 C430,240 450,220 450,190 C450,160 430,120 400,120 Z" fill="#000" />
  <!-- Simplified coat/jacket outline -->
  <path d="M370,190 C370,190 350,230 330,250 M430,190 C430,190 450,230 470,250" stroke="#333" stroke-width="2" fill="none" />
  
  <!-- Text elements -->
  <text x="400" y="80" font-family="Arial, sans-serif" font-size="24" text-anchor="middle" fill="white" filter="url(#glow)">
    Yun | 윤
    <animate attributeName="opacity" values="0.8;1;0.8" dur="4s" repeatCount="indefinite" />
  </text>
  
  <!-- ORV Quote in Korean - with self-drawing effect -->
  <text x="400" y="210" font-family="Arial, sans-serif" font-size="14" text-anchor="middle" fill="white">
    <tspan>회귀를 계속하다 보면, 언젠가 네놈을 만날 수도 있는 건가?</tspan>
  </text>
  
  <!-- Developer descriptor text -->
  <g>
    <text x="400" y="110" font-family="Arial, sans-serif" font-size="16" text-anchor="middle" fill="white" opacity="0.9">
      <tspan>Game Developer &amp; Fullstack Engineer</tspan>
    </text>
  </g>
</svg>
