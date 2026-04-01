<!-- ═══════════════════════════════════════════════════════════════
     ANKUSH SANYAL — @Jsher7
     Theme: Golden Hour · Elegant Dark · Charcoal + Amber/Gold
     Glassmorphism · Cinematic Photo Banner · Self-updating
═══════════════════════════════════════════════════════════════ -->


<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║     BLOCK 1 — CINEMATIC PHOTO BANNER     ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<div align="center">

<svg width="900" height="380" viewBox="0 0 900 380" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <!-- Clip the image to rounded rect -->
    <clipPath id="bannerClip">
      <rect width="896" height="376" x="2" y="2" rx="18"/>
    </clipPath>
    <!-- Dark gradient overlay so text is readable over photo -->
    <linearGradient id="overlay" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0a0500;stop-opacity:0.92"/>
      <stop offset="45%" style="stop-color:#0a0500;stop-opacity:0.75"/>
      <stop offset="100%" style="stop-color:#0a0500;stop-opacity:0.20"/>
    </linearGradient>
    <!-- Amber glow border gradient -->
    <linearGradient id="bannerBorder" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#f59e0b;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#d97706;stop-opacity:0.5"/>
      <stop offset="100%" style="stop-color:#f59e0b;stop-opacity:1"/>
    </linearGradient>
    <filter id="bannerGlow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="textGlow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="subtleGlow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Outer glow border -->
  <rect x="1" y="1" width="898" height="378" rx="18" fill="none"
        stroke="url(#bannerBorder)" stroke-width="1.5" filter="url(#bannerGlow)"/>

  <!-- Photo background -->
  <image href="https://raw.githubusercontent.com/Jsher7/Jsher7/main/banner.jpg"
         x="2" y="2" width="896" height="376"
         preserveAspectRatio="xMidYMid slice"
         clip-path="url(#bannerClip)"/>

  <!-- Dark overlay (left-heavy so text pops) -->
  <rect x="2" y="2" width="896" height="376" rx="18" fill="url(#overlay)" clip-path="url(#bannerClip)"/>

  <!-- Top amber accent line -->
  <rect x="2" y="2" width="896" height="3" rx="2" fill="url(#bannerBorder)"/>

  <!-- Location pill -->
  <rect x="48" y="46" width="188" height="24" rx="12"
        fill="#f59e0b" fill-opacity="0.18" stroke="#f59e0b" stroke-opacity="0.5" stroke-width="1"/>
  <text x="58" y="63" font-family="monospace" font-size="11" fill="#fbbf24" letter-spacing="1">📍 Kolkata, West Bengal, India</text>

  <!-- Main name -->
  <text x="48" y="140" font-family="Georgia, serif" font-size="58" font-weight="bold"
        fill="#fbbf24" filter="url(#textGlow)" letter-spacing="-1">Ankush Sanyal</text>

  <!-- Tagline -->
  <text x="50" y="176" font-family="monospace" font-size="20" font-weight="bold"
        fill="#f59e0b" filter="url(#subtleGlow)" letter-spacing="3">Code.  Capture.  Create.</text>

  <!-- Thin amber divider -->
  <line x1="48" y1="196" x2="440" y2="196" stroke="#f59e0b" stroke-opacity="0.4" stroke-width="1"/>

  <!-- Role pills row 1 -->
  <rect x="48" y="212" width="186" height="26" rx="13" fill="#f59e0b" fill-opacity="0.15" stroke="#f59e0b" stroke-opacity="0.35" stroke-width="1"/>
  <text x="141" y="230" font-family="monospace" font-size="11" fill="#fbbf24" text-anchor="middle">⚡ Full-Stack Developer</text>

  <rect x="244" y="212" width="210" height="26" rx="13" fill="#f59e0b" fill-opacity="0.15" stroke="#f59e0b" stroke-opacity="0.35" stroke-width="1"/>
  <text x="349" y="230" font-family="monospace" font-size="11" fill="#fbbf24" text-anchor="middle">📸 Photographer &amp; Cinematographer</text>

  <!-- Role pills row 2 -->
  <rect x="48" y="248" width="224" height="26" rx="13" fill="#f59e0b" fill-opacity="0.15" stroke="#f59e0b" stroke-opacity="0.35" stroke-width="1"/>
  <text x="160" y="266" font-family="monospace" font-size="11" fill="#fbbf24" text-anchor="middle">🎬 Video Editor · DaVinci · CapCut</text>

  <rect x="282" y="248" width="172" height="26" rx="13" fill="#f59e0b" fill-opacity="0.15" stroke="#f59e0b" stroke-opacity="0.35" stroke-width="1"/>
  <text x="368" y="266" font-family="monospace" font-size="11" fill="#fbbf24" text-anchor="middle">🤖 AI &amp; Web3 Builder</text>

  <!-- Fun fact strip at bottom -->
  <rect x="2" y="330" width="896" height="46" rx="0" fill="#0a0500" fill-opacity="0.82"/>
  <rect x="2" y="373" width="896" height="5" rx="2" fill="url(#bannerBorder)"/>
  <text x="450" y="349" font-family="monospace" font-size="11"
        fill="#d97706" text-anchor="middle" letter-spacing="1">🃏  Jack of all trades, master of none — but oftentimes better than a master of one</text>
  <text x="450" y="366" font-family="monospace" font-size="11"
        fill="#92400e" text-anchor="middle">🎧  3am lo-fi sessions  →  golden hour reels 🌅  →  ships before breakfast ☕</text>
</svg>

</div>

<br/>

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║       SOCIAL BADGES                      ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ankush%20Sanyal-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117)](https://www.linkedin.com/in/ankush-sanyal-30b764360)
[![Instagram](https://img.shields.io/badge/Instagram-@_ssup_ankush-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117)](https://www.instagram.com/_ssup_ankush)
[![Twitter/X](https://img.shields.io/badge/Twitter%2FX-@jungleesher7-1DA1F2?style=for-the-badge&logo=x&logoColor=white&labelColor=0d1117)](https://x.com/jungleesher7)
[![Email](https://img.shields.io/badge/Email-jungleesher7@gmail.com-f59e0b?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117)](mailto:jungleesher7@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-jungleefts-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=0d1117)](https://discord.com/users/jungleefts)

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=Jsher7&style=for-the-badge&color=f59e0b&label=PROFILE+VIEWS&base=1337)](https://github.com/Jsher7)
[![GitHub followers](https://img.shields.io/github/followers/Jsher7?style=for-the-badge&color=f59e0b&labelColor=0d1117&logo=github)](https://github.com/Jsher7?tab=followers)

</div>

<br/>

---

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║     BLOCK 2 — PROFILE SUMMARY CARDS      ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<h2 align="center">📋 &nbsp; Profile Summary</h2>

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Jsher7&theme=github_dark" width="100%"/>

<br/>

<table border="0" cellpadding="4" cellspacing="0">
  <tr>
    <td>
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Jsher7&theme=github_dark"/>
    </td>
    <td>
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Jsher7&theme=github_dark"/>
    </td>
    <td>
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Jsher7&theme=github_dark"/>
    </td>
    <td>
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Jsher7&theme=github_dark&utcOffset=5.5"/>
    </td>
  </tr>
</table>

</div>

<br/>

---

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║     BLOCK 3 — GLASSMORPHISM STATS        ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<h2 align="center">📊 &nbsp; Chronicle Stats</h2>

<div align="center">

<table border="0" cellpadding="6" cellspacing="0">
  <tr>
    <td align="center">
      <img height="175" src="https://github-readme-stats.vercel.app/api?username=Jsher7&show_icons=true&theme=dark&bg_color=0d1117&title_color=f59e0b&icon_color=d97706&text_color=e5c687&border_color=2d2d1a&border_radius=12&include_all_commits=true&count_private=true" />
    </td>
    <td align="center">
      <img height="175" src="https://github-readme-streak-stats.herokuapp.com?user=Jsher7&theme=dark&background=0d1117&border=2d2d1a&ring=f59e0b&fire=d97706&currStreakNum=e5c687&sideNums=e5c687&currStreakLabel=f59e0b&sideLabels=a38850&dates=6b6040&border_radius=12" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jsher7&layout=donut&theme=dark&bg_color=0d1117&title_color=f59e0b&text_color=e5c687&border_color=2d2d1a&border_radius=12&langs_count=8&hide=jupyter%20notebook" />
    </td>
    <td align="center">
      <img height="175" src="https://github-readme-activity-graph.vercel.app/graph?username=Jsher7&bg_color=0d1117&color=f59e0b&line=d97706&point=fbbf24&area=true&area_color=2d1f00&hide_border=false&border_color=2d2d1a&radius=12&custom_title=Contribution+Activity" />
    </td>
  </tr>
</table>

</div>

<br/>

---

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║     BLOCK 4 — SKILL ARSENAL              ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<h2 align="center">⚔️ &nbsp; Skill Arsenal</h2>

<div align="center">

<table border="0" cellpadding="10" cellspacing="0">
<tr>
<td align="center" valign="top">

**◈ Languages ◈**<br/>
<img src="https://skillicons.dev/icons?i=ts,js,py,java,c,bash,html,css&theme=dark&perline=4" />

</td>
<td align="center" valign="top">

**◈ Frontend & 3D ◈**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,vue,angular,threejs,tailwind,redux,vite&theme=dark&perline=4" />

</td>
<td align="center" valign="top">

**◈ Backend ◈**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,django,flask,spring,nginx,docker&theme=dark&perline=4" />

</td>
</tr>
<tr>
<td align="center" valign="top">

**◈ Mobile ◈**<br/>
<img src="https://skillicons.dev/icons?i=flutter,react,electron&theme=dark&perline=4" />

</td>
<td align="center" valign="top">

**◈ Databases & Cloud ◈**<br/>
<img src="https://skillicons.dev/icons?i=mongodb,redis,supabase,postgres,vercel,netlify,github,git&theme=dark&perline=4" />

</td>
<td align="center" valign="top">

**◈ AI/ML & Design ◈**<br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,figma,ps&theme=dark&perline=4" />

</td>
</tr>
</table>

</div>

<br/>

---

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║     BLOCK 5 — ACTIVE QUEST               ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<h2 align="center">🗺️ &nbsp; Active Quest</h2>

<div align="center">

<svg width="760" height="178" viewBox="0 0 760 178" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="qBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a0f00;stop-opacity:0.98"/>
      <stop offset="100%" style="stop-color:#2d1a00;stop-opacity:0.95"/>
    </linearGradient>
    <linearGradient id="qBorder" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#f59e0b"/>
      <stop offset="50%" style="stop-color:#fbbf24"/>
      <stop offset="100%" style="stop-color:#f59e0b"/>
    </linearGradient>
    <filter id="qGlow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect x="1" y="1" width="758" height="176" rx="16" fill="none" stroke="url(#qBorder)" stroke-width="1.5" filter="url(#qGlow)"/>
  <rect x="1" y="1" width="758" height="176" rx="16" fill="url(#qBg)"/>
  <rect x="1" y="1" width="758" height="3" rx="2" fill="url(#qBorder)"/>
  <rect x="1" y="1" width="5" height="176" rx="3" fill="#f59e0b"/>

  <!-- Shield -->
  <rect x="22" y="28" width="58" height="58" rx="12" fill="#f59e0b" fill-opacity="0.12" stroke="#f59e0b" stroke-opacity="0.35" stroke-width="1"/>
  <text x="51" y="65" font-family="monospace" font-size="28" text-anchor="middle">🛡️</text>

  <!-- Title + desc -->
  <text x="98" y="48" font-family="monospace" font-size="18" font-weight="bold" fill="#fbbf24" filter="url(#qGlow)">ScamShield</text>
  <text x="98" y="66" font-family="monospace" font-size="11" fill="#d97706">AI-powered scam detection — emails · websites · jobs · SMS</text>

  <!-- Stack pills -->
  <rect x="98" y="76" width="68" height="20" rx="10" fill="#f59e0b" fill-opacity="0.18"/>
  <text x="132" y="90" font-family="monospace" font-size="10" fill="#fbbf24" text-anchor="middle">Next.js</text>
  <rect x="174" y="76" width="60" height="20" rx="10" fill="#f59e0b" fill-opacity="0.18"/>
  <text x="204" y="90" font-family="monospace" font-size="10" fill="#fbbf24" text-anchor="middle">FastAPI</text>
  <rect x="242" y="76" width="62" height="20" rx="10" fill="#f59e0b" fill-opacity="0.18"/>
  <text x="273" y="90" font-family="monospace" font-size="10" fill="#fbbf24" text-anchor="middle">MongoDB</text>
  <rect x="312" y="76" width="52" height="20" rx="10" fill="#f59e0b" fill-opacity="0.18"/>
  <text x="338" y="90" font-family="monospace" font-size="10" fill="#fbbf24" text-anchor="middle">Docker</text>
  <rect x="372" y="76" width="54" height="20" rx="10" fill="#f59e0b" fill-opacity="0.18"/>
  <text x="399" y="90" font-family="monospace" font-size="10" fill="#fbbf24" text-anchor="middle">Python</text>

  <!-- Right side -->
  <text x="580" y="42" font-family="monospace" font-size="10" fill="#f59e0b" opacity="0.6" letter-spacing="2">STATUS</text>
  <text x="580" y="60" font-family="monospace" font-size="13" fill="#fbbf24">🟡  In Development</text>
  <text x="580" y="88" font-family="monospace" font-size="10" fill="#f59e0b" opacity="0.6" letter-spacing="2">DIFFICULTY</text>
  <text x="580" y="106" font-family="monospace" font-size="14" fill="#f59e0b">★★★★☆</text>
  <text x="580" y="128" font-family="monospace" font-size="10" fill="#f59e0b" opacity="0.6" letter-spacing="2">XP REWARD</text>
  <text x="580" y="146" font-family="monospace" font-size="13" fill="#fbbf24">+2500 XP</text>

  <!-- XP bar -->
  <rect x="22" y="136" width="530" height="8" rx="4" fill="#1a0f00" stroke="#f59e0b" stroke-opacity="0.25" stroke-width="1"/>
  <rect x="22" y="136" width="234" height="8" rx="4" fill="url(#qBorder)"/>
  <text x="22" y="158" font-family="monospace" font-size="10" fill="#92400e">PROGRESS  ████████████░░░░░░░░░░░  44%  —  Keep building, hero.</text>
</svg>

</div>

<br/>

---

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║     BLOCK 6 — FEATURED PROJECTS          ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<h2 align="center">🚀 &nbsp; Featured Projects</h2>

<div align="center">

<svg width="860" height="560" viewBox="0 0 860 560" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="projBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#110900;stop-opacity:0.98"/>
      <stop offset="100%" style="stop-color:#1e1200;stop-opacity:0.96"/>
    </linearGradient>
    <linearGradient id="projBorder" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#f59e0b;stop-opacity:0.7"/>
      <stop offset="50%" style="stop-color:#fbbf24;stop-opacity:0.4"/>
      <stop offset="100%" style="stop-color:#f59e0b;stop-opacity:0.7"/>
    </linearGradient>
    <filter id="projGlow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- ── CARD 1: ScamShield (top left) ── -->
  <rect x="10" y="10" width="410" height="250" rx="14" fill="url(#projBg)" stroke="url(#projBorder)" stroke-width="1.2" filter="url(#projGlow)"/>
  <rect x="10" y="10" width="410" height="4" rx="2" fill="#f59e0b"/>
  <!-- icon + title -->
  <text x="30" y="52" font-family="monospace" font-size="22">🛡️</text>
  <text x="60" y="52" font-family="monospace" font-size="16" font-weight="bold" fill="#fbbf24">ScamShield</text>
  <!-- desc -->
  <text x="30" y="80" font-family="monospace" font-size="11" fill="#d97706">AI-powered platform detecting scam emails,</text>
  <text x="30" y="96" font-family="monospace" font-size="11" fill="#d97706">fraudulent websites, fake jobs &amp; SMS in</text>
  <text x="30" y="112" font-family="monospace" font-size="11" fill="#d97706">real-time — protecting users from deception.</text>
  <!-- tech pills -->
  <rect x="30" y="128" width="76" height="20" rx="10" fill="#3b82f6" fill-opacity="0.25" stroke="#3b82f6" stroke-opacity="0.5" stroke-width="1"/>
  <text x="68" y="142" font-family="monospace" font-size="10" fill="#93c5fd" text-anchor="middle">TypeScript</text>
  <rect x="114" y="128" width="58" height="20" rx="10" fill="#3b7a3b" fill-opacity="0.25" stroke="#4ade80" stroke-opacity="0.5" stroke-width="1"/>
  <text x="143" y="142" font-family="monospace" font-size="10" fill="#86efac" text-anchor="middle">Python</text>
  <rect x="180" y="128" width="64" height="20" rx="10" fill="#f59e0b" fill-opacity="0.18" stroke="#f59e0b" stroke-opacity="0.5" stroke-width="1"/>
  <text x="212" y="142" font-family="monospace" font-size="10" fill="#fbbf24" text-anchor="middle">FastAPI</text>
  <rect x="252" y="128" width="66" height="20" rx="10" fill="#10b981" fill-opacity="0.18" stroke="#10b981" stroke-opacity="0.5" stroke-width="1"/>
  <text x="285" y="142" font-family="monospace" font-size="10" fill="#6ee7b7" text-anchor="middle">MongoDB</text>
  <!-- difficulty + stars row -->
  <text x="30" y="178" font-family="monospace" font-size="11" fill="#92400e">Difficulty: ★★★★☆  ·  XP: +2500</text>
  <!-- view repo button -->
  <rect x="30" y="198" width="120" height="32" rx="8" fill="#f59e0b" fill-opacity="0.12" stroke="#f59e0b" stroke-opacity="0.6" stroke-width="1"/>
  <text x="90" y="219" font-family="monospace" font-size="12" fill="#fbbf24" text-anchor="middle">⚡ View Repo</text>

  <!-- ── CARD 2: Adhikar Hain (top right) ── -->
  <rect x="440" y="10" width="410" height="250" rx="14" fill="url(#projBg)" stroke="url(#projBorder)" stroke-width="1.2" filter="url(#projGlow)"/>
  <rect x="440" y="10" width="410" height="4" rx="2" fill="#f59e0b"/>
  <text x="460" y="52" font-family="monospace" font-size="22">⚖️</text>
  <text x="490" y="52" font-family="monospace" font-size="16" font-weight="bold" fill="#fbbf24">Adhikar Hain</text>
  <text x="460" y="80" font-family="monospace" font-size="11" fill="#d97706">Full-stack platform helping citizens identify</text>
  <text x="460" y="96" font-family="monospace" font-size="11" fill="#d97706">wrongful welfare exclusions, understand why,</text>
  <text x="460" y="112" font-family="monospace" font-size="11" fill="#d97706">and take legal action — automatically.</text>
  <!-- pills -->
  <rect x="460" y="128" width="76" height="20" rx="10" fill="#3b82f6" fill-opacity="0.25" stroke="#3b82f6" stroke-opacity="0.5" stroke-width="1"/>
  <text x="498" y="142" font-family="monospace" font-size="10" fill="#93c5fd" text-anchor="middle">TypeScript</text>
  <rect x="544" y="128" width="58" height="20" rx="10" fill="#3b7a3b" fill-opacity="0.25" stroke="#4ade80" stroke-opacity="0.5" stroke-width="1"/>
  <text x="573" y="142" font-family="monospace" font-size="10" fill="#86efac" text-anchor="middle">Python</text>
  <rect x="610" y="128" width="74" height="20" rx="10" fill="#8b5cf6" fill-opacity="0.25" stroke="#8b5cf6" stroke-opacity="0.5" stroke-width="1"/>
  <text x="647" y="142" font-family="monospace" font-size="10" fill="#c4b5fd" text-anchor="middle">Full-Stack</text>
  <text x="460" y="178" font-family="monospace" font-size="11" fill="#92400e">Difficulty: ★★★★★  ·  XP: +3500</text>
  <rect x="460" y="198" width="120" height="32" rx="8" fill="#f59e0b" fill-opacity="0.12" stroke="#f59e0b" stroke-opacity="0.6" stroke-width="1"/>
  <text x="520" y="219" font-family="monospace" font-size="12" fill="#fbbf24" text-anchor="middle">⚡ View Repo</text>

  <!-- ── CARD 3: Paathsala (bottom left) ── -->
  <rect x="10" y="290" width="410" height="250" rx="14" fill="url(#projBg)" stroke="url(#projBorder)" stroke-width="1.2" filter="url(#projGlow)"/>
  <rect x="10" y="290" width="410" height="4" rx="2" fill="#f59e0b"/>
  <text x="30" y="332" font-family="monospace" font-size="22">📚</text>
  <text x="60" y="332" font-family="monospace" font-size="16" font-weight="bold" fill="#fbbf24">Paathsala</text>
  <text x="30" y="360" font-family="monospace" font-size="11" fill="#d97706">Comprehensive education platform with secure</text>
  <text x="30" y="376" font-family="monospace" font-size="11" fill="#d97706">auth, smart routines, lab assignments, exams,</text>
  <text x="30" y="392" font-family="monospace" font-size="11" fill="#d97706">and AI mentoring for students.</text>
  <!-- pills -->
  <rect x="30" y="408" width="76" height="20" rx="10" fill="#f59e0b" fill-opacity="0.25" stroke="#f59e0b" stroke-opacity="0.5" stroke-width="1"/>
  <text x="68" y="422" font-family="monospace" font-size="10" fill="#fbbf24" text-anchor="middle">JavaScript</text>
  <rect x="114" y="408" width="40" height="20" rx="10" fill="#ec4899" fill-opacity="0.20" stroke="#ec4899" stroke-opacity="0.5" stroke-width="1"/>
  <text x="134" y="422" font-family="monospace" font-size="10" fill="#f9a8d4" text-anchor="middle">CSS</text>
  <rect x="162" y="408" width="46" height="20" rx="10" fill="#ef4444" fill-opacity="0.20" stroke="#ef4444" stroke-opacity="0.5" stroke-width="1"/>
  <text x="185" y="422" font-family="monospace" font-size="10" fill="#fca5a5" text-anchor="middle">HTML</text>
  <rect x="216" y="408" width="40" height="20" rx="10" fill="#8b5cf6" fill-opacity="0.20" stroke="#8b5cf6" stroke-opacity="0.5" stroke-width="1"/>
  <text x="236" y="422" font-family="monospace" font-size="10" fill="#c4b5fd" text-anchor="middle">AI</text>
  <text x="30" y="458" font-family="monospace" font-size="11" fill="#92400e">Difficulty: ★★★☆☆  ·  XP: +1800</text>
  <rect x="30" y="478" width="120" height="32" rx="8" fill="#f59e0b" fill-opacity="0.12" stroke="#f59e0b" stroke-opacity="0.6" stroke-width="1"/>
  <text x="90" y="499" font-family="monospace" font-size="12" fill="#fbbf24" text-anchor="middle">⚡ View Repo</text>

  <!-- ── CARD 4: Women's Day Marketplace (bottom right) ── -->
  <rect x="440" y="290" width="410" height="250" rx="14" fill="url(#projBg)" stroke="url(#projBorder)" stroke-width="1.2" filter="url(#projGlow)"/>
  <rect x="440" y="290" width="410" height="4" rx="2" fill="#f59e0b"/>
  <text x="460" y="332" font-family="monospace" font-size="22">🌸</text>
  <text x="490" y="332" font-family="monospace" font-size="16" font-weight="bold" fill="#fbbf24">Women's Day Market</text>
  <text x="460" y="360" font-family="monospace" font-size="11" fill="#d97706">Marketplace for elderly women to showcase</text>
  <text x="460" y="376" font-family="monospace" font-size="11" fill="#d97706">and sell their skills — bridging the gap</text>
  <text x="460" y="392" font-family="monospace" font-size="11" fill="#d97706">between talent and technology access.</text>
  <!-- pills -->
  <rect x="460" y="408" width="76" height="20" rx="10" fill="#f59e0b" fill-opacity="0.25" stroke="#f59e0b" stroke-opacity="0.5" stroke-width="1"/>
  <text x="498" y="422" font-family="monospace" font-size="10" fill="#fbbf24" text-anchor="middle">JavaScript</text>
  <rect x="544" y="408" width="58" height="20" rx="10" fill="#3b7a3b" fill-opacity="0.25" stroke="#4ade80" stroke-opacity="0.5" stroke-width="1"/>
  <text x="573" y="422" font-family="monospace" font-size="10" fill="#86efac" text-anchor="middle">Python</text>
  <rect x="610" y="408" width="56" height="20" rx="10" fill="#06b6d4" fill-opacity="0.20" stroke="#06b6d4" stroke-opacity="0.5" stroke-width="1"/>
  <text x="638" y="422" font-family="monospace" font-size="10" fill="#67e8f9" text-anchor="middle">Docker</text>
  <text x="460" y="458" font-family="monospace" font-size="11" fill="#92400e">Difficulty: ★★★★☆  ·  XP: +2200</text>
  <rect x="460" y="478" width="120" height="32" rx="8" fill="#f59e0b" fill-opacity="0.12" stroke="#f59e0b" stroke-opacity="0.6" stroke-width="1"/>
  <text x="520" y="499" font-family="monospace" font-size="12" fill="#fbbf24" text-anchor="middle">⚡ View Repo</text>
</svg>

</div>

> 💡 *Click the repo names above to visit — replace SVG href values with actual repo URLs once public*

<br/>

---

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║     BLOCK 7 — SNAKE + TROPHIES           ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<h2 align="center">🐍 &nbsp; The Snake Devours My Commits</h2>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Jsher7/Jsher7/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Jsher7/Jsher7/output/github-contribution-grid-snake.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/Jsher7/Jsher7/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

<br/>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Jsher7&theme=onedark&column=4&margin-w=12&margin-h=12&no-bg=false&no-frame=false" />

</div>

<br/>

---

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║     BLOCK 8 — BEYOND THE CODE            ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<h2 align="center">🎬 &nbsp; Beyond the Code</h2>

<div align="center">

<svg width="860" height="220" viewBox="0 0 860 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="beyondBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a0f00;stop-opacity:0.95"/>
      <stop offset="100%" style="stop-color:#2d1a00;stop-opacity:0.90"/>
    </linearGradient>
    <linearGradient id="beyondBorder" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#f59e0b;stop-opacity:0.8"/>
      <stop offset="50%" style="stop-color:#fbbf24;stop-opacity:0.4"/>
      <stop offset="100%" style="stop-color:#f59e0b;stop-opacity:0.8"/>
    </linearGradient>
    <filter id="beyondGlow">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect x="1" y="1" width="858" height="218" rx="18" fill="none" stroke="url(#beyondBorder)" stroke-width="1.5" filter="url(#beyondGlow)"/>
  <rect x="1" y="1" width="858" height="218" rx="18" fill="url(#beyondBg)"/>
  <rect x="1" y="1" width="858" height="3" rx="2" fill="url(#beyondBorder)"/>

  <!-- Card 1 -->
  <rect x="22" y="26" width="192" height="166" rx="14" fill="#f59e0b" fill-opacity="0.07" stroke="#f59e0b" stroke-opacity="0.22" stroke-width="1"/>
  <text x="118" y="72" font-family="monospace" font-size="32" text-anchor="middle">📸</text>
  <text x="118" y="100" font-family="monospace" font-size="13" font-weight="bold" fill="#fbbf24" text-anchor="middle">Photography</text>
  <text x="118" y="118" font-family="monospace" font-size="10" fill="#d97706" text-anchor="middle">Golden hour · Cinematic reels</text>
  <text x="118" y="134" font-family="monospace" font-size="10" fill="#d97706" text-anchor="middle">Raw stories · Visual poetry</text>
  <text x="118" y="166" font-family="monospace" font-size="9" fill="#78350f" text-anchor="middle">Lightroom · Natural light</text>

  <!-- Card 2 -->
  <rect x="228" y="26" width="192" height="166" rx="14" fill="#f59e0b" fill-opacity="0.07" stroke="#f59e0b" stroke-opacity="0.22" stroke-width="1"/>
  <text x="324" y="72" font-family="monospace" font-size="32" text-anchor="middle">🎬</text>
  <text x="324" y="100" font-family="monospace" font-size="13" font-weight="bold" fill="#fbbf24" text-anchor="middle">Video Editing</text>
  <text x="324" y="118" font-family="monospace" font-size="10" fill="#d97706" text-anchor="middle">DaVinci Resolve · Lightroom</text>
  <text x="324" y="134" font-family="monospace" font-size="10" fill="#d97706" text-anchor="middle">CapCut Pro · VN</text>
  <text x="324" y="166" font-family="monospace" font-size="9" fill="#78350f" text-anchor="middle">Color grading · Cinematic cuts</text>

  <!-- Card 3 -->
  <rect x="434" y="26" width="192" height="166" rx="14" fill="#f59e0b" fill-opacity="0.07" stroke="#f59e0b" stroke-opacity="0.22" stroke-width="1"/>
  <text x="530" y="72" font-family="monospace" font-size="32" text-anchor="middle">🎮</text>
  <text x="530" y="100" font-family="monospace" font-size="13" font-weight="bold" fill="#fbbf24" text-anchor="middle">Gaming</text>
  <text x="530" y="118" font-family="monospace" font-size="10" fill="#d97706" text-anchor="middle">Valorant · RDR2 · GOW</text>
  <text x="530" y="134" font-family="monospace" font-size="10" fill="#d97706" text-anchor="middle">GTA5 · F1 · Assetto Corsa</text>
  <text x="530" y="166" font-family="monospace" font-size="9" fill="#78350f" text-anchor="middle">Uncharted · NFS · Infamous</text>

  <!-- Card 4 -->
  <rect x="640" y="26" width="200" height="166" rx="14" fill="#f59e0b" fill-opacity="0.07" stroke="#f59e0b" stroke-opacity="0.22" stroke-width="1"/>
  <text x="740" y="72" font-family="monospace" font-size="32" text-anchor="middle">🎧</text>
  <text x="740" y="100" font-family="monospace" font-size="13" font-weight="bold" fill="#fbbf24" text-anchor="middle">The Vibe</text>
  <text x="740" y="118" font-family="monospace" font-size="10" fill="#d97706" text-anchor="middle">3am lo-fi sessions</text>
  <text x="740" y="134" font-family="monospace" font-size="10" fill="#d97706" text-anchor="middle">Golden hour shoots 🌅</text>
  <text x="740" y="166" font-family="monospace" font-size="9" fill="#78350f" text-anchor="middle">Ships before breakfast ☕</text>
</svg>

</div>

<br/>

---

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║     BLOCK 9 — FOOTER                     ║ -->
<!-- ╚══════════════════════════════════════════╝ -->

<h2 align="center">💬 &nbsp; Dev Thought of the Day</h2>

<div align="center">

![Random Dev Joke](https://readme-jokes.vercel.app/api?theme=dark&bgColor=%230d1117&borderColor=%23f59e0b&qColor=%23f59e0b&aColor=%23fbbf24&textColor=%23e5c687&codeColor=%23d97706)

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0,0d0d0d,1a0f00,2d1a00,1a1a00,0d0d0d&height=150&section=footer&text=Thanks%20for%20visiting%2C%20traveller%20✦&fontSize=20&fontColor=f59e0b&fontAlignY=68&animation=fadeIn" width="100%"/>

</div>

<div align="center">

*⭐ Star a repo if something catches your eye &nbsp;·&nbsp; 📬 Always open to collabs &nbsp;·&nbsp; 🔄 Auto-updated by GitHub Actions*

</div>
