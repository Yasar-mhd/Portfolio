# 🖥️ Yasar Mahmood — Developer Portfolio

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![JetBrains Mono](https://img.shields.io/badge/Font-JetBrains_Mono-000000?style=for-the-badge&logo=jetbrains&logoColor=white)

**A dark, terminal-aesthetic developer portfolio built with pure HTML, CSS, and JavaScript.**

[🌐 Live View](https://yasar-mhd.vercel.app/) · [📧 Contact](mailto:yasarmahmood7x@gmail.com) · [💼 LinkedIn](https://www.linkedin.com/in/yasar-mahmood007/)

</div>

---

## ✦ Preview

> Dark terminal aesthetic with cyan/green syntax-highlight accents, blinking cursor, and scan-line overlay.

```
yasar@localhost ~/dev $ whoami --full
```

---

## 🗂️ File Structure

```
portfolio/
├── index.html      # Markup — all sections and content
├── style.css       # All styles, variables, animations, responsive
├── script.js       # Cursor, nav scroll, scroll-reveal logic
└── README.md       # You are here
```

---

## ✨ Features

| Feature | Detail |
|---|---|
| 🖱️ **Custom cursor** | Blinking caret cursor + physics-lagged ring tracker |
| 🌐 **Terminal hero** | Prompt line with `whoami` command and inline Java code block |
| 📂 **About.java** | Bio written as real Java class with syntax highlighting |
| 📊 **Skills table** | Color-coded by Proficient / Learning / Up Next with progress bars |
| 🖥️ **Terminal contact** | `cat contact.txt` output with all links |
| 🔒 **Frosted nav** | Sticky navbar that blurs + frosts on scroll |
| 🎞️ **Scroll reveals** | IntersectionObserver fade-up animations on every section |
| 📱 **Responsive** | Mobile-friendly layout, nav collapses cleanly |
| ⚡ **Zero dependencies** | No frameworks, no build tools, no npm — just open `index.html` |

---

## 🎨 Design System

```css
--bg:      #04060a   /* Deep near-black background      */
--accent:  #00d4ff   /* Cyan — primary highlight        */
--accent2: #00ff9d   /* Green — secondary / status      */
--orange:  #ff6b35   /* Orange — string literals        */
--purple:  #a78bfa   /* Purple — keywords               */
--text:    #e2eaf4   /* Off-white body text             */
```

**Fonts:** `JetBrains Mono` (code/UI) + `Space Grotesk` (headings)

---

## 🚀 Getting Started

No build step required. Clone and open directly in a browser:

```bash
git clone https://github.com/Yasar-mhd/portfolio.git
cd portfolio
open index.html        # macOS
# or
start index.html       # Windows
# or just drag index.html into your browser
```

---

## 🌍 Deployment

### GitHub Pages (recommended — free)

```bash
# 1. Push your code to a repo named:  Yasar-mhd.github.io
git init
git add .
git commit -m "feat: initial portfolio"
git remote add origin https://github.com/Yasar-mhd/Yasar-mhd.github.io.git
git push -u origin main

# 2. Go to repo Settings → Pages → Source: main / root
# 3. Your site is live at: https://yasar-mhd.github.io
```

### Vercel (drag & drop)
1. Go to [vercel.com](https://vercel.com) → "Add New Project" → connect your GitHub repo **or** visit [vercel.com/new](https://vercel.com/new) to drag & drop
2. No build config needed — Vercel auto-detects static HTML
3. Done — live at `https://your-project.vercel.app` in under 30 seconds

---

## 🛠️ Customisation

All content lives in `index.html`. Key areas to update:

```
Line ~50   → Nav logo text
Line ~60   → Hero terminal prompt
Line ~75   → Hero name
Line ~90   → Hero code block description
Line ~130  → About.java bio content
Line ~165  → Stack table rows (add/remove skills)
Line ~210  → Stats panel values
Line ~240  → Contact terminal output
Line ~270  → Social links (GitHub, LinkedIn, Twitter, Email)
```

To change accent colours, edit the CSS variables in `style.css`:
```css
:root {
  --accent:  #00d4ff;   /* change to any colour */
  --accent2: #00ff9d;
}
```

---

## 📬 Contact

| Platform | Link |
|---|---|
| 📧 Email | [yasarmahmood7x@gmail.com](mailto:yasarmahmood7x@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/yasar-mahmood007](https://www.linkedin.com/in/yasar-mahmood007/) |
| 🐙 GitHub | [github.com/Yasar-mhd](https://github.com/Yasar-mhd) |

---

<div align="center">

Built with Love, By Yasar.

</div>
