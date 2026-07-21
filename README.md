🤖Clickbait Deflater (AI Chrome Extension)

An AI-powered browser extension that dynamically translates sensationalized, clickbait YouTube titles into boring, factual truth in real-time.

Whenever a user hovers over a YouTube thumbnail, this extension intercepts the DOM, securely queries Meta's Llama 3 model via the Groq API, and injects a factual, un-hyped summary directly into the webpage—all while drawing a real-time glitch animation on the extension icon using an invisible HTML5 canvas.

🛠️ Tech Stack & Architecture

Core Language: Vanilla JavaScript (ES6+)

Architecture: Chrome Extension API (Manifest V3) with background Service Workers.

AI Integration: Groq API (Meta Llama-3.1-8b-instant model) for sub-second, lightning-fast inference.

DOM Manipulation: Complex, real-time JavaScript targeting dynamically loading, single-page application (SPA) web grids.

Graphics: HTML5 OffscreenCanvas for real-time, logic-driven icon animation outside the main thread.

Styling: Custom CSS3 with hardware-accelerated filters (blur, contrast, saturate) and CSS variables.

🛒 Where is the "Add to Chrome" button?

To officially publish an extension for a 1-click install, Google requires a one-time $5.00 Developer Registration Fee.

While $5 is a reasonable price for global distribution,But My currently budget is exactly $0.00 🥲

Therefore, rather than asking you to download zip files and manually load unpacked developer environments, I have provided high-definition visual proof below that this architecture works flawlessly.

📸 Proof of Concept (GIF)



<img src="demo.gif" width="400" alt="Deflater Extension Demo" />


