# 💔 Broken Glass Shaped of a Heart

An interactive SVG animation of a heart made of shattered glass shards. Click anywhere to watch the pieces explode outward into chaos — click again to watch them reassemble into a heart, right before your eyes.

Built with pure SVG polygons and animated using [GSAP](https://gsap.com/).

## ✨ Features

- **Shattered glass aesthetic** — the heart is built from dozens of hand-placed SVG polygon shards
- **Click-to-toggle animation** — disperse the shards into random positions/rotations, or pull them back together
- **Dynamic blur** — a Gaussian blur filter intensifies as the glass scatters, adding depth to the effect
- **Smooth easing** — powered by GSAP's `power2` and `back` eases for natural, physical-feeling motion
- **Zero build step** — just plain HTML, CSS, and JavaScript

## 🚀 Getting Started

No installation or build tools required. Simply open the page in a browser:

```bash
# Clone the repository
git clone https://github.com/<your-username>/broken-glass-shaped-of-a-heart.git
cd broken-glass-shaped-of-a-heart

# Open index.html in your browser
```

Or serve it locally with any static server, e.g.:

```bash
npx serve .
```

## 🖱️ Usage

Click anywhere on the page to toggle between the two states:

| State | Behavior |
|---|---|
| **Together** → Click | Shards fly apart, blur increases, hidden text fades in |
| **Dispersed** → Click | Shards return to their original positions to form the heart again |

## 🛠️ Tech Stack

- **SVG** — vector shapes for the glass shards
- **[GSAP](https://gsap.com/)** — animation engine driving the transforms and easing
- **DrawSVGPlugin** — SVG stroke drawing effects
- **Vanilla JavaScript** — no frameworks, no dependencies to install

## 📁 Project Structure

```
.
├── index.html   # SVG markup and CDN script includes
├── script.js    # Animation logic (disperse / reassemble)
└── style.css    # Layout, background, and typography
```

## 📄 License

This project is open source and available for personal and educational use.
