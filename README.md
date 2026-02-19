# 🛠️ Parametric Soft Jaw Vice Generator

** 3D printable softjaw vice covers made primarly for woodworking vices ** this tool is a browser-based utility designed to bridge the gap between "measuring the old vise in the garage" and "generating a 3D-printable or machine-ready file." It generates dynamic blueprints, handles unit conversions, and exports 3D geometry instantly.

---

### 🚀 Core Features



| Feature | Description |
| :--- | :--- |
| **STL 3D Export** | Powered by `Three.js` to generate **1:1 scale files** ready for 3D printing or CAM software. |
| **Cloud Vault** | A global Firebase repository to save/load specs for major brands (Kurt, Sjobergs, Wilton). |
| **Ink-Saver Print** | A dedicated CSS mode that flips the high-contrast UI to **clean black-on-white** for paper templates. |
| **Manual Precision** | High-fidelity decimal support for both **Metric (mm)** and **Imperial (in)** workflows. |

---

### 🛠️ Tech Stack

* **Frontend:** Vanilla JS / HTML5 / CSS3 (Zero-dependency architecture).
* **Graphics:** `SVG` for 2D Blueprints + `Three.js` for 3D Mesh Generation.
* **Backend:** `Firebase` Realtime Database for the global Vault.
* **Licensing:** MIT.

---

### 🤝 How to Contribute

> "We want this to be the Wikipedia of Vise Jaws." 

This project was **voice-coded** via AI-human collaboration, and we want to keep that spirit of rapid iteration alive. You can help evolve the lab by:

* **Adding Presets:** Submit verified measurements for common workshop vise brands.
* **Refining STL Logic:** Help us implement counter-sunk holes or textured "grip" faces.
* **UI/UX Hardening:** Help make the terminal interface "shop-proof" for tablet users.

---

### 📜 License

This project is licensed under the **MIT License**.
You are free to **fork it, break it, and build something better.**
