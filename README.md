# 🖼️ CSS Animated Image Gallery

This project showcases a **three-section animated image gallery** built using only **HTML** and **CSS**. Each section demonstrates a unique animation technique applied to a set of 4 images — making it a great visual and educational example of using `@keyframes` and CSS animation properties.

---

## 📁 Project Overview

The HTML file contains **three main `<section>`s**, each styled and animated differently using the provided `Gallery_Sim.css` file:

### 🎯 Section Highlights

#### 🔁 **Feature 1: Horizontal Sliding Image**
- A single image (`#aa`) moves horizontally from left to right.
- Uses the `@keyframes move` animation.
- Animation loops infinitely with `alternate` direction.

#### 🎞️ **Feature 2: Fading Image Slideshow**
- A sequence of 3 images fades in and out, one at a time.
- Smooth opacity transitions using `@keyframes fade`.
- Each image appears for 3 seconds in a 9-second loop.

#### 📽️ **Feature 3: Center Highlight Carousel**
- 3 images rotate through the center, where the focused image becomes larger and more opaque.
- Simulates a 3D carousel effect using `@keyframes slide`.
- Each image takes a turn being in focus while the others fade back.

---

## 🧩 Technologies Used

- **HTML5** – Structure of the 3 gallery sections
- **CSS3** – All animations and layout
  - Flexbox for alignment
  - `@keyframes` for motion
  - `opacity`, `transform`, `z-index` transitions

---

## 📂 File Structure

```
📁 animated-gallery/
├── Gallery_Sim.html       # Main HTML file with 3 sections
├── Gallery_Sim.css        # CSS animation for each feature
├── /images/               # Folder containing images used in the gallery
└── README.md              # This file
```

---

## 🖥️ How to Run

1. Clone or download the repository.
2. Make sure your images are placed correctly in the `/images/` folder and linked properly in the HTML.
3. Open `Gallery_Sim.html` in any browser to view all 3 animated gallery sections.

---

## 💡 Customization Tips

- 🔄 **Change timing**: Modify `animation-delay`, `animation-duration`, or `@keyframes` to control speed and flow.
- 🖼️ **Add images**: You can increase image count per section, but you’ll need to adjust the `nth-child` animations accordingly.
- 🎨 **Style**: Easily style each section with borders, filters, or overlays.

---



## 🙌 Acknowledgements

Built to demonstrate pure CSS animation power without any JavaScript. Great for students, portfolio showcases, and interactive design demos.
