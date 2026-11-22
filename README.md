<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:0284c7&height=180&section=header&text=TCP%20Congestion%20Playground&fontColor=ffffff&fontSize=34" alt="TCP Congestion Playground banner"/>
  <br/><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2600&pause=700&center=true&vCenter=true&width=650&lines=Watch+congestion+window+growth;Explore+slow+start+and+avoidance;Inject+a+loss+event+and+compare" alt="Animated title"/>
  <br/><img src="https://img.shields.io/github/license/CyberLoop-dev/tcp-congestion-playground" alt="License"/> <img src="https://img.shields.io/github/languages/top/CyberLoop-dev/tcp-congestion-playground" alt="Language"/> <img src="https://img.shields.io/github/stars/CyberLoop-dev/tcp-congestion-playground" alt="Stars"/> <img src="https://img.shields.io/github/last-commit/CyberLoop-dev/tcp-congestion-playground" alt="Last commit"/>
  <br/><img src="assets/mark.svg" width="210" alt="Congestion curve illustration"/>
</p>

## 🧭 Overview

A deterministic teaching model of TCP congestion-window growth. Step through slow start and congestion avoidance, choose a loss round, and inspect how the simplified sender reacts.

## ✨ Features

- 📈 Live SVG chart of congestion-window size per round.
- 🎚️ Adjustable slow-start threshold and loss round.
- 🧠 Clear phase labels for slow start and congestion avoidance.
- 🔁 Reset and replay the same deterministic scenario.
- 🔒 All simulation runs locally in your browser.

## 🎬 Demo

Run the local app, change the loss round, and press **Next RTT**. The chart and event log update after each simulated round. This repository does not claim a hosted demo.

## 🚀 Quick Start

Requires Node.js 18 or newer.

```bash
npm start
```

Open http://localhost:4173.

## 🧰 Tech Stack

- 🟢 Node.js built-in HTTP server
- 🌐 HTML, CSS, browser JavaScript, and SVG
- 📦 No third-party dependencies

## 🗂️ Folder Structure

```text
tcp-congestion-playground/
├── assets/mark.svg
├── app.js
├── index.html
├── server.js
├── package.json
├── README.md
├── LICENSE
└── .gitignore
```

## 🛣️ Roadmap

- [ ] Add fast-recovery and timeout variants.
- [ ] Compare Reno and Cubic models.
- [ ] Export a simulation trace as CSV.

## 🤝 Contributing

Open an issue with a reproducible scenario or submit a focused pull request. Test locally with `npm start` and keep the model assumptions documented.

## 📄 License

MIT licensed. See [LICENSE](LICENSE).

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0284c7,100:111827&height=105&section=footer" alt="Wave footer"/></p>
