<div align="center">

<svg width="100%" height="320" viewBox="0 0 1000 320" xmlns="http://www.w3.org/2000/svg">

  <defs>

    <!-- Animated Gradient Background -->
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#03140E">
        <animate attributeName="stop-color" values="#03140E;#052b05;#03140E" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#000000">
        <animate attributeName="stop-color" values="#000000;#001a12;#000000" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Haki Glow -->
    <radialGradient id="hakiGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#00FF7F" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#00FF7F" stop-opacity="0"/>
    </radialGradient>

  </defs>

  <!-- Background -->
  <rect width="1000" height="320" fill="url(#bgGradient)" />

  <!-- Moving Light Sweep -->
  <rect x="-300" y="0" width="300" height="320" fill="#00FF7F" opacity="0.03">
    <animate attributeName="x" values="-300;1200" dur="10s" repeatCount="indefinite"/>
  </rect>

  <!-- Floating Particles -->
  <circle cx="100" cy="80" r="2" fill="#00FF7F">
    <animate attributeName="cx" values="100;900" dur="12s" repeatCount="indefinite"/>
  </circle>

  <circle cx="300" cy="250" r="2" fill="#00FF7F">
    <animate attributeName="cy" values="250;100;250" dur="9s" repeatCount="indefinite"/>
  </circle>

  <circle cx="700" cy="120" r="2" fill="#00FF7F">
    <animate attributeName="cx" values="700;200;700" dur="11s" repeatCount="indefinite"/>
  </circle>

  <!-- Haki Pulse -->
  <circle cx="500" cy="140" r="90" fill="url(#hakiGlow)">
    <animate attributeName="r" values="80;115;80" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- Name Glow Shadow -->
  <text x="50%" y="150"
        text-anchor="middle"
        fill="#00FF7F"
        font-family="monospace"
        font-size="60"
        letter-spacing="10"
        opacity="0.15">
    ADARSH
  </text>

  <!-- Main Name -->
  <text x="50%" y="150"
        text-anchor="middle"
        fill="#00FF7F"
        font-family="monospace"
        font-size="60"
        letter-spacing="10">
    ADARSH
  </text>

  <!-- Dual Sword Slash -->
  <line x1="250" y1="120" x2="750" y2="180"
        stroke="#00FF7F"
        stroke-width="3"
        opacity="0">
    <animate attributeName="opacity"
             values="0;1;0"
             dur="2s"
             repeatCount="indefinite"/>
  </line>

  <line x1="750" y1="120" x2="250" y2="180"
        stroke="#00FF7F"
        stroke-width="2"
        opacity="0">
    <animate attributeName="opacity"
             values="0;1;0"
             dur="2s"
             begin="1s"
             repeatCount="indefinite"/>
  </line>

  <!-- Tagline -->
  <text x="50%" y="210"
        text-anchor="middle"
        fill="#9EF5CF"
        font-family="monospace"
        font-size="20"
        letter-spacing="3">
    Code • Linux • AI
  </text>

  <!-- Animated Divider -->
  <line x1="200" y1="250" x2="800" y2="250"
        stroke="#00FF7F"
        stroke-width="1">
    <animate attributeName="opacity"
             values="0.3;1;0.3"
             dur="3s"
             repeatCount="indefinite"/>
  </line>

</svg>

</div>
