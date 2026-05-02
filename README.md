<!-- ════════════════════════════════════════════════════════════════════════ -->
<!--   RAHAT AHMED CHOWDHURY  ·  PROFILE README                               -->
<!--   Animated SVG assets in /assets — all animations are SMIL-based and     -->
<!--   render natively on GitHub. No JS, no external services for visuals.    -->
<!-- ════════════════════════════════════════════════════════════════════════ -->

<div align="center">

  <!-- Animated background -->
  <rect width="1200" height="320" fill="url(#bgGrad)"/>

  <!-- Subtle grid -->
  <g stroke="#00f5ff" stroke-width="0.5" opacity="0.05">
    <line x1="0" y1="80" x2="1200" y2="80"/>
    <line x1="0" y1="160" x2="1200" y2="160"/>
    <line x1="0" y1="240" x2="1200" y2="240"/>
    <line x1="200" y1="0" x2="200" y2="320"/>
    <line x1="400" y1="0" x2="400" y2="320"/>
    <line x1="600" y1="0" x2="600" y2="320"/>
    <line x1="800" y1="0" x2="800" y2="320"/>
    <line x1="1000" y1="0" x2="1000" y2="320"/>
  </g>

  <!-- Floating particles -->
  <g>
    <circle cx="80" cy="60" r="1.5" fill="#00f5ff" filter="url(#glow)">
      <animate attributeName="cy" values="60;40;60" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.8;0.2;0.8" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="180" cy="240" r="1" fill="#ec4899" filter="url(#glow)">
      <animate attributeName="cy" values="240;220;240" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;0.1;0.6" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="320" cy="100" r="2" fill="#a855f7" filter="url(#glow)">
      <animate attributeName="cy" values="100;80;100" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0.9;0.5" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="900" cy="60" r="1.5" fill="#00f5ff" filter="url(#glow)">
      <animate attributeName="cy" values="60;90;60" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1080" cy="180" r="1" fill="#ec4899" filter="url(#glow)">
      <animate attributeName="cy" values="180;200;180" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;0.2;0.6" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1020" cy="80" r="2" fill="#a855f7" filter="url(#glow)">
      <animate attributeName="cy" values="80;120;80" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0.3;0.7" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="600" cy="50" r="1" fill="white">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="450" cy="270" r="1.5" fill="#00f5ff" filter="url(#glow)">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="750" cy="280" r="1" fill="#ec4899" filter="url(#glow)">
      <animate attributeName="opacity" values="0.5;1;0.5" dur="3.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="220" cy="180" r="1" fill="#a855f7" filter="url(#glow)">
      <animate attributeName="cx" values="220;240;220" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="980" cy="240" r="1.5" fill="#00f5ff" filter="url(#glow)">
      <animate attributeName="cx" values="980;960;980" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;0.2;0.6" dur="7s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Corner brackets that fade in -->
  <g stroke="#00f5ff" stroke-width="2" fill="none">
    <path d="M 100 60 L 60 60 L 60 100" opacity="0">
      <animate attributeName="opacity" from="0" to="0.7" dur="0.8s" begin="0.3s" fill="freeze"/>
    </path>
    <path d="M 1100 60 L 1140 60 L 1140 100" opacity="0">
      <animate attributeName="opacity" from="0" to="0.7" dur="0.8s" begin="0.3s" fill="freeze"/>
    </path>
    <path d="M 100 260 L 60 260 L 60 220" opacity="0">
      <animate attributeName="opacity" from="0" to="0.7" dur="0.8s" begin="0.5s" fill="freeze"/>
    </path>
    <path d="M 1100 260 L 1140 260 L 1140 220" opacity="0">
      <animate attributeName="opacity" from="0" to="0.7" dur="0.8s" begin="0.5s" fill="freeze"/>
    </path>
  </g>

  <!-- Top label "INTRODUCING" -->
  <text x="600" y="100" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#00f5ff" letter-spacing="8" opacity="0">
    ━━━━ INTRODUCING ━━━━
    <animate attributeName="opacity" from="0" to="0.85" dur="1s" begin="0.7s" fill="freeze"/>
  </text>

  <!-- NAME — main headline with gradient -->
  <text x="600" y="178" text-anchor="middle"
        font-family="'Helvetica Neue', Helvetica, Arial, sans-serif"
        font-weight="900"
        font-size="62"
        letter-spacing="2"
        fill="url(#textGrad)"
        filter="url(#glow)"
        opacity="0">
    RAHAT AHMED CHOWDHURY
    <animate attributeName="opacity" from="0" to="1" dur="1.5s" begin="1.2s" fill="freeze"/>
    <animate attributeName="font-size" from="50" to="62" dur="1.5s" begin="1.2s" fill="freeze"/>
  </text>

  <!-- Animated underline -->
  <line x1="600" y1="200" x2="600" y2="200" stroke="url(#textGrad)" stroke-width="2" opacity="0.8">
    <animate attributeName="x1" from="600" to="220" dur="1.2s" begin="2.4s" fill="freeze"/>
    <animate attributeName="x2" from="600" to="980" dur="1.2s" begin="2.4s" fill="freeze"/>
  </line>

  <!-- Tagline -->
  <text x="600" y="234" text-anchor="middle"
        font-family="'Courier New', monospace"
        font-size="16"
        fill="#cbd5e1"
        letter-spacing="4"
        opacity="0">
    Full-stack Developer · Building Modern SaaS Applications
    <animate attributeName="opacity" from="0" to="0.85" dur="1.5s" begin="3s" fill="freeze"/>
  </text>

  <!-- Animated status indicator -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.6s" begin="3.8s" fill="freeze"/>
    <circle cx="528" cy="270" r="4" fill="#10b981" filter="url(#strongGlow)">
      <animate attributeName="opacity" values="1;0.4;1" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="r" values="4;5;4" dur="2s" repeatCount="indefinite"/>
    </circle>

  </g>

  <!-- Shine sweep that loops -->
  <rect width="350" height="320" fill="url(#shineGrad)" opacity="0">
    <animate attributeName="opacity" from="0" to="1" begin="4s" dur="0.5s" fill="freeze"/>
    <animate attributeName="x" from="-350" to="1550" dur="7s" begin="4.5s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>

<br/>

<div align="center">

<a href="https://rahat.tech-noverse.com">
  <img src="https://img.shields.io/badge/Portfolio-0a0e27?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0a0e27" alt="Portfolio"/>
</a>
<a href="https://www.linkedin.com/in/rahat-ahmed-chowdhury/">
  <img src="https://img.shields.io/badge/LinkedIn-0a0e27?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a0e27" alt="LinkedIn"/>
</a>
<a href="mailto:rahatahmedchy01@gmail.com">
  <img src="https://img.shields.io/badge/Email-0a0e27?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0a0e27" alt="Email"/>
</a>
<a href="https://github.com/RahatGithub">
  <img src="https://img.shields.io/badge/GitHub-0a0e27?style=for-the-badge&logo=github&logoColor=white&labelColor=0a0e27" alt="GitHub"/>
</a>

</div>

<br/>

<img src="https://raw.githubusercontent.com/RahatGithub/RahatGithub/main/assets/divider.svg" width="100%" alt=""/>

<br/>

## &nbsp; ◆ &nbsp; About

Full-stack developer with hands-on experience designing and building production-grade SaaS platforms, e-commerce systems, and management applications. Comfortable across the modern stack — **React, Next.js, Node.js, Django** — with a strong interest in **multi-tenant SaaS architecture, real-time systems,** and **scalable backends.**

I write code I'd want to maintain. I ship things that work.

<br/>

<img src="https://raw.githubusercontent.com/RahatGithub/RahatGithub/main/assets/divider.svg" width="100%" alt=""/>

<br/>

## &nbsp; ◆ &nbsp; The Stack, in Orbit

<div align="center">

<img src="https://raw.githubusercontent.com/RahatGithub/RahatGithub/main/assets/tech-orbit.svg" width="700" alt="Tech stack — orbital animation"/>

<br/>
<sub><i>Three concentric orbits, three rotation speeds, three directions. Live.</i></sub>

</div>

<br/>

<img src="https://raw.githubusercontent.com/RahatGithub/RahatGithub/main/assets/divider.svg" width="100%" alt=""/>

<br/>

## &nbsp; ◆ &nbsp; Featured Work

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/RahatGithub/velo-SaaS">
        <img src="https://github.com/RahatGithub/shopflow-SaaS/blob/main/static/img/shopflow-cover.png?raw=true" width="400px;" alt="shopflow SaaS"/>
      </a>
      <br />
      <b>ShopFlow SaaS</b>
      <p>Multi-tenant Inventory + POS app</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/RahatGithub/velo-SaaS">
        <img src="https://github.com/RahatGithub/velo-SaaS/blob/main/static/img/velo-cover.png?raw=true" width="400px;" alt="Velo SaaS"/>
      </a>
      <br />
      <b>Velo SaaS</b>
      <p>Multi-tenant project management app</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/RahatGithub/unimarx-rms">
        <img src="https://github.com/RahatGithub/unimarx-rms/blob/main/screenshots/unimarx-cover.png" width="400px;" alt="Unimarx"/>
      </a>
      <br />
      <b>Unimarx</b>
      <p>university result management system</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/RahatGithub/studynest">
        <img src="https://github.com/RahatGithub/studynest/blob/main/static/images/thumbnail.png" width="400px;" alt="StudyNest"/>
      </a>
      <br />
      <b>StudyNest</b>
      <p>an eLearning application</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/RahatGithub/ameaozon">
        <img src="https://github.com/RahatGithub/ameaozon/blob/main/static/images/thumbnail.png" width="400px;" alt="Ameaozon"/>
      </a>
      <br />
      <b>Ameaozon</b>
      <p>an eCommerce application</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/RahatGithub/QuizWiz-Flask">
        <img src="https://github.com/RahatGithub/QuizWiz-Flask/blob/main/app/static/img/QuizWiz.png" width="400px;" alt="QuizWiz"/>
      </a>
      <br />
      <b>QuizWiz</b>
      <p>an interesting quiz game</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/RahatGithub/fithub-gym-app">
        <img src="https://github.com/RahatGithub/fithub-gym-app/blob/main/src/assets/thumbnail.png" width="400px;" alt="Fithub"/>
      </a>
      <br />
      <b>FitHub</b>
      <p>a gym subscription app</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/RahatGithub/QBoard">
        <img src="https://github.com/RahatGithub/QBoard/blob/main/static/img/Qboard.png" width="400px;" alt="QBoard"/>
      </a>
      <br />
      <b>QBoard</b>
      <p>RESTful API for dashboard data</p>
    </td>
  </tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/RahatGithub/RahatGithub/main/assets/divider.svg" width="100%" alt=""/>

<br/>

## &nbsp; ◆ &nbsp; Activity & Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=RahatGithub&show_icons=true&hide_border=true&bg_color=0d1b2a&title_color=00f5ff&icon_color=a855f7&text_color=cbd5e1&count_private=true" height="170" alt="GitHub Stats"/>
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com?user=RahatGithub&hide_border=true&background=0d1b2a&stroke=a855f7&ring=00f5ff&fire=ec4899&currStreakLabel=00f5ff&sideLabels=cbd5e1&dates=cbd5e1&currStreakNum=ffffff&sideNums=a855f7" height="170" alt="GitHub Streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=RahatGithub&bg_color=0d1b2a&color=00f5ff&line=a855f7&point=ec4899&hide_border=true&area=true&area_color=a855f7" alt="Activity Graph" width="98%"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/RahatGithub/RahatGithub/main/assets/divider.svg" width="100%" alt=""/>

<br/>

## &nbsp; ◆ &nbsp; Connect

Open to collaboration, full-time roles, and ambitious projects. The fastest way to reach me:

<div align="center">

<a href="https://rahat.tech-noverse.com">
  <img src="https://img.shields.io/badge/View_Portfolio-0d1b2a?style=for-the-badge&logo=vercel&logoColor=10b981&labelColor=0d1b2a" alt="Portfolio"/>
</a>
&nbsp;
<a href="mailto:rahatahmedchy01@gmail.com">
  <img src="https://img.shields.io/badge/Send_a_message-0d1b2a?style=for-the-badge&logo=gmail&logoColor=ec4899&labelColor=0d1b2a" alt="Email"/>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/rahat-ahmed-chowdhury/">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0d1b2a?style=for-the-badge&logo=linkedin&logoColor=00f5ff&labelColor=0d1b2a" alt="LinkedIn"/>
</a>

</div>

<br/>

<img src="https://raw.githubusercontent.com/RahatGithub/RahatGithub/main/assets/footer.svg" width="100%" alt=""/>
