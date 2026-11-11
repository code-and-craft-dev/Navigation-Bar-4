# Radial Arc Navigation 🌸

A minimalist, physics-driven floating action button (FAB) that fans out 5 navigation nodes along an upper 180° semi-circular arc using pure trigonometry, shockwave ripple physics, and CSS cross rotation.

## ✨ Features
- 🌸 **Trigonometric Arc Fan-Out**: Positions nodes along a 180° semi-circular arc using `Math.cos()` and `Math.sin()`.
- 🎨 **Individual Harmonic Colors**: Each node features its own vibrant accent hue with matching hover & active glows.
- 🌊 **Shockwave Opening Ripple**: An expanding circular shockwave radiates outward on click.
- 🔄 **Cross-to-Close Rotation**: The center trigger morphs from `+` to `×` using CSS pseudo-elements.
- 🎯 **Click-Outside & Escape Dismiss**: Closes automatically when clicking outside or pressing `Escape`.
- 📐 **Subtle Dot-Grid Studio Backdrop**: Tactile blueprint background pattern.
- 💬 **Zero-JS Micro-Tooltips**: Clean hover labels using `data-label` and CSS `::after`.

## 🚀 How to Run
Simply open `index.html` in any web browser.

## 🛠️ Built With
- **HTML5** (Semantic markup with inline SVGs)
- **CSS3** (Shockwave animation, custom properties, spring easing)
- **Vanilla JavaScript** (Only ~22 lines for trigonometry, toggling & dismiss)
