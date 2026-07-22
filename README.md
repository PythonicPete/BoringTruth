<div align="center">

# 🤖 Clickbait Deflater
**Make YouTube boring (and honest) again.**

[![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)]()
[![AI Powered](https://img.shields.io/badge/AI-Groq%20%7C%20Llama%203-F6851B?style=for-the-badge&logo=meta&logoColor=white)]()
[![Manifest V3](https://img.shields.io/badge/Manifest-V3-success?style=for-the-badge)]()

*An AI-powered browser extension that dynamically translates sensationalized, clickbait YouTube titles into boring, factual truth in real-time.*

</div>

---

## ✨ How It Works

No more **"YOU WON'T BELIEVE WHAT HAPPENED!"** 
Whenever you hover over a YouTube thumbnail, Clickbait Deflater silently goes to work:

1. **Intercepts** the DOM on YouTube's dynamically loading grid.
2. **Queries** Meta's Llama 3 model securely via the lightning-fast Groq API.
3. **Injects** a factual, un-hyped summary directly into the page.
4. **Animates** the extension icon in real-time using an invisible HTML5 canvas glitch effect.

All of this happens in less than a second. ⚡

---

## 🛠️ Tech Stack & Architecture

This project is built for speed, relying on modern web APIs and avoiding bloated frontend frameworks.

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Core Engine** | Vanilla JS (ES6+) | Pure JavaScript for maximum performance and zero dependency overhead. |
| **Architecture** | Manifest V3 | Modern Chrome Extension API utilizing background Service Workers. |
| **AI Inference** | Groq API & Llama-3.1-8b | Sub-second inference latency for real-time title translations. |
| **DOM Magic** | MutationObservers | Complex, real-time targeting for dynamically loading SPA web grids. |
| **Graphics** | HTML5 OffscreenCanvas | Real-time, logic-driven icon animation outside the main thread. |
| **Styling** | Custom CSS3 | Hardware-accelerated filters (`blur`, `contrast`, `saturate`) and CSS variables. |

---

## 🛒 Where is the "Add to Chrome" button?

To officially publish an extension to the Chrome Web Store for a 1-click install, Google requires a one-time **$5.00 Developer Registration Fee**.

While $5 is a totally reasonable price for global distribution... my current development budget is exactly **$0.00** 🥲.

Therefore, rather than asking you to download ZIP files, toggle Chrome's "Developer Mode," and manually load unpacked environments, I have provided high-definition visual proof below that this architecture works flawlessly.

---

## 📸 Visual Proof

> **[ ⚠️ Note to reader: Insert your GIF or video demonstration here ]**

<div align="center">
  
  <img src="https://via.placeholder.com/800x450.png?text=Add+Your+GIF+Here" alt="Demo of Clickbait Deflater in action" width="800"/>

  *Hovering over a title instantly replaces the hype with the facts.*
</div>
📸 Proof of Concept (GIF)



<img src="demo.gif" width="400" alt="Deflater Extension Demo" />                           <img src="demo2.gif" width="400" alt="Deflater Extension Demo" />


