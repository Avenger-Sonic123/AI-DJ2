# AI DJ 2 — PoseNet Setup

A setup-stage experiment for gesture-based song selection.

**Repository created:** 2022-11-22  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2022-11-22

## Features and implementation

- Song preloading.
- Webcam canvas.
- Wrist confidence variables.
- Model-loaded callback.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, p5.js, p5.sound, ml5.js, PoseNet.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`style.css`](style.css) | Page styling |

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/AI-DJ2.git
cd AI-DJ2
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Inspect the model and audio setup after granting camera permission.

## Current status and limitations

The registered pose callback is missing, and song switching is not implemented.

## Related project snapshots

Other repositories in this project family:
- [AI_DJ_Project1](https://github.com/Avenger-Sonic123/AI_DJ_Project1) — repository created 2022-10-26
- [AI-DJ-WebApp2](https://github.com/Avenger-Sonic123/AI-DJ-WebApp2) — repository created 2022-11-06
- [try2forAI-DJ-App](https://github.com/Avenger-Sonic123/try2forAI-DJ-App) — repository created 2022-11-06
- [AI-DJ-Webapp-Project](https://github.com/Avenger-Sonic123/AI-DJ-Webapp-Project) — repository created 2022-11-24

---

Source reference: [`a53dfcf3`](https://github.com/Avenger-Sonic123/AI-DJ2/tree/a53dfcf38284fdac98ae54012a51a1c762b8c47e) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
