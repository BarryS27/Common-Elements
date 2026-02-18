# Common Elements

This repository contains the shared foundational assets for my web projects, including SCSS modules, HTML boilerplates, and optimized static assets.

---

## 📦 Repository Contents

### 1. SCSS Framework
Four modular files defining the visual and interactive standards:
* **`_tokens.scss`**: System color variables (iOS-inspired) and animation curves.
* **`_mixins.scss`**: Core textures (glassmorphism) and interaction feedback (tap effects).
* **`_components.scss`**: Reusable UI parts like standardized cards, badges, and footers.
* **`_layout.scss`**: Global resets, typography rules, and entry animations.

### 2. HTML Templates
Standardized boilerplates for various project types:
* **Base Framework**: Pre-configured HTML structures with meta tags, CSP settings, and asset linking.

---

## 🚀 Usage

These files are synced to individual project directories (like `BarryS27.github.io` or `Financial-Terminal-Lite`) via **submodule** to ensure consistency across the local environment.

### Setup Notes
* **SCSS**: Requires a compiler to process the `@import` chain.
* **HTML**: Designed to be used with the local design system; requires correct relative paths to the `common` directory.