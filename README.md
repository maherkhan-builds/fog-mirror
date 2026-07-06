# ✦ Fog Mirror

Blow on your screen to fog it up — then write on it with your finger, just like a steamy bathroom mirror. ✨

**🔗 Try it live:** https://maherkhan-builds.github.io/fog-mirror/

Part of the **Maher Magic** camera AI series by [Maher Khan](https://digimarketingstudio.com).

## How it works

| | 💻 Desktop | 📱 Mobile |
|---|---|---|
| **Fog it up** | Blow into your mic | Blow into your mic, or tap ☁ fog |
| **Write** | Pinch your fingers in the air (AI hand tracking) | Write directly with your finger |
| **Take a photo** | Make an "L" frame with both hands, or tap 📷 | Tap 📷 |
| **Save / share** | Downloads a PNG | Opens your phone's share sheet |

Plus **undo** and **clear** buttons to start fresh.

## Tech

- Plain HTML/CSS/JavaScript — a single `index.html`, no build step, no backend
- [MediaPipe Hands](https://developers.google.com/mediapipe) for in-air pinch drawing
- Web Audio API for breath detection (high-pass filtered mic input)
- Canvas compositing for the fog + wipe effect

## Run it yourself

Camera and mic need HTTPS (or localhost), so either:

```bash
npx serve .        # then open http://localhost:3000
```

…or fork this repo and turn on GitHub Pages — that's all this site is.

## License

MIT — free to use, remix, and share.
