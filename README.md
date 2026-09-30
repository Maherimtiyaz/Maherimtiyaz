<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    MAHERIMTIYAZ — README.md                    -->
<!--          Replace all YOUR_* placeholders with your info        -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ───────────────────────────────────────────────────────────── -->
<!--  CINEMATIC OPENING — WINTER CODING SCENE (inline SVG)         -->
<!-- ───────────────────────────────────────────────────────────── -->

<svg width="100%" height="auto" viewBox="0 0 900 420" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="A developer coding alone during a futuristic winter night — snow falling outside a warm workstation window">
  <defs>
    <linearGradient id="sky" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#020617"/>
      <stop offset="60%" stop-color="#0B1020"/>
      <stop offset="100%" stop-color="#1e1b4b"/>
    </linearGradient>
    <linearGradient id="snowfall" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#f8fafc" stop-opacity="0"/>
      <stop offset="30%" stop-color="#f8fafc" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#f8fafc" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="roomGlow" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#6366F1" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#8B5CF6" stop-opacity="0.05"/>
    </linearGradient>
    <linearGradient id="screenGlow" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#22D3EE"/>
      <stop offset="100%" stop-color="#38BDF8"/>
    </linearGradient>
    <radialGradient id="monitorLight" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="coffeeSteam" cx="0.5" cy="1" r="0.5">
      <stop offset="0%" stop-color="#94A3B8" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#94A3B8" stop-opacity="0"/>
    </radialGradient>
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="textGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Sky -->
  <rect width="900" height="420" fill="url(#sky)"/>

  <!-- Distant city silhouette -->
  <g opacity="0.18">
    <rect x="0" y="280" width="900" height="140" fill="#020617"/>
    <rect x="40" y="240" width="30" height="180" fill="#0B1020"/>
    <rect x="90" y="210" width="20" height="210" fill="#0B1020"/>
    <rect x="130" y="255" width="40" height="165" fill="#050816"/>
    <rect x="190" y="230" width="25" height="190" fill="#0B1020"/>
    <rect x="240" y="270" width="35" height="150" fill="#050816"/>
    <rect x="300" y="200" width="22" height="220" fill="#0B1020"/>
    <rect x="340" y="260" width="45" height="160" fill="#050816"/>
    <rect x="410" y="220" width="28" height="200" fill="#0B1020"/>
    <rect x="460" y="250" width="38" height="170" fill="#050816"/>
    <rect x="520" y="235" width="24" height="185" fill="#0B1020"/>
    <rect x="570" y="265" width="42" height="155" fill="#050816"/>
    <rect x="630" y="210" width="20" height="210" fill="#0B1020"/>
    <rect x="670" y="245" width="36" height="175" fill="#050816"/>
    <rect x="730" y="225" width="26" height="195" fill="#0B1020"/>
    <rect x="780" y="255" width="40" height="165" fill="#050816"/>
    <rect x="840" y="240" width="30" height="180" fill="#0B1020"/>
  </g>

  <!-- Distant window lights -->
  <g opacity="0.4">
    <circle cx="55" cy="255" r="1.5" fill="#f8fafc">
      <animate attributeName="opacity" values="0.4;0.8;0.4" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="100" cy="230" r="1.5" fill="#f8fafc">
      <animate attributeName="opacity" values="0.6;0.3;0.6" dur="3.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="150" cy="270" r="1" fill="#f8fafc">
      <animate attributeName="opacity" values="0.3;0.7;0.3" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="310" cy="220" r="1.5" fill="#f8fafc">
      <animate attributeName="opacity" values="0.5;0.9;0.5" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="470" cy="265" r="1" fill="#f8fafc">
      <animate attributeName="opacity" values="0.4;0.8;0.4" dur="4.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="640" cy="225" r="1.5" fill="#f8fafc">
      <animate attributeName="opacity" values="0.7;0.3;0.7" dur="3.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="790" cy="270" r="1" fill="#f8fafc">
      <animate attributeName="opacity" values="0.3;0.6;0.3" dur="4.2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Mountain silhouettes -->
  <path d="M0 320 L80 260 L160 300 L240 240 L320 310 L400 270 L480 320 L560 250 L640 300 L720 260 L800 310 L900 280 L900 420 L0 420 Z" fill="#050816" opacity="0.6"/>

  <!-- Snow particles -->
  <g>
    <circle cx="30" cy="40" r="1.5" fill="#f8fafc" opacity="0.7">
      <animate attributeName="cy" values="40;400" dur="12s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="30;45;30" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0.2;0.7" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="120" cy="80" r="1" fill="#f8fafc" opacity="0.5">
      <animate attributeName="cy" values="80;420" dur="15s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="120;110;120" dur="10s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0.1;0.5" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="230" cy="20" r="1.5" fill="#f8fafc" opacity="0.6">
      <animate attributeName="cy" values="20;410" dur="18s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="230;245;230" dur="12s" repeatCount="indefinite"/>
    </circle>
    <circle cx="350" cy="60" r="1" fill="#f8fafc" opacity="0.8">
      <animate attributeName="cy" values="60;430" dur="14s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="350;335;350" dur="9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="470" cy="30" r="1.5" fill="#f8fafc" opacity="0.4">
      <animate attributeName="cy" values="30;415" dur="16s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="470;485;470" dur="11s" repeatCount="indefinite"/>
    </circle>
    <circle cx="580" cy="90" r="1" fill="#f8fafc" opacity="0.6">
      <animate attributeName="cy" values="90;425" dur="13s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="580;565;580" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="690" cy="50" r="1.5" fill="#f8fafc" opacity="0.5">
      <animate attributeName="cy" values="50;420" dur="17s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="690;705;690" dur="13s" repeatCount="indefinite"/>
    </circle>
    <circle cx="810" cy="70" r="1" fill="#f8fafc" opacity="0.7">
      <animate attributeName="cy" values="70;430" dur="15s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="810;795;810" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="870" cy="110" r="1.5" fill="#f8fafc" opacity="0.5">
      <animate attributeName="cy" values="110;410" dur="19s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="870;885;870" dur="14s" repeatCount="indefinite"/>
    </circle>
    <!-- Extra slow flakes -->
    <circle cx="60" cy="150" r="1" fill="#f8fafc" opacity="0.3">
      <animate attributeName="cy" values="150;400" dur="22s" repeatCount="indefinite"/>
    </circle>
    <circle cx="200" cy="180" r="1.2" fill="#f8fafc" opacity="0.35">
      <animate attributeName="cy" values="180;410" dur="20s" repeatCount="indefinite"/>
    </circle>
    <circle cx="520" cy="160" r="1" fill="#f8fafc" opacity="0.4">
      <animate attributeName="cy" values="160;420" dur="21s" repeatCount="indefinite"/>
    </circle>
    <circle cx="750" cy="140" r="1.2" fill="#f8fafc" opacity="0.3">
      <animate attributeName="cy" values="140;415" dur="23s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Warm room / workstation area -->
  <rect x="250" y="240" width="400" height="180" rx="6" fill="url(#roomGlow)" opacity="0.8"/>

  <!-- Window frame -->
  <rect x="270" y="250" width="140" height="110" rx="3" fill="none" stroke="#1e293b" stroke-width="3"/>
  <line x1="340" y1="250" x2="340" y2="360" stroke="#1e293b" stroke-width="1.5"/>
  <line x1="270" y1="305" x2="410" y2="305" stroke="#1e293b" stroke-width="1.5"/>

  <!-- Snow visible through window -->
  <rect x="272" y="252" width="136" height="106" fill="#0B1020" opacity="0.3"/>
  <circle cx="300" cy="280" r="2" fill="#f8fafc" opacity="0.5">
    <animate attributeName="cy" values="280;350" dur="8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="350" cy="290" r="1.5" fill="#f8fafc" opacity="0.4">
    <animate attributeName="cy" values="290;355" dur="10s" repeatCount="indefinite"/>
  </circle>
  <circle cx="380" cy="270" r="1.8" fill="#f8fafc" opacity="0.45">
    <animate attributeName="cy" values="270;350" dur="9s" repeatCount="indefinite"/>
  </circle>

  <!-- Desk -->
  <rect x="250" y="360" width="400" height="8" rx="2" fill="#1e293b"/>
  <rect x="270" y="368" width="8" height="40" fill="#1e293b"/>
  <rect x="630" y="368" width="8" height="40" fill="#1e293b"/>

  <!-- Monitor -->
  <rect x="440" y="270" width="130" height="85" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="2"/>
  <rect x="448" y="278" width="114" height="69" rx="2" fill="#020617"/>
  <!-- Code on screen -->
  <g filter="url(#textGlow)">
    <text x="456" y="294" font-family="monospace" font-size="8" fill="#22D3EE" opacity="0.9">def build():</text>
    <text x="456" y="306" font-family="monospace" font-size="8" fill="#94A3B8" opacity="0.7">  return await</text>
    <text x="456" y="318" font-family="monospace" font-size="8" fill="#8B5CF6" opacity="0.8">  api.ship()</text>
    <text x="456" y="330" font-family="monospace" font-size="8" fill="#38BDF8" opacity="0.6"># late night</text>
    <text x="456" y="342" font-family="monospace" font-size="8" fill="#6366F1" opacity="0.5"># keep going</text>
  </g>
  <!-- Screen glow pulse -->
  <rect x="448" y="278" width="114" height="69" rx="2" fill="#22D3EE" opacity="0">
    <animate attributeName="opacity" values="0;0.08;0" dur="3s" repeatCount="indefinite"/>
  </rect>
  <!-- Monitor light on desk -->
  <ellipse cx="505" cy="360" rx="80" ry="15" fill="url(#monitorLight)" opacity="0.5"/>

  <!-- Monitor stand -->
  <rect x="498" y="355" width="14" height="5" fill="#1e293b"/>
  <rect x="490" y="358" width="30" height="3" rx="1" fill="#1e293b"/>

  <!-- Developer character (silhouette) -->
  <g>
    <!-- Chair back -->
    <rect x="400" y="300" width="50" height="70" rx="8" fill="#1e293b"/>
    <!-- Body -->
    <path d="M395 370 Q400 330 420 325 L430 325 Q445 330 450 370 Z" fill="#1e293b"/>
    <!-- Head -->
    <circle cx="422" cy="310" r="16" fill="#1e293b"/>
    <!-- Hoodie hood -->
    <path d="M406 310 Q410 294 422 292 Q434 294 438 310" fill="#0f172a" stroke="#1e293b" stroke-width="1"/>
    <!-- Face (warm monitor light) -->
    <ellipse cx="422" cy="312" rx="7" ry="8" fill="#334155"/>
    <!-- Eyes (subtle blink) -->
    <ellipse cx="418" cy="310" rx="2" ry="2.5" fill="#94A3B8">
      <animate attributeName="ry" values="2.5;0.3;2.5" dur="5s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="426" cy="310" rx="2" ry="2.5" fill="#94A3B8">
      <animate attributeName="ry" values="2.5;0.3;2.5" dur="5s" repeatCount="indefinite"/>
    </ellipse>
    <!-- Arms typing -->
    <path d="M435 340 Q450 348 455 355" stroke="#1e293b" stroke-width="6" fill="none" stroke-linecap="round">
      <animate attributeName="d" values="M435 340 Q450 348 455 355;M435 340 Q450 350 455 357;M435 340 Q450 348 455 355" dur="0.8s" repeatCount="indefinite"/>
    </path>
    <path d="M410 342 Q400 350 395 355" stroke="#1e293b" stroke-width="6" fill="none" stroke-linecap="round">
      <animate attributeName="d" values="M410 342 Q400 350 395 355;M410 342 Q398 352 393 357;M410 342 Q400 350 395 355" dur="0.9s" repeatCount="indefinite"/>
    </path>
    <!-- Legs -->
    <path d="M410 370 L405 400" stroke="#1e293b" stroke-width="8" fill="none" stroke-linecap="round"/>
    <path d="M435 370 L440 400" stroke="#1e293b" stroke-width="8" fill="none" stroke-linecap="round"/>
  </g>

  <!-- Coffee mug -->
  <rect x="585" y="345" width="18" height="18" rx="2" fill="#1e293b"/>
  <rect x="585" y="345" width="18" height="18" rx="2" fill="#0f172a" opacity="0.5"/>
  <path d="M603 350 Q610 350 610 355 Q610 360 603 360" stroke="#1e293b" stroke-width="2" fill="none"/>
  <!-- Coffee steam -->
  <ellipse cx="594" cy="340" rx="6" ry="8" fill="url(#coffeeSteam)">
    <animate attributeName="cy" values="340;325;340" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="6s" repeatCount="indefinite"/>
  </ellipse>

  <!-- Ambient particles -->
  <circle cx="500" cy="240" r="1" fill="#6366F1" opacity="0.4">
    <animate attributeName="cy" values="240;220;240" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0;0.4" dur="7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="550" cy="250" r="1.2" fill="#8B5CF6" opacity="0.3">
    <animate attributeName="cy" values="250;230;250" dur="9s" repeatCount="indefinite"/>
  </circle>
  <circle cx="460" cy="245" r="0.8" fill="#22D3EE" opacity="0.5">
    <animate attributeName="cy" values="245;225;245" dur="8s" repeatCount="indefinite"/>
  </circle>

  <!-- Frost on window edges -->
  <path d="M272 252 Q275 260 272 268" stroke="#94A3B8" stroke-width="1" fill="none" opacity="0.3"/>
  <path d="M408 252 Q405 260 408 268" stroke="#94A3B8" stroke-width="1" fill="none" opacity="0.3"/>
  <path d="M272 360 Q275 352 272 344" stroke="#94A3B8" stroke-width="1" fill="none" opacity="0.3"/>
</svg>

<br/>

<!-- ───────────────────────────────────────────────────────────── -->
<!--  NAME + TITLE                                                   -->
<!-- ───────────────────────────────────────────────────────────── -->

# MAHEK FATIMA
### `BACKEND ENGINEER` · `PYTHON` · `FASTAPI` · `POSTGRESQL`

<br/>

<!-- ───────────────────────────────────────────────────────────── -->
<!--  TYPING TAGLINE                                                 -->
<!-- ───────────────────────────────────────────────────────────── -->

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3500&pause=1200&color=6366F1&center=true&vCenter=true&width=520&lines=Building+scalable+APIs+%26+real-time+systems;Open+to+remote+backend+internships;Python+%7C+FastAPI+%7C+PostgreSQL+%7C+Docker" alt="Typing SVG" />
</a>

<br/><br/>

<!-- ───────────────────────────────────────────────────────────── -->
<!--  STATUS + LOCATION                                              -->
<!-- ───────────────────────────────────────────────────────────── -->

<p>
  <code>◉ OPEN TO OPPORTUNITIES</code> &nbsp;&nbsp;·&nbsp;&nbsp;
  <code>📍 Jaipur, India</code>
</p>

<br/>

<!-- ───────────────────────────────────────────────────────────── -->
<!--  HERO BUTTONS                                                   -->
<!-- ───────────────────────────────────────────────────────────── -->

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

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--  ABOUT                                                          -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## `[ 01 ]` — ABOUT

> I build backend systems that are fast, secure, and production-ready — not just "works on my machine."
>
> I enjoy the messy middle: multi-tenant data isolation, auth flows that don't crumble under load, real-time connections that stay alive, and the kind of architecture that holds up when traffic spikes at 2 AM.
>
> **What differentiates my approach:** I ship with CI/CD from day one, write tests before features, and treat infrastructure as part of the product — not an afterthought.

```yaml
YOUR_NAME:        "Mahek Fatima"
YOUR_USERNAME:    "Maherimtiyaz"
YOUR_LOCATION:    "Jaipur, India"
YOUR_ROLE:        "Backend Engineer"
YOUR_BIO:         "Building scalable APIs & real-time systems"
YOUR_CURRENT_FOCUS: "LLM backends · voice AI · multi-tenant architecture"
OPEN_TO:          "Remote backend engineering internships"
