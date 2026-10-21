# Color Studio

**CSS Gradient & Color Studio** is a free, browser-based tool for web developers. It generates CSS gradients, color palettes, layered box-shadows, CSS variables, and accessible color combinations, with copy-ready code for every tool.

🔗 **Live demo:** https://esnaidinkanakan.github.io/color-studio/

---

## Features

### 🎨 Gradient
- Linear, radial and conic gradients
- Add, remove and reposition color stops
- Angle, shape and center controls
- 8 built-in presets and a shuffle button
- Output includes a solid fallback color and a gradient-text snippet

### 🧩 Palette
- Six harmony modes: analogous, complementary, split complementary, triadic, tetradic, monochrome
- Auto-generated primary scale from 50 to 900
- Contrast table showing each color on white, on dark text, and with its best text color
- Click any swatch to copy its hex value
- Send the palette straight to the Gradient or CSS Variables tool

### 🌫️ Shadow
- Layered `box-shadow` builder (offset, blur, spread, color, opacity, inset)
- Presets: Soft, Layered, Crisp, Glow
- Live preview with adjustable surface color, card color and border radius

### ♿ Contrast
- WCAG 2.2 contrast ratio checker
- Pass/fail results for AA and AAA (normal and large text) and UI components
- One-click fix that changes only the text lightness until it passes AA or AAA

### 🧾 CSS Variables
- Export tokens as **CSS custom properties**, **SCSS**, **Tailwind config** or **JSON**
- Optional prefix (for example `--ui-primary`)
- Includes palette roles, the primary scale, readable "on-" text colors, and the current gradient and shadow

### General
- Light and dark mode that follows your system setting
- Responsive layout for desktop and mobile
- Deep links to each tool: `#gradient`, `#palette`, `#shadow`, `#contrast`, `#variables`
- Remembers the last tool you used
- No frameworks and no build step: a single HTML file with vanilla JavaScript

---

## Project structure

```
color-studio/
├── index.html   # The full app (HTML, CSS and JavaScript)
└── README.md
```

---

## Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/esnaidinkanakan/color-studio.git
   cd color-studio
   ```
2. Open `index.html` in your browser.

You can also serve it with a local server, for example with the VS Code **Live Server** extension or:
```bash
npx serve .
```

---

<p align="center">Designed &amp; built by <strong>Edin</strong></p>
