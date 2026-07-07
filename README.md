<div align="center">

[![Fog Mirror](https://readme-typing-svg.demolab.com?font=Montserrat&weight=800&size=32&duration=3000&pause=800&color=7DD3FC&center=true&vCenter=true&width=700&height=60&lines=✦+Fog+Mirror;Blow+on+Your+Screen.+Watch+It+Fog.;Write+With+Your+Finger+—+In+the+Air;Camera+AI+Magic+✨)](https://maherkhan-builds.github.io/fog-mirror/)

**Blow on your screen to fog it up — then write on it, just like a steamy bathroom mirror**

[![✨ Try It Live](https://img.shields.io/badge/✨_TRY_IT_LIVE-Fog_It_Up-7dd3fc?style=for-the-badge)](https://maherkhan-builds.github.io/fog-mirror/)
[![Built with Claude Code](https://img.shields.io/badge/Built_with-Claude_Code-cc785c?style=for-the-badge)](https://claude.com/claude-code)
[![MediaPipe](https://img.shields.io/badge/AI-MediaPipe_Hands-38e8a5?style=for-the-badge)](https://developers.google.com/mediapipe)

</div>

---

## 🔗 Live App

**▶️ https://maherkhan-builds.github.io/fog-mirror/** — allow camera + mic, then blow.

## 🎯 The Problem

Everyone has drawn a heart on a foggy bathroom mirror. Nobody expects their *phone screen* to do it. Camera AI demos are usually dry tech showcases — hand skeletons and bounding boxes — that don't make anyone smile or hit the share button.

## 💡 The Solution

Fog Mirror turns your camera into a steamy mirror with real physics-feel magic:

- 🌬️ **Blow into your mic** — the screen actually fogs up (breath detection via high-pass-filtered audio)
- ✍️ **Write in the fog** — with your finger on mobile, or by *pinching in the air* on desktop (AI hand tracking)
- 📷 **Frame a photo with your hands** — make an "L" frame with both hands to snap a picture
- 📱 **Save & share** — share sheet on phones, PNG download on desktop
- ↩️ Undo and clear to start fresh

| | 💻 Desktop | 📱 Mobile |
|---|---|---|
| **Fog it up** | Blow into your mic | Blow, or tap ☁ |
| **Write** | Pinch fingers in the air | Finger on screen |
| **Photo** | "L" frame with both hands, or 📷 | Tap 📷 |

## 👥 Who It's For

- **Anyone who wants 30 seconds of delight** — it's built to be shared
- **Educators & speakers** demoing what browser-based camera AI can do
- **Developers** looking for a clean, single-file MediaPipe Hands + Web Audio reference

## 🚀 How to Use

1. Open **https://maherkhan-builds.github.io/fog-mirror/** (camera + mic need HTTPS — GitHub Pages handles that)
2. Allow camera and microphone
3. **Blow.** Then write something in the fog and snap a photo

Run it yourself:

```bash
npx serve .   # then open http://localhost:3000
```

…or fork this repo and turn on GitHub Pages — that's all this site is.

## 🛠️ Tech Stack

- Plain HTML/CSS/JavaScript — a single `index.html`, no build step, no backend
- [MediaPipe Hands](https://developers.google.com/mediapipe) for in-air pinch drawing
- Web Audio API for breath detection (high-pass filtered mic input)
- Canvas compositing for the fog + wipe effect

## 🤖 How It Was Built

Built with **[Claude Code](https://claude.com/claude-code)** (Anthropic) — breath detection, hand-gesture recognition, and fog rendering engineered conversationally in one session.

## 👤 Builder

Built by **[Maher Khan](https://digimarketingstudio.com)** — AI educator, no-code builder & digital marketing strategist.

- 🎓 UCLA Extension Guest Lecturer — ChatGPT, LLMs & Agentic AI
- 🏆 LinkedIn Top Voice, North America — 3 consecutive years
- 🛠️ 28+ AI-powered tools built · 20,000+ professionals trained
- 💼 [LinkedIn](https://www.linkedin.com/in/mahersocialmediastrategistus) · [GitHub](https://github.com/maherkhan-builds) · [Instagram](https://www.instagram.com/social.icm) · [Book a call](https://calendly.com/digitalpoles/let-s-meet-up)

Part of the **Maher Magic** camera AI series. ✨

## 📄 License

MIT — free to use, remix, and share.

<div align="center">

`camera-ai` `mediapipe` `hand-tracking` `computer-vision` `creative-coding` `web-audio-api` `webcam` `interactive-art` `javascript` `claude-code`

</div>
