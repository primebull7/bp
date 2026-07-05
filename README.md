# 🐂 Prime Bull ($BP)

![Solana](https://img.shields.io/badge/Chain-Solana-14F195?style=flat-square)
![Status](https://img.shields.io/badge/Status-Fair%20Launch-00e676?style=flat-square)
![License](https://img.shields.io/badge/License-Proprietary-lightgrey?style=flat-square)

A fair-launch memecoin landing page for **Prime Bull ($BP)** — built on Solana, launched on [Pump.fun](https://pump.fun). No presale, no team dump, just a bonding curve and a herd ready to run.

**Live demo:** _add your GitHub Pages link here once deployed_

---

## ✨ Features

- Animated hero section with a live-style ticker tape and rising candlestick chart
- Tokenomics, "Why Prime Bull," and 4-step "How to Buy" sections
- Scroll-triggered reveal animations (respects `prefers-reduced-motion`)
- Working contact form via EmailJS — no backend required
- "More Projects" spotlight linking out to other launches
- Fully responsive, mobile-first layout
- Single HTML file — no build step, no dependencies to install

## 🛠 Tech Stack

- HTML5 + vanilla CSS3 (no frameworks)
- Vanilla JavaScript (IntersectionObserver for scroll reveals)
- [EmailJS](https://www.emailjs.com) for the contact form
- Google Fonts — Unbounded, Manrope, Space Mono
- Hosted on GitHub Pages

## 📁 File Structure

```
prime-bull/
├── index.html      # everything — markup, styles, and scripts
├── image.png       # Prime Bull artwork (you add this)
├── suiii.png       # SUIMeme logo for the More Projects link (you add this)
└── README.md
```

## 🚀 Before You Deploy

**1. Add your images**
Drop these two files into the same folder as `index.html`:
- `image.png` — the Prime Bull mascot/logo (used in the nav, hero, and footer)
- `suiii.png` — the SUIMeme logo (used in the More Projects section)

**2. Connect the contact form (EmailJS)**
Search `index.html` for the 🔴 comments near the bottom `<script>` tag and fill in:
- Your EmailJS **Public Key**
- Your EmailJS **Service ID**
- Your EmailJS **Template ID**

Sign up free at [emailjs.com](https://www.emailjs.com) if you haven't already — the full setup steps are written directly above those lines in the code.

**3. Update your links**
Search for the `href="#"` and `href="https://pump.fun"` placeholders (also marked with 🔴) and swap in:
- Your live Pump.fun coin link once $BP is minted
- Your real X (Twitter) and Telegram links

## 🌐 Deploy to GitHub Pages

1. Create a new repository (e.g. `PrimeBull`)
2. Push `index.html`, `image.png`, and `suiii.png` to the `main` branch
3. Go to **Settings → Pages**
4. Under **Source**, select the `main` branch and `/ (root)` folder, then **Save**
5. Your site goes live at:
   `https://<your-username>.github.io/<repo-name>/`

## 🎨 Customization

All colors, fonts, and spacing live in the `:root` CSS variables at the top of the `<style>` block — change a value once and it updates everywhere. Section comments (like `<!-- ===== HERO ===== -->`) mark where each part of the page starts, so you can jump straight to the section you want to edit.

## ⚠️ Disclaimer

$BP (Prime Bull) is a community memecoin created for entertainment and cultural purposes. It has no intrinsic value and no guaranteed financial return. Cryptocurrency carries real risk, including total loss of funds — always do your own research.

## License

Proprietary — built for the Prime Bull ($BP) launch. Not licensed for reuse without permission.
