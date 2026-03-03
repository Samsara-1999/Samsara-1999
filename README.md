<div align="center">

<!-- Glassmorphism Animated Header (No external images, no JS) -->
<img
  alt="Samsara Glass Header"
  width="100%"
  src="data:image/svg+xml;utf8,
  <svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 360'>
    <defs>
      <linearGradient id='bg' x1='0' y1='0' x2='1' y2='1'>
        <stop offset='0%' stop-color='%230b1020'/>
        <stop offset='55%' stop-color='%23101630'/>
        <stop offset='100%' stop-color='%230b1020'/>
      </linearGradient>

      <radialGradient id='glow1' cx='25%' cy='30%' r='55%'>
        <stop offset='0%' stop-color='%237c3aed' stop-opacity='0.55'/>
        <stop offset='60%' stop-color='%237c3aed' stop-opacity='0.08'/>
        <stop offset='100%' stop-color='%237c3aed' stop-opacity='0'/>
      </radialGradient>

      <radialGradient id='glow2' cx='78%' cy='32%' r='55%'>
        <stop offset='0%' stop-color='%230ea5e9' stop-opacity='0.50'/>
        <stop offset='60%' stop-color='%230ea5e9' stop-opacity='0.10'/>
        <stop offset='100%' stop-color='%230ea5e9' stop-opacity='0'/>
      </radialGradient>

      <filter id='blur' x='-20%' y='-20%' width='140%' height='140%'>
        <feGaussianBlur stdDeviation='18'/>
      </filter>

      <filter id='glass' x='-20%' y='-20%' width='140%' height='140%'>
        <feGaussianBlur in='SourceGraphic' stdDeviation='6' result='b'/>
        <feColorMatrix in='b' type='matrix'
          values='1 0 0 0 0
                  0 1 0 0 0
                  0 0 1 0 0
                  0 0 0 0.22 0' result='a'/>
        <feComposite in='a' in2='SourceGraphic' operator='over'/>
      </filter>

      <linearGradient id='stroke' x1='0' y1='0' x2='1' y2='1'>
        <stop offset='0%' stop-color='%23ffffff' stop-opacity='0.28'/>
        <stop offset='100%' stop-color='%23ffffff' stop-opacity='0.08'/>
      </linearGradient>

      <linearGradient id='accent' x1='0' y1='0' x2='1' y2='0'>
        <stop offset='0%' stop-color='%237c3aed'/>
        <stop offset='45%' stop-color='%230ea5e9'/>
        <stop offset='100%' stop-color='%2310b981'/>
      </linearGradient>
    </defs>

    <rect width='1200' height='360' fill='url(%23bg)'/>

    <g filter='url(%23blur)'>
      <circle cx='320' cy='120' r='170' fill='url(%23glow1)'/>
      <circle cx='920' cy='120' r='190' fill='url(%23glow2)'/>
    </g>

    <!-- Floating particles -->
    <g opacity='0.65'>
      <circle cx='140' cy='70' r='2.6' fill='%23ffffff'>
        <animate attributeName='cy' values='70;58;70' dur='4.6s' repeatCount='indefinite'/>
        <animate attributeName='opacity' values='0.25;0.9;0.25' dur='4.6s' repeatCount='indefinite'/>
      </circle>
      <circle cx='1080' cy='84' r='2.2' fill='%23ffffff'>
        <animate attributeName='cy' values='84;70;84' dur='5.2s' repeatCount='indefinite'/>
        <animate attributeName='opacity' values='0.2;0.8;0.2' dur='5.2s' repeatCount='indefinite'/>
      </circle>
      <circle cx='1020' cy='210' r='2.8' fill='%23ffffff'>
        <animate attributeName='cy' values='210;196;210' dur='4.2s' repeatCount='indefinite'/>
        <animate attributeName='opacity' values='0.2;0.85;0.2' dur='4.2s' repeatCount='indefinite'/>
      </circle>
      <circle cx='220' cy='245' r='2.1' fill='%23ffffff'>
        <animate attributeName='cy' values='245;258;245' dur='4.9s' repeatCount='indefinite'/>
        <animate attributeName='opacity' values='0.25;0.75;0.25' dur='4.9s' repeatCount='indefinite'/>
      </circle>
    </g>

    <!-- Glass card -->
    <g filter='url(%23glass)'>
      <rect x='90' y='66' rx='22' ry='22' width='1020' height='210'
            fill='%23ffffff' fill-opacity='0.08'
            stroke='url(%23stroke)' stroke-width='1.2'/>
      <rect x='120' y='94' rx='14' ry='14' width='180' height='34'
            fill='%23ffffff' fill-opacity='0.10' stroke='url(%23stroke)' stroke-width='1'/>
      <text x='210' y='118' text-anchor='middle' font-family='ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace'
            font-size='14' fill='%23e5e7eb'>Samsara</text>

      <text x='120' y='160' font-family='ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial'
            font-size='44' fill='%23ffffff' font-weight='800'>Hi, I am Samsara</text>

      <text x='120' y='200' font-family='ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial'
            font-size='18' fill='%23cbd5e1'>
        Direct PhD student in China · Vision Language Models · Architecture · PEFT
      </text>

      <!-- Accent line -->
      <rect x='120' y='220' width='520' height='6' rx='3' fill='url(%23accent)'>
        <animate attributeName='width' values='520;640;520' dur='5.8s' repeatCount='indefinite'/>
      </rect>

      <text x='120' y='255' font-family='ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace'
            font-size='14' fill='%2394a3b8'>
        Always happy to chat about research and engineering.
      </text>
    </g>

    <!-- Animated wave footer -->
    <path d='M0 318 C 180 290, 360 350, 540 322 C 720 295, 900 350, 1200 318 L1200 360 L0 360 Z'
          fill='%23ffffff' fill-opacity='0.06'>
      <animate attributeName='d'
        dur='6.5s' repeatCount='indefinite'
        values='
          M0 318 C 180 290, 360 350, 540 322 C 720 295, 900 350, 1200 318 L1200 360 L0 360 Z;
          M0 322 C 180 350, 360 290, 540 318 C 720 350, 900 295, 1200 322 L1200 360 L0 360 Z;
          M0 318 C 180 290, 360 350, 540 322 C 720 295, 900 350, 1200 318 L1200 360 L0 360 Z
        '/>
    </path>
  </svg>"
/>

</div>

<br/>

<div align="center">

<!-- Fancy badges (these are stable) -->
<img src="https://img.shields.io/badge/Focus-VLMs%20%7C%20Architecture%20%7C%20PEFT-8b5cf6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Role-Server%20Admin%20and%20Ops%20Builder-0ea5e9?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-10b981?style=for-the-badge" />

</div>

---

## 🧠 About Me

I am **Samsara**, a direct-PhD student in China.  
My research focuses on **Vision Language Models**, especially **architecture design** and **parameter efficient fine tuning**.

If you are exploring VLMs, multimodal architecture, or PEFT methods, feel free to reach out. I am always happy to exchange ideas.

---

## 🛠️ Daily Work

I also serve as the **main administrator** of our servers.

- I build ops tools to automate boring tasks and keep clusters stable  
- I enjoy writing infrastructure software and polishing internal workflows  
- I also know PC hardware and building rigs (yes, I enjoy it hahaha)

---

## 🎬♟️🏋️ Hobbies

- Mystery and thriller movies  
- Board games and puzzle or strategy games  
- Fitness

---

## 💼 Job Hunting

I am currently looking for opportunities.  
If you think I could be a good fit for your team, I would really appreciate a referral or a chat.

---

## 🤝 Let’s Talk

- Open an issue in any repo, or contact me on GitHub
- Topics: VLMs, architecture, PEFT, efficiency, systems

<div align="center">

<!-- Animated divider -->
<img
  alt="Animated Divider"
  width="100%"
  src="data:image/svg+xml;utf8,
  <svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 120'>
    <defs>
      <linearGradient id='g' x1='0' y1='0' x2='1' y2='0'>
        <stop offset='0%' stop-color='%237c3aed' stop-opacity='0.0'/>
        <stop offset='25%' stop-color='%237c3aed' stop-opacity='0.7'/>
        <stop offset='55%' stop-color='%230ea5e9' stop-opacity='0.7'/>
        <stop offset='80%' stop-color='%2310b981' stop-opacity='0.7'/>
        <stop offset='100%' stop-color='%2310b981' stop-opacity='0.0'/>
      </linearGradient>
      <filter id='soft'>
        <feGaussianBlur stdDeviation='1.6'/>
      </filter>
    </defs>

    <rect width='1200' height='120' fill='none'/>
    <path id='wave' d='M0 70 C 200 30, 400 110, 600 70 C 800 30, 1000 110, 1200 70'
          stroke='url(%23g)' stroke-width='6' fill='none' filter='url(%23soft)'>
      <animate attributeName='d' dur='5.5s' repeatCount='indefinite'
        values='
          M0 70 C 200 30, 400 110, 600 70 C 800 30, 1000 110, 1200 70;
          M0 70 C 200 110, 400 30, 600 70 C 800 110, 1000 30, 1200 70;
          M0 70 C 200 30, 400 110, 600 70 C 800 30, 1000 110, 1200 70
        '/>
    </path>

    <circle r='6' fill='%23ffffff' opacity='0.85'>
      <animateMotion dur='4.2s' repeatCount='indefinite'>
        <mpath href='%23wave'/>
      </animateMotion>
    </circle>

    <circle r='4' fill='%23ffffff' opacity='0.55'>
      <animateMotion dur='6.4s' repeatCount='indefinite' begin='-1.2s'>
        <mpath href='%23wave'/>
      </animateMotion>
    </circle>
  </svg>"
/>

</div>
