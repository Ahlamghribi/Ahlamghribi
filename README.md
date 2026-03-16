<svg xmlns="http://www.w3.org/2000/svg" width="900" height="280" viewBox="0 0 900 280">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d0d12"/>
      <stop offset="100%" style="stop-color:#13001f"/>
    </linearGradient>
    <linearGradient id="line1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#9333ea;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#9333ea;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#9333ea;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="line2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#f59e0b;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#f59e0b;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#f59e0b;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="textgrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ffffff"/>
      <stop offset="60%" style="stop-color:#e9d5ff"/>
      <stop offset="100%" style="stop-color:#9333ea"/>
    </linearGradient>
    <radialGradient id="glow1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#9333ea;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#9333ea;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="glow2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#f59e0b;stop-opacity:0.08"/>
      <stop offset="100%" style="stop-color:#f59e0b;stop-opacity:0"/>
    </radialGradient>
    <filter id="blur1">
      <feGaussianBlur stdDeviation="18"/>
    </filter>
    <filter id="blur2">
      <feGaussianBlur stdDeviation="8"/>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="280" fill="url(#bg)"/>

  <!-- Grid lines -->
  <g opacity="0.06" stroke="#9333ea" stroke-width="0.5">
    <line x1="0" y1="56" x2="900" y2="56"/>
    <line x1="0" y1="112" x2="900" y2="112"/>
    <line x1="0" y1="168" x2="900" y2="168"/>
    <line x1="0" y1="224" x2="900" y2="224"/>
    <line x1="180" y1="0" x2="180" y2="280"/>
    <line x1="360" y1="0" x2="360" y2="280"/>
    <line x1="540" y1="0" x2="540" y2="280"/>
    <line x1="720" y1="0" x2="720" y2="280"/>
  </g>

  <!-- Glow blobs -->
  <ellipse cx="240" cy="140" rx="260" ry="160" fill="url(#glow1)" filter="url(#blur1)"/>
  <ellipse cx="700" cy="100" rx="180" ry="120" fill="url(#glow2)" filter="url(#blur1)"/>
  <ellipse cx="450" cy="220" rx="200" ry="80" fill="url(#glow1)" filter="url(#blur2)"/>

  <!-- Corner accents -->
  <path d="M0,0 L60,0 L0,60 Z" fill="#9333ea" opacity="0.12"/>
  <path d="M900,280 L840,280 L900,220 Z" fill="#9333ea" opacity="0.12"/>
  <path d="M900,0 L860,0 L900,40 Z" fill="#f59e0b" opacity="0.18"/>
  <path d="M0,280 L40,280 L0,240 Z" fill="#f59e0b" opacity="0.12"/>

  <!-- Top horizontal line -->
  <rect x="0" y="0" width="900" height="1.5" fill="url(#line1)" opacity="0.8"/>
  <!-- Bottom line -->
  <rect x="0" y="278" width="900" height="1.5" fill="url(#line1)" opacity="0.5"/>
  <!-- Gold accent line -->
  <rect x="0" y="2" width="900" height="0.8" fill="url(#line2)" opacity="0.6"/>

  <!-- Side vertical accents -->
  <rect x="0" y="0" width="1.5" height="280" fill="url(#line1)" opacity="0.4"/>
  <rect x="898.5" y="0" width="1.5" height="280" fill="url(#line1)" opacity="0.4"/>

  <!-- Dot matrix top-right -->
  <g opacity="0.15" fill="#9333ea">
    <circle cx="790" cy="30" r="1.5"/>
    <circle cx="810" cy="30" r="1.5"/>
    <circle cx="830" cy="30" r="1.5"/>
    <circle cx="850" cy="30" r="1.5"/>
    <circle cx="870" cy="30" r="1.5"/>
    <circle cx="790" cy="50" r="1.5"/>
    <circle cx="810" cy="50" r="1.5"/>
    <circle cx="830" cy="50" r="1.5"/>
    <circle cx="850" cy="50" r="1.5"/>
    <circle cx="870" cy="50" r="1.5"/>
    <circle cx="790" cy="70" r="1.5"/>
    <circle cx="810" cy="70" r="1.5"/>
    <circle cx="830" cy="70" r="1.5"/>
    <circle cx="850" cy="70" r="1.5"/>
    <circle cx="870" cy="70" r="1.5"/>
  </g>

  <!-- Dot matrix bottom-left -->
  <g opacity="0.12" fill="#f59e0b">
    <circle cx="30" cy="210" r="1.5"/>
    <circle cx="50" cy="210" r="1.5"/>
    <circle cx="70" cy="210" r="1.5"/>
    <circle cx="30" cy="230" r="1.5"/>
    <circle cx="50" cy="230" r="1.5"/>
    <circle cx="70" cy="230" r="1.5"/>
    <circle cx="30" cy="250" r="1.5"/>
    <circle cx="50" cy="250" r="1.5"/>
    <circle cx="70" cy="250" r="1.5"/>
  </g>

  <!-- Small geometric shapes -->
  <polygon points="820,180 832,160 844,180" fill="none" stroke="#9333ea" stroke-width="1" opacity="0.3"/>
  <polygon points="60,90 72,70 84,90" fill="none" stroke="#f59e0b" stroke-width="1" opacity="0.25"/>
  <rect x="840" y="200" width="14" height="14" fill="none" stroke="#9333ea" stroke-width="1" opacity="0.2" transform="rotate(20,847,207)"/>
  <circle cx="80" cy="160" r="8" fill="none" stroke="#9333ea" stroke-width="1" opacity="0.2"/>

  <!-- Tag top-left -->
  <rect x="28" y="28" width="130" height="22" rx="11" fill="#9333ea" opacity="0.12"/>
  <rect x="28" y="28" width="130" height="22" rx="11" fill="none" stroke="#9333ea" stroke-width="0.8" opacity="0.4"/>
  <circle cx="44" cy="39" r="3.5" fill="#22c55e" opacity="0.9"/>
  <text x="54" y="44" font-family="monospace" font-size="10" fill="#9333ea" opacity="0.9" font-weight="600">Available for work</text>

  <!-- Tag top-right -->
  <rect x="742" y="28" width="130" height="22" rx="11" fill="#f59e0b" opacity="0.08"/>
  <rect x="742" y="28" width="130" height="22" rx="11" fill="none" stroke="#f59e0b" stroke-width="0.8" opacity="0.3"/>
  <text x="775" y="44" font-family="monospace" font-size="10" fill="#f59e0b" opacity="0.8" font-weight="600">Algeria 🇩🇿 → World</text>

  <!-- Main name -->
  <text x="450" y="130" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="68" font-weight="800" fill="url(#textgrad)" letter-spacing="-2">Ahlam Ghribi</text>

  <!-- Subtitle -->
  <text x="450" y="168" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="15" font-weight="400" fill="#9ca3af" letter-spacing="2">Full-Stack Developer  ✦  Cybersecurity  ✦  UI/UX Engineer</text>

  <!-- Bottom tagline -->
  <text x="450" y="220" text-anchor="middle" font-family="monospace" font-size="11" fill="#6b21a8" opacity="0.9" letter-spacing="3">BUILDING WHAT MATTERS — SECURING WHAT EXISTS</text>

  <!-- Bottom gold line accent under name -->
  <rect x="330" y="178" width="240" height="1" fill="url(#line2)" opacity="0.6"/>

</svg>
