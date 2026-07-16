# Panopticon-AI
An AI exam proctor that watches everything — gaze, lips, and your phone — entirely inside your browser. No backend, no uploads, nothing leaves the tab.

🔗 [Live demo](https://harshitanayan.github.io/Panopticon-AI/)

## Features

- 👁️ Off-screen gaze detection
- 🗣️ Lip-sync talking detection (ignores background noise)
- ✍️ Ghost-writer detection (typing without matching body motion)
- 📱 Real-time phone detection via webcam
- 🪟 Tab-switch / window-minimize tracking
- 📄 Auto-generated PDF report when the session ends

## Tech

MediaPipe · TensorFlow.js (coco-ssd) · Web Audio API · jsPDF — pure HTML/CSS/JS, no framework, no build step.

## Note

This is a personal project showcasing browser-based AI, not certified proctoring software — detection logic runs client-side and is inspectable via DevTools.
