# Pure CSS Carousel / Slider

## Overview
This project demonstrates a **Pure CSS Carousel/Slider** using HTML and CSS. It uses hidden radio buttons and the `:checked` pseudo-class to switch between slides, with a CSS animation for auto-scrolling — no JavaScript required.

---

## Features
- **Pure CSS Slider**
  - No JavaScript required
  - Uses radio inputs for state control
- **Auto Scroll**
  - Slides change automatically using `@keyframes` animation
- **Manual Navigation**
  - Click dots to jump to a specific slide
- **Smooth Transitions**
  - Slides move with `ease-in-out` transition on manual click

---

## File Structure

```
Task/
├── index.html
├── styles.css
└── assets/
    ├── img1.jpg
    ├── img2.jpg
    └── img3.jpg
```

---

## Workflow

### 1. HTML Structure
- **Radio Buttons**
  - Placed outside `.slider` so `checked` state does not block auto-scroll
  - No default `checked` attribute — lets animation run on load
- **Labels**
  - Act as clickable dot indicators using `for` attribute
- **Slides**
  - Each slide holds a full-width image

### 2. CSS Styling

- **Hide Inputs**

```css
input {
  display: none;
}
```

- **Slide Layout**

```css
.slides {
  display: flex;
  width: 100%;
  height: 100%;
  animation: slideAnimation 9s infinite;
}

.slide {
  min-width: 100%;
  flex-shrink: 0;
}
```

- **Auto Scroll Animation**

```css
@keyframes slideAnimation {
  0%,  30% { transform: translateX(0%); }
  33%, 63% { transform: translateX(-100%); }
  66%, 96% { transform: translateX(-200%); }
  100%     { transform: translateX(0%); }
}
```

- **Manual Dot Navigation**

```css
#slide1:checked ~ .slider .slides {
  transform: translateX(0%);
  animation: none;
  transition: transform 0.5s ease-in-out;
}
```

---

## Key Fix

The radio inputs must be placed **outside** the `.slider` div. If placed inside with `checked` on load, the `#slide1:checked ~ .slides` rule fires immediately and sets `animation: none`, killing the auto-scroll before it starts.

---

## Conclusion

This project shows how to build an auto-scrolling image carousel using only CSS, demonstrating the power of `@keyframes`, `:checked`, and sibling selectors.