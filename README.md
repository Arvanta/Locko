# Locko 🔐

**Locko** is a modern, lightweight, and cryptographically secure password generator that runs entirely in your browser. Designed with privacy and security first, all generation algorithms execute locally—no servers, no external dependencies, and no tracking.

![alt text](https://github.com/Arvanta/Locko/blob/main/Locko_ScreenShot.png?raw=true)

---

## ✨ Features

- **🔒 100% Client-Side & Offline:** Built with pure HTML5, CSS3, and modern JavaScript. Your passwords never leave your browser.
- **🛡️ Cryptographically Secure:** Uses the browser's native `window.crypto.getRandomValues()` API instead of `Math.random()`.
- **⚙️ Multiple Generation Modes:**
  - **All Characters:** Full randomness with complete character set control.
  - **Easy to Read:** Excludes similar & confusing characters (`1`, `l`, `I`, `0`, `O`).
  - **Easy to Say:** Generates pronounceable password patterns (alternating vowels & consonants).
- **🔀 Unique Characters Option:** Prevent duplicate characters within a single password.
- **📊 Real-time Strength Meter:** Instant visual indicators (`Weak`, `Medium`, `Strong`, `Very Strong`) based on security entropy.
- **🌙 Dark / Light Themes:** Sleek, responsive design that adapts smoothly to your preferred theme.
- **📋 Smart Session History:** Keeps track of your **last 5 copied passwords** using `sessionStorage` (cleared automatically when the tab closes).

---

## 🚀 Quick Start

Since **Locko** is a single-file application with zero external dependencies, getting started is completely effortless:

1. **Download the File:**
   Download the **`Locko.html`** file from this repository to your local computer.
2. **Run in Browser:**
   Double-click **`Locko.html`** to open and run it directly in any modern web browser (Chrome, Firefox, Edge, Safari, Brave).

No installation, no build process, and no internet connection required!
