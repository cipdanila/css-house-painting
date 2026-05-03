# Interactive CSS House Painting 🏠

A digital artwork created entirely with semantic HTML and advanced CSS, featuring interactive 3D animations and procedural environment textures.

## 🚀 Features

- **Interactive Elements:** 
  - **Windows:** Tilt-open effect (X-axis rotation) simulating a top-hinged window.
  - **Door:** 3D swinging animation (Y-axis rotation) with a golden doorknob.
  - **Interior Shadows:** Dark "containers" behind openings simulate room depth when interactive elements are activated.
- **Procedural Textures:**
  - **Cloudscape:** Irregular, soft-edged clouds built using overlapping radial gradients.
  - **Lush Grass:** Multi-layered gradients with yellow/green highlights for a textured meadow look.
  - **Brickwork:** Repeating linear gradients on the chimney for a realistic masonry effect.
  - **Shingles:** Shingle-textured roof created using `clip-path` and intersecting gradients.
- **Dynamic Smoke:** Animated smoke puffs rising from the chimney using CSS keyframes and staggered delays.

## 🛠️ Tech Stack

- **HTML5:** Semantic structure with dedicated containers for 3D interactions.
- **CSS3:** 3D Transforms (`perspective`, `rotate`), Keyframe Animations, Multiple Backgrounds, and `clip-path`.

## 💡 Key Learnings

1. **3D Interactive Design:** Managing `transform-origin` to simulate realistic hinge movements.
2. **Advanced Gradients:** Using multiple radial and linear gradients on the `body` to create a complete environment without images.
3. **Pseudo-depth:** Implementing the "hole" technique to show a dark interior when doors or windows are opened.

## 🔧 Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/cipdanila/css-house-painting.git
   ```
2. Open `index.html` in your favorite browser.

---
*Created by Ciprian Danila - Pushing the boundaries of CSS.*
