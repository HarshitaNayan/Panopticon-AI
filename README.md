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

## Before You Start

- Open the live demo and allow webcam access when prompted.
- Use a well-lit space and keep your face visible to the camera.
- Close other applications that are using your webcam.
- Treat detection alerts as signals to review, not proof of cheating.

## Note

This is a personal project showcasing browser-based AI, not certified proctoring software — detection logic runs client-side and is inspectable via DevTools.

## Troubleshooting

If the webcam does not start, check your browser's camera permissions, close other apps using the camera, and reload the demo.
