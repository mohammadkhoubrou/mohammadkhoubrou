<!-- README.md — animated greeting + tiny robot for @mohammadkhoubrou -->
<p align="center">

<!-- Animated SVG: blinking text + small robot circling -->
<svg xmlns="http://www.w3.org/2000/svg"
     width="760" height="140" viewBox="0 0 760 140" role="img" aria-label="Animated greeting">
  <defs>
    <style type="text/css"><![CDATA[
      .greeting { font: 700 32px "Segoe UI", Roboto, Helvetica, Arial, sans-serif; fill:#0f172a; }
      .shadow { font: 700 32px "Segoe UI", Roboto, Helvetica, Arial, sans-serif; fill:#cbd5e1; opacity:0.25; }
      .robot-body { stroke:#0f172a; stroke-width:2; fill:#e6eef8; }
    ]]></style>
  </defs>

  <!-- shadow text -->
  <text x="60" y="60" class="shadow">Hey, How are you today?</text>

  <!-- blinking main text -->
  <text x="60" y="60" class="greeting">
    <tspan>
      Hey, How are you today?
      <animate attributeName="opacity"
               values="0;1;1;0;1"
               dur="2.4s"
               repeatCount="indefinite" />
    </tspan>
  </text>

  <!-- tiny robot group -->
  <g id="robot" transform="translate(0,0)">
    <path id="orbitPath" d="M420,15 a1,1 0 0,1 0,120 a1,1 0 0,1 0,-120" fill="none" stroke="none"/>

    <!-- robot -->
  <g class="robot" transform="translate(420,20)">
      <rect x="-12" y="0" width="24" height="24" rx="4" class="robot-body"/>
      <circle cx="-5" cy="8" r="2" fill="#0f172a"/>
      <circle cx="5" cy="8" r="2" fill="#0f172a"/>
      <rect x="-6" y="14" width="12" height="2" rx="1" fill="#0f172a" />
      <line x1="6" y1="-2" x2="12" y2="-8" stroke="#0f172a" stroke-width="2" stroke-linecap="round"/>
      <circle cx="13" cy="-9" r="1.8" fill="#f97316"/>
      <animateTransform attributeName="transform"
                        type="rotate"
                        values="-8 0 0; 8 0 0; -8 0 0"
                        dur="1.6s"
                        repeatCount="indefinite"/>
  </g>

  <!-- robot motion -->
  <animateMotion xlink:href="#robot"
                   dur="6s"
                   repeatCount="indefinite"
                   rotate="auto">
      <mpath xlink:href="#orbitPath"/>
    </animateMotion>
  </g>
</svg>

</p>

---

## 👋 Hey there, I'm [@mohammadkhoubrou](https://github.com/mohammadkhoubrou)

Hi — I'm **Mohammad Khoubrou**!  
I’m a developer who enjoys experimenting with ideas, learning new technologies, and bringing a creative touch to everything I build.  
Here’s a bit more about me:

- 🔭 I’m currently working on: *your current project or focus*
- 🌱 I’m learning: *tools or technologies you're exploring*
- 👯 I’m looking to collaborate on: *interesting open-source or creative projects*
- 💬 Ask me about: *your specialties or favorite topics*
- 📫 How to reach me: *your email / social links*
- ⚡ Fun fact: *add something fun or personal here!*

---

<p align="center">
  <sub>✨ Crafted with a dash of code and creativity by <a href="https://github.com/mohammadkhoubrou">@mohammadkhoubrou</a> ✨</sub>
</p>
