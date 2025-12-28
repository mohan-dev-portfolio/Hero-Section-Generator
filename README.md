# HeroForge | Portfolio Hero Generator

**HeroForge** is a lightweight, frontend-only workbench designed for developers to prototype and generate modern, aesthetic hero sections for their portfolios instantly. Built entirely with **Vanilla JavaScript** and **CSS variables**, it requires no build steps, frameworks, or external dependencies.

---

## 🚀 Features

- **Live Preview**  
  Real-time rendering of changes as you type.

- **Multiple Variants**
  - **Protocol** — Grid-based, minimalist, and technical.
  - **Lumina** — Modern mesh gradients with bold typography.
  - **Narrative** — Story-driven layout with elegant typography.

- **Production-Ready Code**  
  Generates clean, semantic HTML and scoped CSS using `clamp()` for fluid responsiveness.

- **Dark Mode Aesthetic**  
  A premium, developer-focused UI with glassmorphism and subtle neon accents.

- **Export Options**  
  One-click copy to clipboard or download as a standalone `.html` file.

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure  
- **CSS3** — Custom properties (CSS variables), Flexbox/Grid, and complex animations  
- **JavaScript (ES6+)** — State management, DOM manipulation, and template literal rendering  

---

## 🏁 Getting Started

HeroForge is a static web application. No installation or build step is required.

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

Clone the repository:

```bash
git clone https://github.com/mohan-dev-portfolio/Hero-Section-Generator.git
```

Navigate to the project directory:

```bash
cd Hero-Section-Generator
```

Run the app:

- Simply open `index.html` in your preferred browser.

> **Optional:** For the best development experience, use a local server extension (such as Live Server for VS Code) to avoid potential CORS issues with local file protocols. The app is designed to work without one.

---

## 📖 Usage

1. **Enter Details**  
   Input your name, role, and an optional subheading in the sidebar.

2. **Select Variant**  
   Choose between **Protocol**, **Lumina**, or **Narrative** styles.

3. **Generate**  
   Click **Generate Hero** to update the preview.  
   (Previews may also update automatically as you type.)

4. **Export**
   - **View Code** — Inspect the generated HTML and CSS.
   - **Copy** — Paste the code directly into your portfolio.
   - **Download** — Save the hero as a standalone HTML file.

---

## 📂 Project Structure

```text
hero-forge/
│
├── index.html      # Main application file (UI, logic, and styles combined for portability)
├── favicon.png     # App icon
└── README.md       # Documentation
```

> **Note:** The project is intentionally contained within `index.html` for maximum portability.  
> For larger or production deployments, it can be split into `script.js` and `style.css`.

---

## 🎨 Customization

To add your own hero templates, locate the `TEMPLATES` object in the JavaScript section of `index.html`.  
Each key represents a variant and returns a template literal containing scoped HTML and CSS.

```js
const TEMPLATES = {
  myNewVariant: (data) => `
    <style>
      /* Your scoped CSS */
    </style>
    <section class="hero">
      <h1>${data.name}</h1>
    </section>
  `,
  // ...existing templates
};
```

---

## 🤝 Contributing

Contributions are welcome and encouraged.

1. Fork the project  
2. Create your feature branch  
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add AmazingFeature"
   ```
4. Push to the branch  
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**.  
See the `LICENSE` file for more information.

---

<div align="center">
  Created by <strong>Mohan Prasath</strong><br />
  <a href="https://bit.ly/mohan-dev">Portfolio</a> •
  <a href="https://github.com/mohan-dev-portfolio">GitHub</a> •
  <a href="https://www.linkedin.com/in/mohanprasath21">LinkedIn</a>
</div>
