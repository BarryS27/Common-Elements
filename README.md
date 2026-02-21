# @barrys27/ui
### A simple, clean UI architecture for building better interfaces.

**@barrys27/ui** is a minimalist CSS utility library designed for clarity and order. It doesn't force you into complex frameworks; instead, it provides a set of **design rules** and **atomic components** to make your data dashboards or personal portfolios look professional and refined.

---

## 📐 The Rules (Design Philosophy)

### 1. The 8-Point Grid
The secret to great design is alignment. In this system, every margin, padding, and gap follows the **8-point grid** (8, 16, 24, 32...). By sticking to these mathematical increments, your interface will always feel balanced and consistent.

### 2. Glassmorphism
Inspired by iOS, our core containers use a frosted-glass effect. This "material" ensures your content is readable on any background while maintaining a light, modern aesthetic.

### 3. Zero-JS Motion
We believe motion should be part of the physics of the page, not a heavy script. Using modern CSS, elements automatically fade and scale into view as you scroll—no JavaScript required.

---

## 💎 The Atoms (Core Components)

* **`.card`**: The primary container. It features frosted-glass styling and smooth corners. Add `.is-interactive` for spring-loaded hover feedback.
* **`.row`**: Built for data density. It perfectly aligns labels to the left and values to the right, creating a clean flow for financial or technical info.
* **`.badge`**: A sharp, high-contrast label. It uses "hairline" borders to stay crisp and visible even at small sizes.

---

## 🚀 Implementation Patterns

### Pattern A: Immersive Exhibition
Ideal for showcasing projects on sites like [`barrys27.github.io`](https://barrys27.github.io):

```scss
<div class="card fade-in">
    <img src="cover.jpg" class="cover">
    <div style="padding: 24px;">
        <h3>Iris Dataset Analysis</h3>
        <p>A study in data visualization and species relationships.</p>
    </div>
</div>
```

---

## 🛠 Getting Started

1. **Install**: `npm install @barrys27/ui`
2. **Import**: Add the essentials to your Scss entry point:

```scss
@use '@barrys27/ui/base';
@use '@barrys27/ui/card';
@use '@barrys27/ui/badge';
@use '@barrys27/ui/row';
```

---

Author
Bairu Song
Lexington High School
Focusing on Data Science and Business.
---
Inspired by iOS Human Interface Guidelines.