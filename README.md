<div align="center">

<svg xmlns="http://www.w3.org/2000/svg"
     width="100%"
     viewBox="0 0 1200 360"
     role="img"
     aria-label="ZUDOCHAN007 GitHub Profile">

  <defs>

    <!-- Background -->
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#06141f"/>
      <stop offset="50%" stop-color="#0b2533"/>
      <stop offset="100%" stop-color="#06141f"/>
    </linearGradient>

    <!-- Main neon -->
    <linearGradient id="neon" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#22d3ee"/>
      <stop offset="50%" stop-color="#2dd4bf"/>
      <stop offset="100%" stop-color="#60a5fa"/>
    </linearGradient>

    <!-- Glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Grid -->
    <pattern id="grid"
             width="30"
             height="30"
             patternUnits="userSpaceOnUse">

      <path d="M30 0H0V30"
            fill="none"
            stroke="#2dd4bf"
            stroke-opacity="0.12"/>

    </pattern>

    <!-- Scan -->
    <linearGradient id="scan"
                    x1="0"
                    y1="0"
                    x2="0"
                    y2="1">

      <stop offset="0%"
            stop-color="#22d3ee"
            stop-opacity="0"/>

      <stop offset="50%"
            stop-color="#22d3ee"
            stop-opacity="0.45"/>

      <stop offset="100%"
            stop-color="#22d3ee"
            stop-opacity="0"/>

    </linearGradient>

    <!-- Clip -->
    <clipPath id="screen">
      <rect x="1"
            y="1"
            width="1198"
            height="358"
            rx="22"/>
    </clipPath>

  </defs>


  <!-- ================= BACKGROUND ================= -->

  <rect x="1"
        y="1"
        width="1198"
        height="358"
        rx="22"
        fill="url(#bg)"
        stroke="#2dd4bf"
        stroke-opacity="0.55"/>

  <rect x="1"
        y="1"
        width="1198"
        height="358"
        rx="22"
        fill="url(#grid)"
        clip-path="url(#screen)"/>


  <!-- ================= TERMINAL BAR ================= -->

  <rect x="1"
        y="1"
        width="1198"
        height="42"
        rx="22"
        fill="#071018"/>

  <line x1="1"
        y1="42"
        x2="1199"
        y2="42"
        stroke="#2dd4bf"
        stroke-opacity="0.25"/>


  <!-- Terminal dots -->

  <circle cx="24"
          cy="22"
          r="6"
          fill="#ff5f56"/>

  <circle cx="45"
          cy="22"
          r="6"
          fill="#ffbd2e"/>

  <circle cx="66"
          cy="22"
          r="6"
          fill="#27c93f"/>


  <!-- Terminal text -->

  <text x="600"
        y="27"
        text-anchor="middle"
        font-family="monospace"
        font-size="13"
        fill="#7dd3fc">

    zudochan007@github:~$ ./profile.sh

  </text>


  <!-- ================= GLOW ORBS ================= -->

  <circle cx="110"
          cy="120"
          r="100"
          fill="#22d3ee"
          opacity="0.08">

    <animate
      attributeName="r"
      values="80;120;80"
      dur="5s"
      repeatCount="indefinite"/>

  </circle>


  <circle cx="1090"
          cy="270"
          r="130"
          fill="#2dd4bf"
          opacity="0.07">

    <animate
      attributeName="r"
      values="110;150;110"
      dur="6s"
      repeatCount="indefinite"/>

  </circle>


  <!-- ================= LEFT SIDE ================= -->

  <text x="75"
        y="92"
        font-family="monospace"
        font-size="13"
        font-weight="bold"
        letter-spacing="3"
        fill="#5eead4">

    SYSTEM ONLINE

  </text>


  <!-- Name -->

  <text x="75"
        y="145"
        font-family="monospace"
        font-size="48"
        font-weight="bold"
        fill="url(#neon)"
        filter="url(#glow)">

    ZUDOCHAN007

  </text>


  <!-- Typing effect -->

  <text x="78"
        y="177"
        font-family="monospace"
        font-size="16"
        fill="#ccfbf1">

    &gt; Software Engineering Student_

    <animate
      attributeName="opacity"
      values="1;0;1"
      dur="1.2s"
      repeatCount="indefinite"/>

  </text>


  <!-- Description -->

  <text x="78"
        y="208"
        font-family="monospace"
        font-size="13"
        fill="#94a3b8">

    Building modern Web • AI • Software

  </text>


  <!-- ================= SKILLS ================= -->

  <g transform="translate(78 235)">

    <rect width="100"
          height="30"
          rx="15"
          fill="#0f2b35"
          stroke="#2dd4bf"
          stroke-opacity="0.7"/>

    <text x="50"
          y="20"
          text-anchor="middle"
          font-family="monospace"
          font-size="12"
          fill="#ccfbf1">

      JavaScript

    </text>

  </g>


  <g transform="translate(188 235)">

    <rect width="80"
          height="30"
          rx="15"
          fill="#0f2b35"
          stroke="#2dd4bf"
          stroke-opacity="0.7"/>

    <text x="40"
          y="20"
          text-anchor="middle"
          font-family="monospace"
          font-size="12"
          fill="#ccfbf1">

      React

    </text>

  </g>


  <g transform="translate(278 235)">

    <rect width="85"
          height="30"
          rx="15"
          fill="#0f2b35"
          stroke="#2dd4bf"
          stroke-opacity="0.7"/>

    <text x="42"
          y="20"
          text-anchor="middle"
          font-family="monospace"
          font-size="12"
          fill="#ccfbf1">

      .NET

    </text>

  </g>


  <g transform="translate(373 235)">

    <rect width="65"
          height="30"
          rx="15"
          fill="#0f2b35"
          stroke="#2dd4bf"
          stroke-opacity="0.7"/>

    <text x="32"
          y="20"
          text-anchor="middle"
          font-family="monospace"
          font-size="12"
          fill="#ccfbf1">

      AI

    </text>

  </g>


  <!-- ================= RIGHT PANEL ================= -->

  <rect x="710"
        y="80"
        width="410"
        height="215"
        rx="18"
        fill="#06151d"
        fill-opacity="0.78"
        stroke="#2dd4bf"
        stroke-opacity="0.35"/>


  <text x="740"
        y="112"
        font-family="monospace"
        font-size="12"
        font-weight="bold"
        letter-spacing="2"
        fill="#5eead4">

    PROFILE_SCAN

  </text>


  <!-- INFO 1 -->

  <text x="740"
        y="145"
        font-family="monospace"
        font-size="13"
        font-weight="bold"
        fill="#2dd4bf">

    USER

  </text>

  <line x1="805"
        y1="141"
        x2="1030"
        y2="141"
        stroke="#5eead4"
        stroke-opacity="0.25"
        stroke-dasharray="3 5"/>

  <text x="1045"
        y="145"
        font-family="monospace"
        font-size="13"
        fill="#ccfbf1">

    @zudochan007

  </text>


  <!-- INFO 2 -->

  <text x="740"
        y="180"
        font-family="monospace"
        font-size="13"
        font-weight="bold"
        fill="#2dd4bf">

    ROLE

  </text>

  <line x1="805"
        y1="176"
        x2="1030"
        y2="176"
        stroke="#5eead4"
        stroke-opacity="0.25"
        stroke-dasharray="3 5"/>

  <text x="1045"
        y="180"
        font-family="monospace"
        font-size="13"
        fill="#ccfbf1">

    Developer

  </text>


  <!-- INFO 3 -->

  <text x="740"
        y="215"
        font-family="monospace"
        font-size="13"
        font-weight="bold"
        fill="#2dd4bf">

    FOCUS

  </text>

  <line x1="805"
        y1="211"
        x2="1030"
        y2="211"
        stroke="#5eead4"
        stroke-opacity="0.25"
        stroke-dasharray="3 5"/>

  <text x="1045"
        y="215"
        font-family="monospace"
        font-size="13"
        fill="#ccfbf1">

    Web / AI

  </text>


  <!-- INFO 4 -->

  <text x="740"
        y="250"
        font-family="monospace"
        font-size="13"
        font-weight="bold"
        fill="#2dd4bf">

    STATUS

  </text>

  <line x1="805"
        y1="246"
        x2="1030"
        y2="246"
        stroke="#5eead4"
        stroke-opacity="0.25"
        stroke-dasharray="3 5"/>

  <text x="1045"
        y="250"
        font-family="monospace"
        font-size="13"
        fill="#4ade80">

    ONLINE

  </text>


  <!-- ================= SCAN LINE ================= -->

  <rect x="20"
        y="45"
        width="1160"
        height="65"
        fill="url(#scan)"
        opacity="0.35">

    <animateTransform
      attributeName="transform"
      type="translate"
      from="0 -100"
      to="0 420"
      dur="4.5s"
      repeatCount="indefinite"/>

  </rect>


  <!-- ================= FOOTER ================= -->

  <text x="1130"
        y="335"
        text-anchor="end"
        font-family="monospace"
        font-size="10"
        fill="#5eead4"
        opacity="0.55">

    ZUDOCHAN007 // GITHUB

  </text>

</svg>

</div>


<br>

<div align="center">

### ⚡ BUILD • CREATE • LEARN • REPEAT ⚡

</div>

---

## 👨‍💻 About Me

```text
┌─────────────────────────────────────────────┐
│              ZUDOCHAN007                    │
├─────────────────────────────────────────────┤
│                                             │
│  Software Engineering Student               │
│                                             │
│  🌐 Web Development                         │
│  🤖 Artificial Intelligence                  │
│  ⚛️ React / JavaScript                      │
│  ⚙️ .NET / Backend                          │
│  🗄️ Database                                │
│                                             │
│  Always learning something new... 🚀        │
│                                             │
└─────────────────────────────────────────────┘
