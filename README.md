# PixelVault — Premium Photo Downloads

PixelVault is a high-end, responsive, single-page static website featuring a curated catalog of breathtaking nature and landscape photography. It allows visitors to explore stunning images, view detailed camera metadata (EXIF details), and download them in ultra-high resolution individually or in bulk.

The project is built entirely with vanilla technologies, prioritizing speed, accessibility, clean aesthetics, and fluid user interactions.

---

## ✨ Features

- **Modern Visual Design:** Sleek dark-mode aesthetic utilizing glassmorphism, smooth gradients, ambient neon glow effects, and a background grid.
- **Micro-Animations:** Fluid scroll-triggered entrance animations using the browser's native `IntersectionObserver` API.
- **Detailed Photo Cards:** Clean grids that showcase metadata (resolution, category, file size) and allow users to toggle detailed camera EXIF data (Camera body, location, lens exposure settings, and exact dimensions).
- **Instant Individual Downloads:** Standard HTML5 `download` attribute integrations for instant high-resolution asset acquisition.
- **Staggered Bulk Download:** A "Download All" mechanism that fetches all photographs in sequence with an interactive dashboard displaying size statistics.
- **Interactive FAQ Accordion:** Interactive, smooth collapsible FAQs addressing common inquiries about the platform and image usage.
- **Fully Responsive:** Meticulously designed media queries ensuring a premium layout across desktop, tablet, and mobile browsers.

---

## 🛠️ Tech Stack

- **Core Structure:** Semantic HTML5
- **Styling & Aesthetics:** Vanilla CSS3 (CSS Variables, Flexbox/Grid, Backdrop Filters, Keyframe Animations)
- **Logic & Interactions:** Pure Vanilla JavaScript (No heavy frameworks or external JS dependencies)
- **Assets:** High-resolution photographs sourced from Unsplash and custom SVG icons

---

## 📁 Directory Structure

```text
Static-website/
├── index.html       # The main entrypoint (markup & interaction logic)
├── style.css        # Core stylesheet containing the design system & responsive rules
├── README.md        # Project documentation and details
└── images/          # Assets folder containing high-resolution photograph files
    ├── mountain-landscape.jpg
    ├── ocean-coastline.jpg
    ├── enchanted-forest.jpg
    └── aurora-borealis.jpg
```

---

## 📸 Photographed Assets

| Photo Name | Location | Camera | Exposure Settings | File Size |
| :--- | :--- | :--- | :--- | :--- |
| **Mountain Majesty** | Swiss Alps | Sony α7R IV | f/8.0 · 1/250s · ISO 100 | 525 KB |
| **Ocean Paradise** | Amalfi Coast, Italy | Canon EOS R5 | f/4.0 · 1/800s · ISO 200 | 464 KB |
| **Enchanted Forest** | Redwood National Park, USA | Nikon Z7 II | f/11 · 0.5s · ISO 64 | 768 KB |
| **Aurora Borealis** | Tromsø, Norway | Fujifilm GFX 100S | f/2.8 · 8.0s · ISO 1600 | 805 KB |

---

## 🚀 How to Run Locally

Since this project consists of standard static files, you can launch it in a few different ways:

### Method 1: Direct File Opening
Double-click `index.html` or drag and drop it into any modern web browser.

### Method 2: Python Local Server
If you have Python installed, navigate to the project directory in your terminal and run:
```bash
python -m http.server 8000
```
Then open your browser and navigate to `http://localhost:8000`.

### Method 3: Node.js (Live Server / Serve)
If you have Node.js installed, you can serve the directory dynamically:
```bash
npx serve .
```
Then navigate to the URL provided in the terminal (usually `http://localhost:3000` or `http://localhost:5000`).

---

## 📄 Licensing

All images provided in PixelVault are licensed under **Creative Commons CC0 (Public Domain)**. They are free to download, modify, distribute, and use for both personal and commercial projects without requiring attribution or royalty payments.
