# 📄 Responsive Web Resume & PDF Template

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive](https://img.shields.io/badge/Design-Responsive-brightgreen?style=flat)](#features)
[![Print Friendly](https://img.shields.io/badge/Print-PDF%20Optimized-blue?style=flat)](#-exporting-to-pdf)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-informational?style=flat&logo=github)](https://pages.github.com/)

A modern, clean, and high-performance web-based resume template designed for **Flutter Developers** and software engineers. Built entirely with vanilla HTML5 and CSS3, it offers pixel-perfect responsiveness across desktop, tablet, and mobile devices, along with dedicated print stylesheets for instant one-click PDF export.

---

## 📑 Table of Contents

- [Features](#-features)
- [Project Structure & Variants](#-project-structure--variants)
- [Quick Start / Local Preview](#-quick-start--local-preview)
- [Exporting to PDF](#-exporting-to-pdf)
- [Deployment (GitHub Pages)](#-deployment-github-pages)
- [Customization Guide](#-customization-guide)
- [About the Author](#-about-the-author)
- [License](#-license)

---

## ✨ Features

- **⚡ Ultra-Lightweight & Fast**: Pure HTML & CSS with zero frameworks, external dependencies, or build tools required.
- **📱 Fully Responsive**: Fluid multi-column layout on desktop that gracefully collapses to single-column on tablets and smartphones.
- **🖨️ Print & PDF Ready**: Carefully crafted `@media print` rules ensure page breaks, typography, margins, and colors print cleanly to A4/Letter size without awkward splits or unwanted UI elements.
- **📥 One-Click PDF Export**: Built-in floating action button invoking `window.print()` for instant saving as PDF.
- **🎯 Semantic & ATS-Friendly**: Structured semantic HTML headings (`<h1>`-`<h4>`), lists, and sections to maximize readability for applicant tracking systems and search engines.
- **🎨 Multiple Layout Variants**: Included variations offering different typography spacing, density, and formatting options.

---

## 📂 Project Structure & Variants

```text
resume/
├── index.html        # Main standard resume template (balanced layout + PDF button)
├── index3.html       # Condensed/compact variation (tight vertical spacing)
├── index4.html       # Spacious variation (larger typography & relaxed padding)
└── README.md         # Project documentation
```

### Resume Sections Included:
1. **Header & Contact Info**: Name, title, phone, email, LinkedIn, GitHub, portfolio, and location.
2. **Professional Summary**: Highlights of production experience, scale, and performance impact.
3. **Technical Skills Grid**: Categorized overview (Mobile Dev, State Management, Architecture, Backend & APIs, Firebase, Databases, Payments, DevOps, and Tooling).
4. **Professional Experience**: Detailed roles, duration, achievements, and key project breakdowns (e.g., Kookease, EasyLife, Impetus, Oasis Floral, QiSpine, Go2MkT, Mitra Fintech).
5. **Education**: University degrees, institutions, and scores.
6. **Certifications**: Relevant technical course certifications and bootcamps.
7. **Key Achievements**: Quantifiable metric-driven career highlights.
8. **Soft Skills & Languages**: Tagged team and interpersonal skills, plus spoken languages.

---

## 🚀 Quick Start / Local Preview

Because this project is built with static HTML and CSS, you do not need to install `npm` packages or set up a build pipeline.

### Option 1: Open Directly in Browser
Simply double-click `index.html` or run:
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### Option 2: Run with a Local Development Server
For hot reloading or mobile device testing on your local network:

```bash
# Python 3
python3 -m http.server 8000

# or using npx serve
npx serve .
```
Then navigate to `http://localhost:8000` in your web browser.

---

## 🖨️ Exporting to PDF

To generate a clean, professional PDF:

1. Open `index.html` in any Chromium-based browser (Chrome, Edge, Brave) or Safari / Firefox.
2. Click the floating **"📥 Download PDF"** button in the bottom right corner (or press `Ctrl + P` / `Cmd + P`).
3. In the print dialog, configure the following settings:
   - **Destination**: `Save as PDF`
   - **Paper size**: `A4` (or `Letter`)
   - **Margins**: `Default` (or `Minimum`)
   - **Options**: Enable **"Background graphics"** *(ensures headers and category accents render with full color)*
   - **Headers and Footers**: Uncheck *(removes date, page URL, and browser titles)*
4. Click **Save**.

---

## 🌐 Deployment (GitHub Pages)

Host this resume for free on GitHub Pages:

1. Push your repository to GitHub (`main` branch).
2. Go to your repository on GitHub: `https://github.com/Jaat0050/resume`.
3. Click **Settings** > **Pages** (in the left sidebar).
4. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
5. Your live resume will be accessible at:
   ```
   https://Jaat0050.github.io/resume/
   ```

---

## 🛠️ Customization Guide

You can easily adapt this resume for your own background:

### 1. Update Contact Information & Links
In `index.html` (inside `<div class="header">`):
```html
<h1>YOUR NAME</h1>
<div class="title">Your Professional Title</div>
<div class="contact-info">
    <span>📞 +1 (555) 000-0000</span>
    <a href="mailto:your.email@example.com">📧 your.email@example.com</a>
    <a href="https://linkedin.com/in/your-profile" target="_blank">🔗 LinkedIn</a>
    <a href="https://github.com/your-handle" target="_blank">💻 GitHub</a>
</div>
```

### 2. Change the Theme Accent Color
To change the primary color scheme (default is deep blue to cyan gradient), search and replace the hex codes in `<style>`:
- **Header Gradient**: `linear-gradient(135deg, #0066cc 0%, #00bfff 100%)`
- **Section Headers & Accents**: `#0066cc`
- **Skill Card Background**: `#f0f8ff`

### 3. Add or Remove Sections
Each section is modularly wrapped with `<div class="section">...</div>`. You can duplicate or reorder sections (e.g., adding Publications, Awards, or Volunteer Work) without breaking the layout.

---

## 👤 About the Author

**Arjun Rana** — Senior Flutter Developer
- 🌐 **Portfolio**: [arjun-rana-portfolio.netlify.app](https://arjun-rana-portfolio.netlify.app/)
- 💼 **LinkedIn**: [linkedin.com/in/arjun-rana-738503194](https://linkedin.com/in/arjun-rana-738503194/)
- 💻 **GitHub**: [@Jaat0050](https://github.com/Jaat0050)
- 📧 **Email**: [rana.arjun62000@gmail.com](mailto:rana.arjun62000@gmail.com)

---

## 📜 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT). Feel free to fork, customize, and use it for your personal resume or portfolio!
