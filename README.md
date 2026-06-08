# 💻 System Override | Cyber Aesthetic UI

A premium, purely CSS-driven UI component featuring a hacker-inspired glassmorphism code window floating over a moving 3D cyber grid. Perfect for portfolios, 404 pages, or tech-focused landing pages.

## ✨ Features

* **Authentic Cyberpunk Vibe:** Combines a neon ambient glow with a high-contrast dark mode palette.
* **3D Perspective Grid:** A CSS-only animated floor grid that creates a sense of depth (`perspective` and `rotateX`).
* **Matrix Rain Effect:** Multi-layered, looping digital "rain" patterns running in the background.
* **Premium Glassmorphism:** The central code window uses `backdrop-filter: blur`, subtle gradients, and custom drop shadows to create a realistic frosted glass effect.
* **Staggered Typing Animation:** Code lines "boot up" sequentially using staggered CSS animation delays to simulate a live terminal.
* **Zero Dependencies:** 100% Vanilla HTML and CSS. No JavaScript required.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure with clear class naming.
* **CSS3:** Advanced animations (`@keyframes`), gradients, flexbox layout, and backdrop filters.
* **Font:** [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (Imported via Google Fonts) for authentic developer typography.

## 🚀 How to Use

Simply copy the HTML and CSS into your project. 

If you are using a platform like **Uiverse.io** or CodePen:
1. Paste the content inside the `<body>` tags into the HTML editor.
2. Paste the contents of the `<style>` block into the CSS editor.
3. *Note: Ensure your environment allows background colors on the main container for the glow effects to display properly.*

## 🎨 Customization Guide

This component is built to be easily tweaked. Here are the main areas you can customize in the CSS:

* **Change the Glow Colors:** Find `.ambient-glow` and adjust the `rgba()` values in the `radial-gradient` to change the background aura.
* **Modify the Code Text:** Inside the HTML, locate the `.code-content` div. You can change the text inside the `<span>` tags to display your own custom code snippet.
* **Adjust the Rain Speed:** In the `.rain-pattern` classes, change `animation: rainDrop 2s` to a higher number (like `4s`) to make the rain fall slower.
* **Terminal Colors:** The syntax highlighting uses authentic "One Dark" theme colors. You can change these in the CSS under the `/* Authentic Dev Colors */` section (e.g., `.keyword`, `.variable`, `.function`).

## 📄 License

This project is open-source and free to use in personal or commercial projects.
