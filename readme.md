# Prismatic — Real-Time Glass & Iridescence in Three.js

A small WebGL playground exploring physically-based transmissive materials — real glass refraction, iridescent thin-film coatings, and HDR environment lighting, all rendered in real time in the browser.

https://github.com/user-attachments/assets/a2606d11-d1c6-45eb-ac9f-de78af1b6b4d

https://github.com/user-attachments/assets/577ab1be-5749-4654-8f3c-e580e45585de
<!-- Replace with your actual demo GIF/video thumbnail, or embed a link below -->

---

## ✨ What it does

- Renders physically accurate **transmissive glass** (`MeshPhysicalMaterial` with `transmission`, `ior`, and `thickness`) so light bends and passes through geometry like real glass
- Adds **iridescent thin-film coatings** for that soap-bubble / oil-slick color shift as the camera moves
- Lights the entire scene with a real **HDR environment map** for physically grounded reflections and refractions
- Live, drag-and-orbit camera control
- A debug panel (`lil-gui`) to tweak transmission, IOR, thickness, metalness, and roughness in real time and see the material react instantly

## 🛠️ Built with

- [Three.js](https://threejs.org/) — WebGL rendering
- `MeshPhysicalMaterial` — PBR glass/iridescence shading
- `RGBELoader` — HDR environment map loading
- `OrbitControls` — camera interaction
- [lil-gui](https://lil-gui.georgealways.com/) — real-time debug controls

## 🚀 Run it locally

```bash
git clone https://github.com/Ayush-7275/prismatic.git
cd prismatic
npm install
npm run dev
```

Then open the local server URL shown in your terminal.

## 🎛️ Play with it

Once running, use the debug panel in the top-right corner to adjust:
- **Transmission** — how "see-through" the material is
- **IOR** — index of refraction (how much light bends passing through)
- **Thickness** — perceived material depth for refraction
- **Metalness / Roughness** — surface finish

Drag to orbit the camera around the sphere, plane, and torus.

## 📌 Notes

This project was built while deepening my understanding of physically-based rendering and creative frontend graphics in Three.js.

## 📄 License

MIT
