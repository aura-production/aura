# Aura
Aura Production — автоматизация смет и инженерных расчётов
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 400" width="400" height="400">
  <defs>
    <radialGradient id="auraGrad" cx="50%" cy="45%" r="55%">
      <stop offset="0%" stop-color="#8b5cf6" stop-opacity="1"/>
      <stop offset="50%" stop-color="#6366f1" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#1e1b4b" stop-opacity="0.1"/>
    </radialGradient>
    <linearGradient id="ringGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#a78bfa"/>
      <stop offset="100%" stop-color="#6366f1"/>
    </linearGradient>
  </defs>
  
  <!-- Фон -->
  <rect width="400" height="400" fill="#0f172a"/>
  
  <!-- Аура (внешний круг) -->
  <circle cx="200" cy="160" r="110" fill="none" stroke="url(#ringGrad)" stroke-width="3" opacity="0.9"/>
  <circle cx="200" cy="160" r="85" fill="none" stroke="url(#ringGrad)" stroke-width="1.5" opacity="0.5"/>
  
  <!-- Свечение -->
  <circle cx="200" cy="160" r="70" fill="url(#auraGrad)"/>
  
  <!-- Лучи (волна света) -->
  <g stroke="#c4b5fd" stroke-width="2" stroke-linecap="round" opacity="0.85">
    <line x1="200" y1="110" x2="200" y2="140"/>
    <line x1="200" y1="180" x2="200" y2="210"/>
    <line x1="150" y1="160" x2="180" y2="160"/>
    <line x1="220" y1="160" x2="250" y2="160"/>
    <line x1="165" y1="125" x2="185" y2="145"/>
    <line x1="215" y1="175" x2="235" y2="195"/>
    <line x1="235" y1="125" x2="215" y2="145"/>
    <line x1="185" y1="175" x2="165" y2="195"/>
  </g>
  
  <!-- Точка в центре (ядро) -->
  <circle cx="200" cy="160" r="8" fill="#e0e7ff"/>
  
  <!-- Название -->
  <text x="200" y="310" font-family="Arial, Helvetica, sans-serif" font-size="32" font-weight="700" fill="#e0e7ff" text-anchor="middle" letter-spacing="4">AURA</text>
  <text x="200" y="345" font-family="Arial, Helvetica, sans-serif" font-size="18" font-weight="400" fill="#a78bfa" text-anchor="middle" letter-spacing="8">PRODUCTION</text>
  
  <!-- Подпись -->
  <text x="200" y="380" font-family="Arial, Helvetica, sans-serif" font-size="10" fill="#6366f1" text-anchor="middle" letter-spacing="2">SERGIJUS INCORPORATED</text>
</svg>
