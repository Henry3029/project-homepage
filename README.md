# project-homepage
# Personal Portfolio Homepage | The Odin Project

A responsive, high-end personal landing page built as part of The Odin Project's Advanced HTML and CSS curriculum. This project demonstrates mastery of complex layout design, semantic document structures, and custom typography implementation without the reliance on external CSS frameworks.

---

## 🎯 Project Assignment Objectives

The goal of this project was to synthesize core concepts from the Advanced HTML and CSS section, specifically focusing on:
* **Component Component Architecture:** Crafting a clean, central hero profile section featuring a user profile picture coupled with a grid structure.
* **The "My Work" Grid:** Designing a gallery of **six distinct project cards** showcasing individual featured works, descriptive text, and technical icon links.
* **Typography & Visual Hierarchy:** Correctly implementing Google Fonts CDN (`Playfair Display` for bold, elegant headings and `Roboto` for highly readable body copy).

---

## 🛠️ Technical Concepts Mastered

### 1. Advanced Layout Management
* Utilized raw CSS positioning rules to cleanly lay out card assets, including absolute positioning techniques for interactive overlay elements.
* Implemented `overflow-x: hidden` globally on the viewport wrapper to eliminate unwanted horizontal layout wobbling on mobile devices, ensuring a native app feel.

### 2. Typography & CDN Integration
* Solved cross-origin font rendering bugs by configuring optimized preconnect resource hints (`fonts.gstatic.com`).
* Engineered a strict CSS specificity stack where header typography cleanly overrides global body font styles without layout shifts.

---

## 🖥️ Project Structure

```text
├── index.html          # Semantic HTML5 document (Profile Hero + 6 Work Cards)
└── css/
    └── style.css       # Custom stylesheet handling typography hierarchy & responsive layout rules
    
    
    🔒 License
This project is open-source and available under the MIT License.