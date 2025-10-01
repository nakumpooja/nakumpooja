<!--
  README.md for: https://github.com/nakumpooja
  Gradient animated header + clean sections
-->

<!-- ===== Gradient Animated Header (SVG) ===== -->
<p align="center">
  <img alt="Gradient Header" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="900" height="180" viewBox="0 0 900 180">
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop offset="0" stop-color="%23ff0044">
          <animate attributeName="stop-color" values="%23ff0044;%2300ff6a;%23008bff;%23ff0044" dur="6s" repeatCount="indefinite"/>
        </stop>
        <stop offset="0.5" stop-color="%2300ff6a">
          <animate attributeName="stop-color" values="%2300ff6a;%23008bff;%23ff0044;%2300ff6a" dur="6s" repeatCount="indefinite"/>
        </stop>
        <stop offset="1" stop-color="%23008bff">
          <animate attributeName="stop-color" values="%23008bff;%23ff0044;%2300ff6a;%23008bff" dur="6s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>

      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <rect width="100%" height="100%" rx="12" ry="12" fill="%230b0b0b"/>
    <g transform="translate(30,30)">
      <text x="0" y="70" font-family="Segoe UI, Roboto, system-ui, -apple-system, 'Helvetica Neue', Arial" font-size="56" font-weight="700" fill="url(%23g)" filter="url(%23glow)">
        nakumpooja
      </text>
      <text x="0" y="110" font-family="Segoe UI, Roboto, system-ui, -apple-system, 'Helvetica Neue', Arial" font-size="14" fill="%23bdbdbd">
        Crafting clean code • Building elegant web experiences • Always learning
      </text>

      <!-- subtle animated line -->
      <rect x="310" y="2" width="560" height="8" rx="4" fill="url(%23g)">
        <animate attributeName="x" values="310;10;310" dur="8s" repeatCount="indefinite"/>
      </rect>
    </g>
  </svg>' />
</p>

# Hi, I’m **nakumpooja** 👋

> Welcome! I'm a passionate developer who loves building clean UIs, solving problems, and experimenting with colorful design and micro-interactions.

---

## ✨ Overview
This `README` uses an inline SVG header with animated gradients.  
It’s a showcase of how a profile can look lively while staying lightweight and accessible.

---

## 🔧 About Me
- 🔭 Currently working on **front-end UI**, **web apps**, and **creative layouts**  
- 🌱 Learning modern JS frameworks, design systems, and accessibility best practices  
- 💬 Ask me about UI/UX, GitHub workflows, or animation techniques  

---

## 🛠️ Skills
- **Languages**: JavaScript (ES6+), HTML, CSS, TypeScript  
- **Frameworks**: React / Next.js, Vue, or plain HTML/CSS prototypes  
- **Backend**: Node.js, Express, Firebase  
- **Design / UX**: Figma, SVG, Lottie animations  
- **Tools**: Git, GitHub Actions, VS Code  

---

## 🚀 Projects
> _(Replace with your real projects & links)_

- **UI Kit** – A small design system with accessible color usage and animations  
- **Portfolio Website** – Responsive site with smooth transitions and project gallery  
- **Micro-Interactions Library** – JS + CSS utilities for hover/tap animations  

---

## 📫 Contact
- GitHub: [@nakumpooja](https://github.com/nakumpooja)  
- Email: `your-email@example.com` *(replace with real email)*  

---

## 📈 GitHub Stats
You can add dynamic GitHub stats images (requires `github-readme-stats` service):

`![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nakumpooja&layout=compact&hide=Jupyter%20Notebook)`  

`![Stats](https://github-readme-stats.vercel.app/api?username=nakumpooja&show_icons=true&theme=dark)`  

---

## ❤️ How to Personalize
1. Update the **About Me** section with real info  
2. Replace projects with actual repo links  
3. Add a learning checklist (✅) for your growth path  
4. If you prefer, I can generate a version in **dark neon** or **soft pastel gradients**  

---

### License
This template is free to use — adapt it as you like.  
Made with ❤️ and animated gradients.
