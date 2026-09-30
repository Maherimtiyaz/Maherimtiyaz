<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                    MAHERIMTIYAZ — README.md                              -->
<!--              Replace all YOUR_* placeholders with your info              -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ─────────────────────────────────────────────────────────────────────── -->
<!--  HERO — CINEMATIC WINTER CODING SCENE                                     -->
<!-- ─────────────────────────────────────────────────────────────────────── -->

<svg viewBox="0 0 900 500" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet" role="img" aria-label="A developer coding alone during a futuristic winter night — aurora in the sky, snow falling outside a warm workstation window, coffee steam rising, monitor glowing with code">
  <defs>
    <linearGradient id="skyGrad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#020617"/>
      <stop offset="40%" stop-color="#0B1020"/>
      <stop offset="100%" stop-color="#1e1b4b"/>
    </linearGradient>
    <linearGradient id="aurora1" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0"/>
      <stop offset="30%" stop-color="#22D3EE" stop-opacity="0.4"/>
      <stop offset="70%" stop-color="#6366F1" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#8B5CF6" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="aurora2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#8B5CF6" stop-opacity="0"/>
      <stop offset="40%" stop-color="#8B5CF6" stop-opacity="0.3"/>
      <stop offset="60%" stop-color="#F472B6" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#F472B6" stop-opacity="0"/>
    </linearGradient>
    <radialGradient id="screenLight" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="lampLight" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0%" stop-color="#F472B6" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#F472B6" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="roomGlow" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0%" stop-color="#6366F1" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#6366F1" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="steamGrad" cx="0.5" cy="1" r="0.5">
      <stop offset="0%" stop-color="#94A3B8" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#94A3B8" stop-opacity="0"/>
    </radialGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- SKY -->
  <rect width="900" height="500" fill="url(#skyGrad)"/>

  <!-- AURORA BOREALIS -->
  <g>
    <path fill="url(#aurora1)" opacity="0.5">
      <animate attributeName="d" values="M0 90 Q225 50 450 80 Q675 110 900 70 L900 0 L0 0 Z;M0 75 Q225 60 450 65 Q675 95 900 80 L900 0 L0 0 Z;M0 90 Q225 50 450 80 Q675 110 900 70 L900 0 L0 0 Z" dur="18s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0.8;0.5" dur="12s" repeatCount="indefinite"/>
    </path>
    <path fill="url(#aurora2)" opacity="0.4">
      <animate attributeName="d" values="M0 120 Q225 90 450 105 Q675 120 900 95 L900 0 L0 0 Z;M0 105 Q225 100 450 95 Q675 110 900 105 L900 0 L0 0 Z;M0 120 Q225 90 450 105 Q675 120 900 95 L900 0 L0 0 Z" dur="22s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.2;0.4" dur="15s" repeatCount="indefinite"/>
    </path>
  </g>

  <!-- STARS -->
  <g fill="#f8fafc">
    <circle cx="80" cy="40" r="1.2"><animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="180" cy="25" r="0.8"><animate attributeName="opacity" values="0.5;0.2;0.5" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="300" cy="55" r="1"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="3.5s" repeatCount="indefinite"/></circle>
    <circle cx="420" cy="30" r="1.2"><animate attributeName="opacity" values="0.6;0.3;0.6" dur="5s" repeatCount="indefinite"/></circle>
    <circle cx="550" cy="60" r="0.8"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="4.5s" repeatCount="indefinite"/></circle>
    <circle cx="680" cy="35" r="1"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.2s" repeatCount="indefinite"/></circle>
    <circle cx="800" cy="50" r="1.2"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="4.8s" repeatCount="indefinite"/></circle>
    <circle cx="120" cy="80" r="0.6"><animate attributeName="opacity" values="0.2;0.7;0.2" dur="6s" repeatCount="indefinite"/></circle>
    <circle cx="650" cy="85" r="0.6"><animate attributeName="opacity" values="0.3;0.9;0.3" dur="5.5s" repeatCount="indefinite"/></circle>
    <circle cx="870" cy="25" r="1"><animate attributeName="opacity" values="0.5;0.2;0.5" dur="3.8s" repeatCount="indefinite"/></circle>
  </g>

  <!-- SHOOTING STAR -->
  <g opacity="0">
    <line x1="0" y1="0" x2="60" y2="30" stroke="#f8fafc" stroke-width="2" stroke-linecap="round"/>
    <line x1="0" y1="0" x2="60" y2="30" stroke="#22D3EE" stroke-width="4" stroke-linecap="round" opacity="0.5" filter="url(#glow)"/>
    <animate attributeName="opacity" values="0;0;0;1;1;0;0" dur="12s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="translate" values="100 20;400 160" dur="12s" repeatCount="indefinite"/>
  </g>

  <!-- MOUNTAINS -->
  <path d="M0 360 L80 300 L160 340 L240 280 L320 350 L400 310 L480 360 L560 290 L640 350 L720 300 L800 340 L900 310 L900 500 L0 500 Z" fill="#050816" opacity="0.7"/>
  <path d="M0 400 L120 340 L240 390 L360 330 L480 400 L600 350 L720 400 L840 350 L900 380 L900 500 L0 500 Z" fill="#020617" opacity="0.9"/>

  <!-- CITY SILHOUETTE -->
  <g fill="#0B1020" opacity="0.4">
    <rect x="30" y="320" width="25" height="180"/>
    <rect x="65" y="300" width="18" height="200"/>
    <rect x="95" y="340" width="30" height="160"/>
    <rect x="140" y="310" width="22" height="190"/>
    <rect x="175" y="290" width="28" height="210"/>
    <rect x="215" y="330" width="20" height="170"/>
    <rect x="250" y="305" width="35" height="195"/>
    <rect x="300" y="320" width="18" height="180"/>
    <rect x="330" y="295" width="25" height="205"/>
    <rect x="370" y="335" width="30" height="165"/>
    <rect x="415" y="310" width="22" height="190"/>
    <rect x="450" y="290" width="28" height="210"/>
    <rect x="490" y="325" width="20" height="175"/>
    <rect x="525" y="300" width="35" height="200"/>
    <rect x="575" y="315" width="18" height="185"/>
    <rect x="605" y="295" width="25" height="205"/>
    <rect x="645" y="330" width="30" height="170"/>
    <rect x="690" y="310" width="22" height="190"/>
    <rect x="725" y="290" width="28" height="210"/>
    <rect x="765" y="325" width="20" height="175"/>
    <rect x="800" y="305" width="35" height="195"/>
    <rect x="850" y="320" width="18" height="180"/>
  </g>

  <!-- CITY WINDOWS -->
  <g fill="#f8fafc">
    <rect x="35" y="330" width="3" height="4" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="4s" repeatCount="indefinite"/></rect>
    <rect x="45" y="345" width="3" height="4" opacity="0.4"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="3.5s" repeatCount="indefinite"/></rect>
    <rect x="100" y="350" width="3" height="4" opacity="0.5"><animate attributeName="opacity" values="0.5;0.2;0.5" dur="5s" repeatCount="indefinite"/></rect>
    <rect x="145" y="320" width="3" height="4" opacity="0.7"><animate attributeName="opacity" values="0.7;0.3;0.7" dur="4.2s" repeatCount="indefinite"/></rect>
    <rect x="185" y="310" width="3" height="4" opacity="0.5"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="3.8s" repeatCount="indefinite"/></rect>
    <rect x="260" y="320" width="3" height="4" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="4.5s" repeatCount="indefinite"/></rect>
    <rect x="340" y="310" width="3" height="4" opacity="0.4"><animate attributeName="opacity" values="0.4;0.8;0.4" dur="3.2s" repeatCount="indefinite"/></rect>
    <rect x="425" y="325" width="3" height="4" opacity="0.7"><animate attributeName="opacity" values="0.7;0.2;0.7" dur="5.5s" repeatCount="indefinite"/></rect>
    <rect x="460" y="305" width="3" height="4" opacity="0.5"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="4s" repeatCount="indefinite"/></rect>
    <rect x="535" y="315" width="3" height="4" opacity="0.6"><animate attributeName="opacity" values="0.6;0.3;0.6" dur="3.6s" repeatCount="indefinite"/></rect>
    <rect x="615" y="310" width="3" height="4" opacity="0.4"><animate attributeName="opacity" values="0.4;0.7;0.4" dur="4.8s" repeatCount="indefinite"/></rect>
    <rect x="700" y="320" width="3" height="4" opacity="0.8"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="3.4s" repeatCount="indefinite"/></rect>
    <rect x="735" y="305" width="3" height="4" opacity="0.5"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="5.2s" repeatCount="indefinite"/></rect>
    <rect x="810" y="320" width="3" height="4" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="3.9s" repeatCount="indefinite"/></rect>
  </g>

  <!-- SNOW LAYER 1 (far, slow) -->
  <g fill="#f8fafc" opacity="0.3">
    <circle cx="40" cy="20" r="0.8"><animate attributeName="cy" values="20;500" dur="22s" repeatCount="indefinite"/></circle>
    <circle cx="140" cy="60" r="0.6"><animate attributeName="cy" values="60;500" dur="25s" repeatCount="indefinite"/></circle>
    <circle cx="250" cy="30" r="0.8"><animate attributeName="cy" values="30;500" dur="20s" repeatCount="indefinite"/></circle>
    <circle cx="360" cy="80" r="0.6"><animate attributeName="cy" values="80;500" dur="24s" repeatCount="indefinite"/></circle>
    <circle cx="480" cy="40" r="0.8"><animate attributeName="cy" values="40;500" dur="23s" repeatCount="indefinite"/></circle>
    <circle cx="590" cy="70" r="0.6"><animate attributeName="cy" values="70;500" dur="26s" repeatCount="indefinite"/></circle>
    <circle cx="700" cy="25" r="0.8"><animate attributeName="cy" values="25;500" dur="21s" repeatCount="indefinite"/></circle>
    <circle cx="820" cy="55" r="0.6"><animate attributeName="cy" values="55;500" dur="24s" repeatCount="indefinite"/></circle>
  </g>

  <!-- SNOW LAYER 2 (mid, medium) -->
  <g fill="#f8fafc" opacity="0.5">
    <circle cx="80" cy="10" r="1.2"><animate attributeName="cy" values="10;500" dur="16s" repeatCount="indefinite"/><animate attributeName="cx" values="80;90;80" dur="10s" repeatCount="indefinite"/></circle>
    <circle cx="200" cy="50" r="1"><animate attributeName="cy" values="50;500" dur="18s" repeatCount="indefinite"/><animate attributeName="cx" values="200;190;200" dur="12s" repeatCount="indefinite"/></circle>
    <circle cx="320" cy="20" r="1.2"><animate attributeName="cy" values="20;500" dur="15s" repeatCount="indefinite"/><animate attributeName="cx" values="320;330;320" dur="9s" repeatCount="indefinite"/></circle>
    <circle cx="440" cy="70" r="1"><animate attributeName="cy" values="70;500" dur="17s" repeatCount="indefinite"/><animate attributeName="cx" values="440;430;440" dur="11s" repeatCount="indefinite"/></circle>
    <circle cx="560" cy="35" r="1.2"><animate attributeName="cy" values="35;500" dur="19s" repeatCount="indefinite"/><animate attributeName="cx" values="560;570;560" dur="13s" repeatCount="indefinite"/></circle>
    <circle cx="680" cy="60" r="1"><animate attributeName="cy" values="60;500" dur="16s" repeatCount="indefinite"/><animate attributeName="cx" values="680;670;680" dur="10s" repeatCount="indefinite"/></circle>
    <circle cx="800" cy="15" r="1.2"><animate attributeName="cy" values="15;500" dur="18s" repeatCount="indefinite"/><animate attributeName="cx" values="800;810;800" dur="12s" repeatCount="indefinite"/></circle>
    <circle cx="860" cy="45" r="1"><animate attributeName="cy" values="45;500" dur="20s" repeatCount="indefinite"/><animate attributeName="cx" values="860;850;860" dur="14s" repeatCount="indefinite"/></circle>
  </g>

  <!-- SNOW LAYER 3 (near, fast, large) -->
  <g fill="#f8fafc" opacity="0.7">
    <circle cx="120" cy="30" r="1.8"><animate attributeName="cy" values="30;500" dur="11s" repeatCount="indefinite"/><animate attributeName="cx" values="120;130;120" dur="7s" repeatCount="indefinite"/></circle>
    <circle cx="280" cy="80" r="1.5"><animate attributeName="cy" values="80;500" dur="13s" repeatCount="indefinite"/><animate attributeName="cx" values="280;270;280" dur="8s" repeatCount="indefinite"/></circle>
    <circle cx="420" cy="10" r="1.8"><animate attributeName="cy" values="10;500" dur="10s" repeatCount="indefinite"/><animate attributeName="cx" values="420;430;420" dur="6s" repeatCount="indefinite"/></circle>
    <circle cx="580" cy="50" r="1.5"><animate attributeName="cy" values="50;500" dur="12s" repeatCount="indefinite"/><animate attributeName="cx" values="580;570;580" dur="9s" repeatCount="indefinite"/></circle>
    <circle cx="720" cy="20" r="1.8"><animate attributeName="cy" values="20;500" dur="14s" repeatCount="indefinite"/><animate attributeName="cx" values="720;730;720" dur="7s" repeatCount="indefinite"/></circle>
    <circle cx="850" cy="65" r="1.5"><animate attributeName="cy" values="65;500" dur="11s" repeatCount="indefinite"/><animate attributeName="cx" values="850;840;850" dur="8s" repeatCount="indefinite"/></circle>
  </g>

  <!-- ROOM GLOW -->
  <ellipse cx="550" cy="420" rx="250" ry="100" fill="url(#roomGlow)"/>

  <!-- CABIN WALL -->
  <rect x="350" y="280" width="400" height="200" rx="8" fill="#0f172a" opacity="0.8"/>
  <rect x="350" y="280" width="400" height="200" rx="8" fill="none" stroke="#1e293b" stroke-width="2"/>

  <!-- WINDOW -->
  <rect x="370" y="300" width="130" height="100" rx="4" fill="#020617" stroke="#1e293b" stroke-width="3"/>
  <line x1="435" y1="300" x2="435" y2="400" stroke="#1e293b" stroke-width="2"/>
  <line x1="370" y1="350" x2="500" y2="350" stroke="#1e293b" stroke-width="2"/>
  <circle cx="390" cy="320" r="1.5" fill="#f8fafc" opacity="0.4"><animate attributeName="cy" values="320;390" dur="8s" repeatCount="indefinite"/></circle>
  <circle cx="420" cy="330" r="1" fill="#f8fafc" opacity="0.3"><animate attributeName="cy" values="330;395" dur="10s" repeatCount="indefinite"/></circle>
  <circle cx="460" cy="315" r="1.2" fill="#f8fafc" opacity="0.35"><animate attributeName="cy" values="315;390" dur="9s" repeatCount="indefinite"/></circle>
  <path d="M372 302 Q378 310 372 318" stroke="#94A3B8" stroke-width="0.8" fill="none" opacity="0.3"/>
  <path d="M498 302 Q492 310 498 318" stroke="#94A3B8" stroke-width="0.8" fill="none" opacity="0.3"/>
  <path d="M372 398 Q378 390 372 382" stroke="#94A3B8" stroke-width="0.8" fill="none" opacity="0.3"/>

  <!-- DESK -->
  <rect x="350" y="410" width="400" height="6" rx="3" fill="#1e293b"/>
  <rect x="370" y="416" width="8" height="50" fill="#1e293b"/>
  <rect x="720" y="416" width="8" height="50" fill="#1e293b"/>

  <!-- MONITOR -->
  <rect x="540" y="320" width="140" height="90" rx="5" fill="#0f172a" stroke="#1e293b" stroke-width="2"/>
  <rect x="548" y="328" width="124" height="74" rx="3" fill="#020617"/>
  <rect x="548" y="328" width="124" height="74" rx="3" fill="#22D3EE" opacity="0"><animate attributeName="opacity" values="0;0.06;0" dur="4s" repeatCount="indefinite"/></rect>
  <g font-family="monospace" font-size="8" filter="url(#glow)">
    <text x="556" y="344" fill="#22D3EE" opacity="0">def build():<animate attributeName="opacity" values="0;0;1;1;1;0;0" dur="8s" repeatCount="indefinite"/></text>
    <text x="556" y="356" fill="#94A3B8" opacity="0">  return await<animate attributeName="opacity" values="0;0;0;1;1;1;0" dur="8s" repeatCount="indefinite"/></text>
    <text x="556" y="368" fill="#8B5CF6" opacity="0">  api.ship()<animate attributeName="opacity" values="0;0;0;0;1;1;1" dur="8s" repeatCount="indefinite"/></text>
    <text x="556" y="380" fill="#38BDF8" opacity="0"># late night<animate attributeName="opacity" values="0;0;0;0;0;1;1" dur="8s" repeatCount="indefinite"/></text>
    <text x="556" y="392" fill="#6366F1" opacity="0"># keep going<animate attributeName="opacity" values="0;0;0;0;0;0;1" dur="8s" repeatCount="indefinite"/></text>
  </g>
  <rect x="605" y="410" width="10" height="5" fill="#1e293b"/>
  <rect x="595" y="413" width="30" height="3" rx="1" fill="#1e293b"/>
  <ellipse cx="610" cy="410" rx="90" ry="20" fill="url(#screenLight)" opacity="0.5"/>

  <!-- CHARACTER -->
  <g>
    <rect x="490" y="350" width="55" height="80" rx="10" fill="#1e293b"/>
    <path d="M485 420 Q490 380 510 375 L520 375 Q540 380 545 420 Z" fill="#1e293b"/>
    <circle cx="515" cy="358" r="18" fill="#1e293b"/>
    <path d="M497 358 Q502 340 515 338 Q528 340 533 358" fill="#0f172a" stroke="#1e293b" stroke-width="1.5"/>
    <path d="M498 350 Q515 335 532 350" stroke="#334155" stroke-width="3" fill="none"/>
    <ellipse cx="498" cy="355" rx="4" ry="6" fill="#334155"/>
    <ellipse cx="532" cy="355" rx="4" ry="6" fill="#334155"/>
    <ellipse cx="498" cy="355" rx="4" ry="6" fill="#22D3EE" opacity="0"><animate attributeName="opacity" values="0;0.3;0" dur="3s" repeatCount="indefinite"/></ellipse>
    <ellipse cx="532" cy="355" rx="4" ry="6" fill="#22D3EE" opacity="0"><animate attributeName="opacity" values="0;0.3;0" dur="3s" repeatCount="indefinite"/></ellipse>
    <ellipse cx="515" cy="360" rx="8" ry="9" fill="#334155"/>
    <ellipse cx="515" cy="360" rx="8" ry="9" fill="#22D3EE" opacity="0.1"><animate attributeName="opacity" values="0.1;0.2;0.1" dur="4s" repeatCount="indefinite"/></ellipse>
    <ellipse cx="511" cy="358" rx="2" ry="2.5" fill="#94A3B8"><animate attributeName="ry" values="2.5;0.3;2.5" dur="5s" repeatCount="indefinite"/></ellipse>
    <ellipse cx="519" cy="358" rx="2" ry="2.5" fill="#94A3B8"><animate attributeName="ry" values="2.5;0.3;2.5" dur="5s" repeatCount="indefinite"/></ellipse>
    <path d="M510 372 L508 385" stroke="#334155" stroke-width="1" fill="none"/>
    <path d="M520 372 L522 385" stroke="#334155" stroke-width="1" fill="none"/>
    <path d="M500 390 Q490 400 485 405" stroke="#1e293b" stroke-width="7" fill="none" stroke-linecap="round">
      <animate attributeName="d" values="M500 390 Q490 400 485 405;M500 390 Q488 402 483 407;M500 390 Q490 400 485 405" dur="0.9s" repeatCount="indefinite"/>
    </path>
    <path d="M530 390 Q540 400 545 405" stroke="#1e293b" stroke-width="7" fill="none" stroke-linecap="round">
      <animate attributeName="d" values="M530 390 Q540 400 545 405;M530 390 Q542 402 547 407;M530 390 Q540 400 545 405" dur="0.8s" repeatCount="indefinite"/>
    </path>
    <path d="M500 420 L495 450" stroke="#1e293b" stroke-width="9" fill="none" stroke-linecap="round"/>
    <path d="M530 420 L535 450" stroke="#1e293b" stroke-width="9" fill="none" stroke-linecap="round"/>
  </g>

  <!-- KEYBOARD -->
  <rect x="520" y="405" width="60" height="6" rx="2" fill="#0f172a"/>
  <rect x="525" y="406" width="50" height="1" fill="#22D3EE" opacity="0.3"><animate attributeName="opacity" values="0.3;0.6;0.3" dur="2s" repeatCount="indefinite"/></rect>

  <!-- COFFEE MUG -->
  <rect x="680" y="395" width="20" height="18" rx="3" fill="#1e293b"/>
  <rect x="680" y="395" width="20" height="18" rx="3" fill="#0f172a" opacity="0.5"/>
  <path d="M700 400 Q708 400 708 405 Q708 410 700 410" stroke="#1e293b" stroke-width="2.5" fill="none"/>
  <ellipse cx="690" cy="388" rx="7" ry="10" fill="url(#steamGrad)"><animate attributeName="cy" values="388;370;388" dur="7s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.4;0;0.4" dur="7s" repeatCount="indefinite"/></ellipse>
  <ellipse cx="695" cy="385" rx="5" ry="8" fill="url(#steamGrad)"><animate attributeName="cy" values="385;365;385" dur="9s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.3;0;0.3" dur="9s" repeatCount="indefinite"/></ellipse>

  <!-- DESK LAMP -->
  <rect x="730" y="390" width="6" height="25" fill="#1e293b"/>
  <path d="M733 390 Q745 375 755 380 L760 385 L745 395 Z" fill="#1e293b"/>
  <circle cx="755" cy="382" r="4" fill="#F472B6" opacity="0.8"><animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/></circle>
  <circle cx="755" cy="382" r="15" fill="url(#lampLight)" opacity="0.5"/>

  <!-- AMBIENT PARTICLES -->
  <g>
    <circle cx="580" cy="300" r="1" fill="#6366F1" opacity="0.5"><animate attributeName="cy" values="300;280;300" dur="8s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.5;0;0.5" dur="8s" repeatCount="indefinite"/></circle>
    <circle cx="650" cy="310" r="1.2" fill="#8B5CF6" opacity="0.4"><animate attributeName="cy" values="310;290;310" dur="10s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.4;0;0.4" dur="10s" repeatCount="indefinite"/></circle>
    <circle cx="530" cy="295" r="0.8" fill="#22D3EE" opacity="0.6"><animate attributeName="cy" values="295;275;295" dur="9s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.6;0;0.6" dur="9s" repeatCount="indefinite"/></circle>
    <circle cx="700" cy="305" r="1" fill="#F472B6" opacity="0.3"><animate attributeName="cy" values="305;285;305" dur="11s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.3;0;0.3" dur="11s" repeatCount="indefinite"/></circle>
    <circle cx="620" cy="290" r="0.8" fill="#38BDF8" opacity="0.5"><animate attributeName="cy" values="290;270;290" dur="7s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.5;0;0.5" dur="7s" repeatCount="indefinite"/></circle>
  </g>

  <!-- CINEMATIC BARS -->
  <rect x="0" y="0" width="900" height="30" fill="#020617" opacity="0.6"/>
  <rect x="0" y="470" width="900" height="30" fill="#020617" opacity="0.6"/>
</svg>

<br/>

<!-- ─────────────────────────────────────────────────────────────────────── -->
<!--  IDENTITY                                                                -->
<!-- ─────────────────────────────────────────────────────────────────────── -->

# YOUR_NAME
### `BACKEND ENGINEER` · `PYTHON` · `FASTAPI` · `POSTGRESQL`

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3500&pause=1200&color=6366F1&center=true&vCenter=true&width=560&lines=Building+scalable+APIs+%26+real-time+systems;Multi-tenant+architecture+%7C+Auth+flows;AI+backends+%7C+RAG+pipelines+%7C+Voice+AI;Open+to+remote+backend+internships" alt="Typing SVG" />
</a>

<br/><br/>

<!-- ─────────────────────────────────────────────────────────────────────── -->
<!--  STATUS HUD                                                               -->
<!-- ─────────────────────────────────────────────────────────────────────── -->

<table>
  <tr>
    <td align="center"><code>◉ ONLINE</code></td>
    <td align="center"><code>⬢ BUILDING</code></td>
    <td align="center"><code>◆ OPEN TO WORK</code></td>
    <td align="center"><code>📍 JAIPUR, INDIA</code></td>
  </tr>
</table>

<br/>

<!-- ─────────────────────────────────────────────────────────────────────── -->
<!--  HERO BUTTONS                                                             -->
<!-- ─────────────────────────────────────────────────────────────────────── -->

<a href="https://github.com/Maherimtiyaz">
  <img src="https://img.shields.io/badge/GitHub-Maherimtiyaz-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0B1020" alt="GitHub" />
</a>
&nbsp;
<a href="YOUR_WEBSITE">
  <img src="https://img.shields.io/badge/Portfolio-YOUR__WEBSITE-6366F1?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0B1020" alt="Portfolio" />
</a>
&nbsp;
<a href="YOUR_LINKEDIN">
  <img src="https://img.shields.io/badge/LinkedIn-YOUR__LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B1020" alt="LinkedIn" />
</a>
&nbsp;
<a href="mailto:YOUR_EMAIL">
  <img src="https://img.shields.io/badge/Email-YOUR__EMAIL-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0B1020" alt="Email" />
</a>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  DIVIDER                                                                  -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">
  <svg width="300" height="2" viewBox="0 0 300 2" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="div1" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#6366F1" stop-opacity="0"/>
        <stop offset="50%" stop-color="#6366F1" stop-opacity="0.6"/>
        <stop offset="100%" stop-color="#6366F1" stop-opacity="0"/>
      </linearGradient>
    </defs>
    <rect width="300" height="2" rx="1" fill="url(#div1)"/>
  </svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  [ 01 ] — ABOUT                                                           -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## `[ 01 ]` — ABOUT

> I build backend systems that are fast, secure, and production-ready — not just "works on my machine."
>
> I enjoy the messy middle: multi-tenant data isolation, auth flows that don't crumble under load, real-time connections that stay alive, and the kind of architecture that holds up when traffic spikes at 2 AM.
>
> **What differentiates my approach:** I ship with CI/CD from day one, write tests before features, and treat infrastructure as part of the product — not an afterthought.

```yaml
YOUR_NAME:           "YOUR_NAME"
YOUR_USERNAME:       "Maherimtiyaz"
YOUR_LOCATION:       "Jaipur, India"
YOUR_ROLE:           "Backend Engineer"
YOUR_BIO:            "Building scalable APIs & real-time systems"
YOUR_CURRENT_FOCUS:  "LLM backends · voice AI · multi-tenant architecture"
OPEN_TO:             "Remote backend engineering internships"
```

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  [ 02 ] — WHAT I BUILD                                                    -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## `[ 02 ]` — WHAT I BUILD

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ API ARCHITECTURE</h3>
      <p>Production-grade REST APIs with proper layering, migrations, and CI pipelines.</p>
      <code>FastAPI · PostgreSQL · Alembic · Docker</code>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 AUTH SYSTEMS</h3>
      <p>Stateless JWT auth with bcrypt, RBAC, and OWASP-aligned validation.</p>
      <code>JWT · bcrypt · RBAC · pytest</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 REAL-TIME BACKENDS</h3>
      <p>WebSocket servers with multi-room support, JWT handshakes, and indexed queries.</p>
      <code>WebSockets · FastAPI · PostgreSQL</code>
    </td>
    <td width="50%" valign="top">
      <h3>🧠 AI BACKENDS</h3>
      <p>RAG pipelines, streaming LLM responses, prompt routing, and session state.</p>
      <code>FAISS · Celery · Redis · OpenAI</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏗️ MULTI-TENANT SYSTEMS</h3>
      <p>Org-isolated data, role-based access, conflict detection at the DB layer.</p>
      <code>PostgreSQL · FastAPI · Docker</code>
    </td>
    <td width="50%" valign="top">
      <h3>📦 PRODUCT ENGINEERING</h3>
      <p>From schema design to deployment — full ownership of the backend surface.</p>
      <code>Docker · GitHub Actions · Render</code>
    </td>
  </tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  DIVIDER                                                                  -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">
  <svg width="300" height="2" viewBox="0 0 300 2" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="div2" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#8B5CF6" stop-opacity="0"/>
        <stop offset="50%" stop-color="#8B5CF6" stop-opacity="0.6"/>
        <stop offset="100%" stop-color="#8B5CF6" stop-opacity="0"/>
      </linearGradient>
    </defs>
    <rect width="300" height="2" rx="1" fill="url(#div2)"/>
  </svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  [ 03 ] — TECH LOADOUT                                                    -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## `[ 03 ]` — TECH LOADOUT

<div align="center">

### LANGUAGES
<img src="https://skillicons.dev/icons?i=python,ts,js,bash&theme=dark" height="48" />

### BACKEND
<img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,mongodb,redis&theme=dark" height="48" />

### AI / ML
<img src="https://skillicons.dev/icons?i=openai,py,tensorflow&theme=dark" height="48" />
&nbsp;
<img src="https://img.shields.io/badge/LLMs-6366F1?style=flat-square&logo=openai&logoColor=white&labelColor=0B1020" />
<img src="https://img.shields.io/badge/RAG-8B5CF6?style=flat-square&logo=langchain&logoColor=white&labelColor=0B1020" />
<img src="https://img.shields.io/badge/FAISS-22D3EE?style=flat-square&logo=meta&logoColor=white&labelColor=0B1020" />
<img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white&labelColor=0B1020" />

### INFRASTRUCTURE
<img src="https://skillicons.dev/icons?i=docker,githubactions,linux,nginx&theme=dark" height="48" />

### TOOLS
<img src="https://skillicons.dev/icons?i=git,vscode,postman,figma&theme=dark" height="48" />

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  DIVIDER                                                                  -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">
  <svg width="300" height="2" viewBox="0 0 300 2" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="div3" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#22D3EE" stop-opacity="0"/>
        <stop offset="50%" stop-color="#22D3EE" stop-opacity="0.6"/>
        <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
      </linearGradient>
    </defs>
    <rect width="300" height="2" rx="1" fill="url(#div3)"/>
  </svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  [ 04 ] — SHIPPED PROJECTS                                                -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## `[ 04 ]` — SHIPPED PROJECTS

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 AI_Powered_Doc_API</h3>
      <p><b>Production-grade AI document platform.</b><br/>
      PDF uploads → semantic retrieval → conversational Q&A. Deployed on Render — real infra debugging included.</p>
      <p><code>Python · FastAPI · RAG · FAISS · Celery · Redis · Docker</code></p>
      <p>
        <img src="https://img.shields.io/badge/●_LIVE-22D3EE?style=flat-square&labelColor=0B1020" />
      </p>
      <a href="https://github.com/Maherimtiyaz/AI_Powered_Doc_API">GitHub →</a>
    </td>
    <td width="50%" valign="top">
      <h3>📋 Task-Manager-API</h3>
      <p><b>Flagship backend engineering project.</b><br/>
      Multi-tenant REST API with isolated org data, role-based access, and Alembic migrations. CI runs pytest on every push.</p>
      <p><code>Python · FastAPI · PostgreSQL · JWT · RBAC · Docker · GitHub Actions</code></p>
      <p>
        <img src="https://img.shields.io/badge/●_OPEN_SOURCE-8B5CF6?style=flat-square&labelColor=0B1020" />
      </p>
      <a href="https://github.com/Maherimtiyaz/Task-Manager-API">GitHub →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💬 Chat_Backend</h3>
      <p><b>Real-time messaging backend.</b><br/>
      WebSocket support with multi-room concurrent connections, JWT handshakes, and PostgreSQL persistence. Indexed FK queries — no sequential scans.</p>
      <p><code>Python · FastAPI · WebSockets · PostgreSQL · Docker</code></p>
      <p>
        <img src="https://img.shields.io/badge/●_LIVE-22D3EE?style=flat-square&labelColor=0B1020" />
      </p>
      <a href="https://github.com/Maherimtiyaz/Chat_Backend">GitHub →</a>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 Auth-service</h3>
      <p><b>Pluggable JWT auth module.</b><br/>
      Stateless authentication with bcrypt + RBAC. OWASP-aligned input validation. Designed as a pluggable module for microservice stacks.</p>
      <p><code>Python · FastAPI · JWT · bcrypt · pytest</code></p>
      <p>
        <img src="https://img.shields.io/badge/●_OPEN_SOURCE-8B5CF6?style=flat-square&labelColor=0B1020" />
      </p>
      <a href="https://github.com/Maherimtiyaz/Auth-service">GitHub →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 AI_ChatBot_Backend_API</h3>
      <p><b>LLM integration layer.</b><br/>
      Prompt routing, streaming responses, multi-turn conversation state. Prompt templates for hallucination reduction.</p>
      <p><code>Python · FastAPI · OpenAI · Anthropic</code></p>
      <p>
        <img src="https://img.shields.io/badge/●_EXPERIMENTAL-F472B6?style=flat-square&labelColor=0B1020" />
      </p>
      <a href="https://github.com/Maherimtiyaz/AI_ChatBot_Backend_API">GitHub →</a>
    </td>
    <td width="50%" valign="top">
      <h3>📅 College-appointment-system-API</h3>
      <p><b>Role-based scheduling API.</b><br/>
      REST API with conflict-detection logic at the database layer. Built with Node.js/Express alongside Python/FastAPI breadth.</p>
      <p><code>Node.js · Express · MongoDB · RBAC</code></p>
      <p>
        <img src="https://img.shields.io/badge/●_OPEN_SOURCE-8B5CF6?style=flat-square&labelColor=0B1020" />
      </p>
      <a href="https://github.com/Maherimtiyaz/College-appointment-system-API">GitHub →</a>
    </td>
  </tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  DIVIDER                                                                  -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">
  <svg width="300" height="2" viewBox="0 0 300 2" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="div4" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#F472B6" stop-opacity="0"/>
        <stop offset="50%" stop-color="#F472B6" stop-opacity="0.6"/>
        <stop offset="100%" stop-color="#F472B6" stop-opacity="0"/>
      </linearGradient>
    </defs>
    <rect width="300" height="2" rx="1" fill="url(#div4)"/>
  </svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  [ 05 ] — SYSTEM HUD                                                      -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## `[ 05 ]` — SYSTEM HUD

<div align="center">

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=Maherimtiyaz&show_icons=true&theme=transparent&bg_color=0B1020&title_color=6366F1&icon_color=8B5CF6&text_color=94A3B8&border_color=1e293b&hide_border=true&rank_icon=github" alt="GitHub Stats" height="165" />
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Maherimtiyaz&layout=compact&theme=transparent&bg_color=0B1020&title_color=6366F1&text_color=94A3B8&border_color=1e293b&hide_border=true" alt="Top Languages" height="165" />
    </td>
  </tr>
</table>

<br/>

<img src="https://streak-stats.demolab.com?user=Maherimtiyaz&theme=transparent&background=0B1020&ring=6366F1&fire=8B5CF6&currStreakLabel=94A3B8&sideLabels=94A3B8&dates=64748B&border=1e293b&hide_border=true" alt="GitHub Streak" width="520" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Maherimtiyaz&bg_color=0B1020&color=94A3B8&line=6366F1&point=8B5CF6&area=true&area_color=6366F1&hide_border=true&custom_title=Contribution%20Graph" alt="Contribution Activity Graph" width="900" />

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Maherimtiyaz&color=6366F1&style=flat-square&label=PROFILE+VIEWS" alt="Profile Views" />

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  DIVIDER                                                                  -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">
  <svg width="300" height="2" viewBox="0 0 300 2" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="div5" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#38BDF8" stop-opacity="0"/>
        <stop offset="50%" stop-color="#38BDF8" stop-opacity="0.6"/>
        <stop offset="100%" stop-color="#38BDF8" stop-opacity="0"/>
      </linearGradient>
    </defs>
    <rect width="300" height="2" rx="1" fill="url(#div5)"/>
  </svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--  [ 06 ] — CURRENT QUEST                                                   -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## `[ 06 ]` — CURRENT QUEST

<div align="center">


╔══════════════════════════════════════════════════════════════════════╗
║  PLAYER PROFILE                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  CLASS              BACKEND ENGINEER                                 ║
║  PRIMARY WEAPON     SYSTEM DESIGN                                    ║
║  SPECIAL ABILITY    TURNING COMPLEXITY INTO APIs                     ║
║  CURRENT QUEST      VOICE AI + MULTI-TENANT ARCHITECTURE             ║
║                                                                      ║
║  [██████████████████░░░░░░░░░░░░░░░░░]  45%                          ║
║                                                                      ║
║  LEARN → BUILD → BREAK → DEBUG → SHIP                                ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
