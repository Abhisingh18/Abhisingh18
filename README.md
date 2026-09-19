<div align="center">

<!-- ===================== FUTURISTIC AI BANNER ===================== -->

<svg width="100%" height="360" viewBox="0 0 1200 360"
     xmlns="http://www.w3.org/2000/svg">

  <defs>

    <!-- Background -->
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#050816"/>
      <stop offset="45%" stop-color="#101B45"/>
      <stop offset="100%" stop-color="#16082F"/>
    </linearGradient>

    <!-- Neon path -->
    <linearGradient id="path" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00E5FF"/>
      <stop offset="25%" stop-color="#7C3AED"/>
      <stop offset="50%" stop-color="#FF3CAC"/>
      <stop offset="75%" stop-color="#FFB000"/>
      <stop offset="100%" stop-color="#00FFB3"/>
    </linearGradient>

    <!-- Text gradient -->
    <linearGradient id="title" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00E5FF"/>
      <stop offset="50%" stop-color="#FFFFFF"/>
      <stop offset="100%" stop-color="#FF5ACD"/>
    </linearGradient>

    <!-- Glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Strong glow -->
    <filter id="strongGlow">
      <feGaussianBlur stdDeviation="10" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

  </defs>

  <!-- Background -->
  <rect width="1200" height="360" rx="25" fill="url(#bg)"/>

  <!-- Stars -->
  <g fill="#FFFFFF" opacity="0.8">
    <circle cx="80" cy="55" r="2"/>
    <circle cx="180" cy="105" r="1.5"/>
    <circle cx="300" cy="40" r="2"/>
    <circle cx="420" cy="90" r="1"/>
    <circle cx="520" cy="35" r="2"/>
    <circle cx="680" cy="75" r="1.5"/>
    <circle cx="820" cy="35" r="2"/>
    <circle cx="980" cy="85" r="1.5"/>
    <circle cx="1110" cy="45" r="2"/>
    <circle cx="1150" cy="150" r="1"/>
  </g>

  <!-- Decorative planets -->
  <circle cx="95" cy="270" r="48"
          fill="#172554"
          stroke="#00E5FF"
          stroke-width="2"
          opacity="0.9"/>

  <circle cx="1090" cy="280" r="58"
          fill="#24103F"
          stroke="#FF5ACD"
          stroke-width="2"
          opacity="0.9"/>

  <!-- Planet rings -->
  <ellipse cx="1090" cy="280"
           rx="82" ry="22"
           fill="none"
           stroke="#FF5ACD"
           stroke-width="2"
           opacity="0.6"/>

  <!-- Main heading -->
  <text x="600" y="70"
        text-anchor="middle"
        font-family="Arial, sans-serif"
        font-size="42"
        font-weight="800"
        fill="url(#title)">
    LLM RESEARCHER
  </text>

  <text x="600" y="110"
        text-anchor="middle"
        font-family="Arial, sans-serif"
        font-size="27"
        font-weight="700"
        fill="#FFB86C">
    AI ENGINEER
  </text>

  <text x="600" y="140"
        text-anchor="middle"
        font-family="Arial, sans-serif"
        font-size="15"
        fill="#D6E4FF">
    Research • Build • Deploy • Impact
  </text>

  <!-- Travelling path glow -->
  <path d="M 80 255
           C 250 175, 350 315, 500 220
           C 650 125, 730 270, 850 190
           C 960 115, 1050 175, 1110 130"
        fill="none"
        stroke="#FFFFFF"
        stroke-width="10"
        opacity="0.12"
        filter="url(#strongGlow)"/>

  <!-- Main neon path -->
  <path d="M 80 255
           C 250 175, 350 315, 500 220
           C 650 125, 730 270, 850 190
           C 960 115, 1050 175, 1110 130"
        fill="none"
        stroke="url(#path)"
        stroke-width="4"
        filter="url(#glow)"/>

  <!-- Milestone 1 -->
  <circle cx="250" cy="205" r="25"
          fill="#07152F"
          stroke="#00E5FF"
          stroke-width="3"
          filter="url(#glow)"/>

  <text x="250" y="211"
        text-anchor="middle"
        font-size="19">
    🧠
  </text>

  <text x="250" y="250"
        text-anchor="middle"
        fill="#00E5FF"
        font-family="Arial"
        font-size="14"
        font-weight="700">
    LEARN
  </text>

  <!-- Milestone 2 -->
  <circle cx="500" cy="220" r="25"
          fill="#07152F"
          stroke="#A855F7"
          stroke-width="3"
          filter="url(#glow)"/>

  <text x="500" y="226"
        text-anchor="middle"
        font-size="19">
    ⚙️
  </text>

  <text x="500" y="265"
        text-anchor="middle"
        fill="#C084FC"
        font-family="Arial"
        font-size="14"
        font-weight="700">
    BUILD
  </text>

  <!-- Milestone 3 -->
  <circle cx="730" cy="235" r="25"
          fill="#07152F"
          stroke="#FF3CAC"
          stroke-width="3"
          filter="url(#glow)"/>

  <text x="730" y="241"
        text-anchor="middle"
        font-size="19">
    🤖
  </text>

  <text x="730" y="278"
        text-anchor="middle"
        fill="#FF5ACD"
        font-family="Arial"
        font-size="14"
        font-weight="700">
    TRAIN
  </text>

  <!-- Milestone 4 -->
  <circle cx="900" cy="165" r="25"
          fill="#07152F"
          stroke="#FFB000"
          stroke-width="3"
          filter="url(#glow)"/>

  <text x="900" y="171"
        text-anchor="middle"
        font-size="19">
    🚀
  </text>

  <text x="900" y="205"
        text-anchor="middle"
        fill="#FFB000"
        font-family="Arial"
        font-size="14"
        font-weight="700">
    DEPLOY
  </text>

  <!-- ================= TRAVELLING ROBOT ================= -->

  <g>

    <!-- Robot body -->
    <rect x="40" y="225"
          width="42"
          height="30"
          rx="10"
          fill="#EAF7FF"
          stroke="#00E5FF"
          stroke-width="2"/>

    <!-- Robot head -->
    <rect x="38" y="195"
          width="46"
          height="35"
          rx="12"
          fill="#FFFFFF"
          stroke="#00E5FF"
          stroke-width="2"/>

    <!-- Robot eyes -->
    <circle cx="51" cy="211" r="4"
            fill="#00E5FF"
            filter="url(#glow)"/>

    <circle cx="71" cy="211" r="4"
            fill="#FF5ACD"
            filter="url(#glow)"/>

    <!-- Antenna -->
    <line x1="61" y1="195"
          x2="61" y2="184"
          stroke="#FFFFFF"
          stroke-width="2"/>

    <circle cx="61" cy="181" r="4"
            fill="#FFB000"
            filter="url(#glow)"/>

    <!-- Robot legs -->
    <line x1="51" y1="255"
          x2="45" y2="267"
          stroke="#FFFFFF"
          stroke-width="4"/>

    <line x1="71" y1="255"
          x2="77" y2="267"
          stroke="#FFFFFF"
          stroke-width="4"/>

    <!-- Robot arms -->
    <line x1="40" y1="235"
          x2="28" y2="245"
          stroke="#FFFFFF"
          stroke-width="4"/>

    <line x1="82" y1="235"
          x2="94" y2="225"
          stroke="#FFFFFF"
          stroke-width="4"/>

    <!-- Jet trail -->
    <path d="M 28 250 L 5 260 L 27 270 Z"
          fill="#00E5FF"
          opacity="0.8"
          filter="url(#glow)"/>

    <!-- ROBOT TRAVEL ANIMATION -->
    <animateMotion
      dur="8s"
      repeatCount="indefinite"
      rotate="auto"
      path="M 0,0
            C 180,-80 300,60 460,-35
            C 620,-130 700,15 820,-65
            C 940,-140 1040,-80 1070,-125"/>
  </g>

  <!-- Bottom tech labels -->

  <g font-family="Arial" font-size="13" font-weight="600">

    <rect x="245" y="315"
          width="120" height="28"
          rx="14"
          fill="#07152F"
          stroke="#00E5FF"/>

    <text x="305" y="334"
          text-anchor="middle"
          fill="#00E5FF">
      LLMs
    </text>

    <rect x="380" y="315"
          width="150" height="28"
          rx="14"
          fill="#07152F"
          stroke="#A855F7"/>

    <text x="455" y="334"
          text-anchor="middle"
          fill="#C084FC">
      MULTIMODAL AI
    </text>

    <rect x="545" y="315"
          width="125" height="28"
          rx="14"
          fill="#07152F"
          stroke="#FF3CAC"/>

    <text x="607" y="334"
          text-anchor="middle"
          fill="#FF5ACD">
      GENERATIVE AI
    </text>

    <rect x="685" y="315"
          width="105" height="28"
          rx="14"
          fill="#07152F"
          stroke="#FFB000"/>

    <text x="737" y="334"
          text-anchor="middle"
          fill="#FFB000">
      MLOps
    </text>

  </g>

</svg>

</div>

<br/>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=800&color=00D9FF&center=true&vCenter=true&width=850&lines=LLM+Researcher+%40+IIT+Madras;AI+Engineer+%7C+Multimodal+AI+%7C+Generative+AI;Training+Models+from+Scratch;Research+%E2%86%92+Production+AI;Building+Intelligent+Systems+That+Scale" />

<br/>

**🧠 LLMs** &nbsp;•&nbsp;
**🤖 Multimodal AI** &nbsp;•&nbsp;
**🔬 AI Research** &nbsp;•&nbsp;
**⚙️ MLOps** &nbsp;•&nbsp;
**⚡ Generative AI**

</div>

---

# 👋 About Me

I am an **LLM Researcher @ IIT Madras** and AI Engineer focused on building scalable AI systems that bridge the gap between **research and production**.

My work spans **Large Language Models, Multimodal AI, Generative AI, intelligent automation, and production-grade AI systems**.

I enjoy working from first principles — from **understanding architectures and training models from scratch** to deploying reliable systems for real-world applications.

---

## 🔬 Research & Engineering

```text
┌──────────────────────────────────────────────────────┐
│                  AI RESEARCH STACK                   │
├──────────────────────────────────────────────────────┤
│                                                      │
│  🧠 LLMs              → Transformers • MoE          │
│  🤖 Multimodal AI     → Vision • Language • Speech  │
│  🎨 Generative AI     → Diffusion • GANs            │
│  🎙️ Speech AI         → ASR • TTS • S2ST            │
│  ⚙️ AI Engineering    → FastAPI • PyTorch • MLOps   │
│  🔎 AI Systems        → RAG • Agents • Vector DBs   │
│                                                      │
└──────────────────────────────────────────────────────┘
