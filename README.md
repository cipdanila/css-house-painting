# Interactive CSS House Painting (Bojdeuca Ticau Edition) 🏠

A digital artwork created entirely with semantic HTML and advanced CSS, featuring interactive 3D animations, procedural environment textures, and a dynamic ecosystem switcher. This project merges design mechanics from the **City Skyline** curriculum with traditional architectural elements inspired by Ion Creangă's historical cottage in Ticău, Iași.

## 🚀 Features

*   **Interactive 3D Elements & Light Physics:**
    *   **Windows:** Tilt-open effect (X-axis rotation) simulating a top-hinged window layout.
    *   **Door:** 3D swinging animation (Y-axis rotation) complete with a golden doorknob layer.
    *   **Dynamic Interiors:** Integrated advanced hover triggers (`:has()`). Openings reveal a dark vacancy during daytime, but dynamically spill a warm golden radial light gradient and cast external beams onto the grass when opened at night.
*   **City Skyline Integrated Day/Night Engine:**
    *   **Pure CSS Environment Switcher:** Driven entirely by a No-JS checkbox hack (`.state-checkbox ~ .sky`). Clicking the celestial button transitions the entire scene fluidly over a 0.8s bezier curve.
    *   **Morphic Icon Switcher:** The toggle controller dynamically changes from a glowing golden Sun into a sharp silver crescent Moon using precise shadow offsets (`box-shadow`).
    *   **Procedural Atmospheres:** Swaps a custom, vibrant daytime sunburst layout for a midnight blue starfield generated using overlapping micro-radial gradients directly in the stylesheet.
*   **Strict Web Accessibility & Vestibular Guard (Axe Linter Approved):**
    *   **Reduced Motion Mitigation:** Full implementation of the `prefers-reduced-motion: reduce` media feature. Users with motion sensitivities or vestibular disorders will see all high-frequency 3D rotations disabled, the continuous chimney smoke animated particles halted, and transitions instantly snapped to prevent motion-induced discomfort.
*   **Procedural Textures:**
    *   **Lush Meadow:** Multi-layered grass gradients with variable brightness filters that dim automatically when night falls.
    *   **Brickwork & Shingles:** Masonry effects on the chimney via repeating gradients and a shingle-textured roof created using intersecting patterns bounded by a clean `clip-path` polygon.
*   **Dynamic Smoke:** Staggered particle animation loops using CSS keyframes to simulate smoke puffs rising into the upper atmosphere.

## 🛠️ Tech Stack

*   **HTML5:** Clean semantic architecture providing dedicated voxel anchors for advanced 3D perspective manipulation.
*   **CSS3:** Design Tokens / Variables (`:root`), 3D Transforms (`perspective`, `rotate`), Keyframe Animations, Complex Background Matrices, Accessibility Media Queries (`prefers-reduced-motion`), and Sibling Combinators (`~`).

## 💡 Key Learnings & Project Evolution

1. **Cross-Project Integration:** Successfully adapted environmental rendering logic and multi-layered gradient configurations mastered in the **City Skyline** project to create an interactive celestial ecosystem.
2. **Advanced Light Casting:** Managing parent-child layout properties via pseudo-classes to shift structural backgrounds when structural entryways open under specific global states.
3. **Inclusive Motion Architecture:** Developing an override layers layout that respects operating system accessibility preferences to ensure a safe user experience across all dynamic elements.

## 🔧 Setup

1. Clone the repository:
   ```bash
   git clone https://github.com
   ```
2. Open `index.html` inside your favorite browser workspace.

---
*Created by Ciprian Danila - Pushing the boundaries of CSS.*
