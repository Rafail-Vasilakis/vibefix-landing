# 🛡️ VibeFix — The Self-Healing DevOps Engine for AI Builders

> **You built an app with AI. What happens when it breaks?**  
> VibeFix catches the crash, spins up an isolated sandbox, tests the fix, and opens a 1-click GitHub PR.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Cloudflare Pages](https://img.shields.io/badge/Deployed%20with-Cloudflare%20Pages-f38020.svg)](https://pages.cloudflare.com)
[![Product Hunt](https://img.shields.io/badge/Product%20Hunt-Featured-da552f.svg)](https://www.producthunt.com)

---

## 🌟 Interactive Features
- **Live "Break This App" Simulator:** An embedded interactive mock SaaS checkout that crashes on click (`TypeError: Cannot read property of undefined`), triggers autonomous AST repair, and verifies the patch live.
- **Vibe App Vulnerability Scanner:** Instant diagnostic tool scanning web apps for common AI-generated flaws (missing Error Boundaries, unprotected billing state).
- **Security & Zero-Leak Architecture:** Client-side secret scrubbing, isolated disposable sandboxes, zero database access, and 100% human-in-the-loop approvals.
- **Web Audio Haptics:** Micro-interactions powered by Web Audio API synthesizers for real-time auditory feedback.
- **Universal Waitlist Engine:** Integrated lead capture engine with local storage and priority rank badge.

---

## 🚀 Quick Start Locally

Clone this repo and open `index.html` directly in your browser, or serve it with Python/Node:

```bash
# Clone repository
git clone https://github.com/Rafail-Vasilakis/vibefix-landing.git
cd vibefix-landing

# Serve locally
python -m http.server 8000
```
Then visit `http://localhost:8000`.

---

## ☁️ Deployment to Cloudflare Pages

1. Log in to your [Cloudflare Dashboard](https://dash.cloudflare.com).
2. Go to **Workers & Pages** $\rightarrow$ **Create Application** $\rightarrow$ **Pages** $\rightarrow$ **Connect to Git**.
3. Select `Rafail-Vasilakis/vibefix-landing`.
4. Build settings:
   - **Framework preset:** `None`
   - **Build command:** *(leave empty)*
   - **Build output directory:** `.` (root)
5. Click **Save and Deploy**. Your site will be live at `https://vibefix-landing.pages.dev` in ~10 seconds!

---

## 📄 License
MIT © 2026 VibeFix Team.
