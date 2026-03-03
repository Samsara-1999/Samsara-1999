<div align="center">

<img
  alt="Samsara Cosmic Header"
  width="100%"
  src="data:image/svg+xml;utf8,
  <svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 420'>
    <defs>
      <linearGradient id='space' x1='0' y1='0' x2='1' y2='1'>
        <stop offset='0%' stop-color='%23020713'/>
        <stop offset='45%' stop-color='%230b1533'/>
        <stop offset='100%' stop-color='%23030a1d'/>
      </linearGradient>

      <radialGradient id='nebulaA' cx='20%' cy='20%' r='70%'>
        <stop offset='0%' stop-color='%237a5cff' stop-opacity='0.55'/>
        <stop offset='60%' stop-color='%237a5cff' stop-opacity='0.08'/>
        <stop offset='100%' stop-color='%237a5cff' stop-opacity='0'/>
      </radialGradient>

      <radialGradient id='nebulaB' cx='82%' cy='30%' r='70%'>
        <stop offset='0%' stop-color='%2300d4ff' stop-opacity='0.52'/>
        <stop offset='62%' stop-color='%2300d4ff' stop-opacity='0.08'/>
        <stop offset='100%' stop-color='%2300d4ff' stop-opacity='0'/>
      </radialGradient>

      <radialGradient id='planet' cx='35%' cy='30%' r='70%'>
        <stop offset='0%' stop-color='%23bff1ff'/>
        <stop offset='60%' stop-color='%2358b6ff'/>
        <stop offset='100%' stop-color='%231c3b8f'/>
      </radialGradient>

      <linearGradient id='glassStroke' x1='0' y1='0' x2='1' y2='1'>
        <stop offset='0%' stop-color='%23ffffff' stop-opacity='0.30'/>
        <stop offset='100%' stop-color='%23ffffff' stop-opacity='0.04'/>
      </linearGradient>

      <linearGradient id='accent' x1='0' y1='0' x2='1' y2='0'>
        <stop offset='0%' stop-color='%237a5cff'/>
        <stop offset='50%' stop-color='%2300d4ff'/>
        <stop offset='100%' stop-color='%235cf2c1'/>
      </linearGradient>

      <filter id='blurLarge'>
        <feGaussianBlur stdDeviation='24'/>
      </filter>

      <filter id='glow'>
        <feGaussianBlur stdDeviation='2.3' result='b'/>
        <feMerge>
          <feMergeNode in='b'/>
          <feMergeNode in='SourceGraphic'/>
        </feMerge>
      </filter>
    </defs>

    <rect width='1200' height='420' fill='url(%23space)'/>

    <g filter='url(%23blurLarge)'>
      <circle cx='220' cy='90' r='180' fill='url(%23nebulaA)'/>
      <circle cx='980' cy='130' r='220' fill='url(%23nebulaB)'/>
    </g>

    <g opacity='0.85'>
      <circle cx='78' cy='60' r='1.8' fill='%23fff'>
        <animate attributeName='opacity' values='0.2;1;0.2' dur='4.1s' repeatCount='indefinite'/>
      </circle>
      <circle cx='189' cy='130' r='1.3' fill='%23fff'>
        <animate attributeName='opacity' values='0.1;0.95;0.1' dur='3.7s' repeatCount='indefinite'/>
      </circle>
      <circle cx='346' cy='52' r='1.6' fill='%23fff'>
        <animate attributeName='opacity' values='0.2;0.9;0.2' dur='5.4s' repeatCount='indefinite'/>
      </circle>
      <circle cx='483' cy='114' r='1.4' fill='%23fff'>
        <animate attributeName='opacity' values='0.15;1;0.15' dur='4.4s' repeatCount='indefinite'/>
      </circle>
      <circle cx='602' cy='64' r='1.7' fill='%23fff'>
        <animate attributeName='opacity' values='0.25;0.95;0.25' dur='3.9s' repeatCount='indefinite'/>
      </circle>
      <circle cx='754' cy='108' r='1.5' fill='%23fff'>
        <animate attributeName='opacity' values='0.2;0.85;0.2' dur='4.8s' repeatCount='indefinite'/>
      </circle>
      <circle cx='908' cy='66' r='1.9' fill='%23fff'>
        <animate attributeName='opacity' values='0.2;1;0.2' dur='5.1s' repeatCount='indefinite'/>
      </circle>
      <circle cx='1034' cy='150' r='1.4' fill='%23fff'>
        <animate attributeName='opacity' values='0.25;0.8;0.25' dur='3.5s' repeatCount='indefinite'/>
      </circle>
      <circle cx='1120' cy='82' r='1.8' fill='%23fff'>
        <animate attributeName='opacity' values='0.15;1;0.15' dur='5.2s' repeatCount='indefinite'/>
      </circle>
    </g>

    <g filter='url(%23glow)' opacity='0.8'>
      <line x1='1040' y1='40' x2='940' y2='120' stroke='%23ffffff' stroke-opacity='0.75' stroke-width='1.2'>
        <animate attributeName='x1' values='1040;1010;1040' dur='5.2s' repeatCount='indefinite'/>
        <animate attributeName='x2' values='940;910;940' dur='5.2s' repeatCount='indefinite'/>
        <animate attributeName='opacity' values='0;0.95;0' dur='5.2s' repeatCount='indefinite'/>
      </line>
      <line x1='260' y1='70' x2='170' y2='142' stroke='%23ffffff' stroke-opacity='0.65' stroke-width='1'>
        <animate attributeName='x1' values='260;240;260' dur='6.6s' repeatCount='indefinite'/>
        <animate attributeName='x2' values='170;150;170' dur='6.6s' repeatCount='indefinite'/>
        <animate attributeName='opacity' values='0;0.85;0' dur='6.6s' repeatCount='indefinite'/>
      </line>
    </g>

    <circle cx='930' cy='300' r='56' fill='url(%23planet)' opacity='0.95'>
      <animate attributeName='cy' values='300;292;300' dur='7s' repeatCount='indefinite'/>
    </circle>
    <ellipse cx='930' cy='300' rx='90' ry='21' fill='none' stroke='%23d9f8ff' stroke-opacity='0.4' stroke-width='2'/>

    <ellipse cx='180' cy='312' rx='58' ry='12' fill='none' stroke='%23a084ff' stroke-opacity='0.45' stroke-width='1.5'>
      <animateTransform attributeName='transform' type='rotate' values='0 180 312;360 180 312' dur='14s' repeatCount='indefinite'/>
    </ellipse>
    <circle cx='238' cy='312' r='9' fill='%23b6fbff'/>

    <g>
      <rect x='88' y='86' width='1024' height='248' rx='24' fill='%23ffffff' fill-opacity='0.08' stroke='url(%23glassStroke)' stroke-width='1.2'/>
      <rect x='118' y='116' width='188' height='36' rx='10' fill='%23ffffff' fill-opacity='0.10' stroke='url(%23glassStroke)'/>
      <text x='212' y='139' text-anchor='middle' fill='%23e5f3ff' font-size='14' font-family='Consolas, Monaco, monospace'>Samsara Hyperlane</text>
      <text x='118' y='194' fill='%23ffffff' font-size='52' font-weight='700' font-family='Segoe UI, Arial, sans-serif'>Hello, I am Samsara</text>
      <text x='118' y='234' fill='%23c9def9' font-size='20' font-family='Segoe UI, Arial, sans-serif'>Direct PhD in China | Vision Language Models | Architecture | PEFT</text>
      <rect x='118' y='256' width='590' height='6' rx='3' fill='url(%23accent)'>
        <animate attributeName='width' values='590;700;590' dur='5.8s' repeatCount='indefinite'/>
      </rect>
      <text x='118' y='296' fill='%239bb2cf' font-size='15' font-family='Consolas, Monaco, monospace'>Exploring efficient multimodal systems and reliable engineering.</text>
    </g>

    <path d='M0 368 C 190 338, 380 404, 570 372 C 760 340, 950 404, 1200 370 L1200 420 L0 420 Z' fill='%23ffffff' fill-opacity='0.06'>
      <animate attributeName='d' dur='8s' repeatCount='indefinite'
      values='
      M0 368 C 190 338, 380 404, 570 372 C 760 340, 950 404, 1200 370 L1200 420 L0 420 Z;
      M0 372 C 190 404, 380 338, 570 368 C 760 404, 950 340, 1200 374 L1200 420 L0 420 Z;
      M0 368 C 190 338, 380 404, 570 372 C 760 340, 950 404, 1200 370 L1200 420 L0 420 Z'/>
    </path>
  </svg>"
/>

</div>

<br/>

<div align="center">

<img src="https://img.shields.io/badge/Field-VLM%20%7C%20Architecture%20%7C%20PEFT-6d5efc?style=for-the-badge" />
<img src="https://img.shields.io/badge/Role-Server%20Admin%20%26%20Ops-14b8ff?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Open%20to%20Research%20%26%20Work-3cd6b8?style=for-the-badge" />

</div>

---

## Cosmic Profile

I am **Samsara**, a direct-PhD student in China.  
My main route is **Vision Language Models**, with focus on:

- Multimodal architecture design
- Parameter-efficient fine-tuning
- Practical system optimization

I enjoy turning research ideas into robust engineering artifacts.

---

## Glass Deck

| Module | Current Focus |
| --- | --- |
| `research.core` | VLM architecture and PEFT experiments |
| `infra.ops` | Cluster stability, automation, and internal tools |
| `performance.loop` | Resource efficiency and deployment practicality |

---

## Daily Orbit

- Building ops workflows to reduce repetitive maintenance
- Developing utility software for server and cluster management
- Keeping both research iteration speed and system reliability high

---

## Beyond Work

- Mystery and thriller films
- Board games and strategy games
- Fitness and strength training

---

## Contact Channel

- Open an issue in any repo, or message me on GitHub
- Topics: VLMs, multimodal architecture, PEFT, infra engineering

<div align="center">

<img
  alt="Cosmic Divider"
  width="100%"
  src="data:image/svg+xml;utf8,
  <svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 150'>
    <defs>
      <linearGradient id='trail' x1='0' y1='0' x2='1' y2='0'>
        <stop offset='0%' stop-color='%237a5cff' stop-opacity='0'/>
        <stop offset='25%' stop-color='%237a5cff' stop-opacity='0.8'/>
        <stop offset='55%' stop-color='%2300d4ff' stop-opacity='0.85'/>
        <stop offset='85%' stop-color='%235cf2c1' stop-opacity='0.8'/>
        <stop offset='100%' stop-color='%235cf2c1' stop-opacity='0'/>
      </linearGradient>
    </defs>

    <rect width='1200' height='150' fill='none'/>

    <path id='orbit' d='M0 88 C 180 30, 390 132, 600 80 C 810 26, 1020 132, 1200 74'
      stroke='url(%23trail)' stroke-width='5.2' fill='none'>
      <animate attributeName='d' dur='6s' repeatCount='indefinite'
        values='
          M0 88 C 180 30, 390 132, 600 80 C 810 26, 1020 132, 1200 74;
          M0 78 C 180 132, 390 30, 600 86 C 810 132, 1020 30, 1200 84;
          M0 88 C 180 30, 390 132, 600 80 C 810 26, 1020 132, 1200 74
        '/>
    </path>

    <circle r='5.5' fill='%23ffffff' opacity='0.9'>
      <animateMotion dur='3.8s' repeatCount='indefinite'>
        <mpath href='%23orbit'/>
      </animateMotion>
    </circle>

    <circle r='3.8' fill='%23d2f4ff' opacity='0.75'>
      <animateMotion dur='6.1s' repeatCount='indefinite' begin='-1.5s'>
        <mpath href='%23orbit'/>
      </animateMotion>
    </circle>
  </svg>"
/>

</div>
