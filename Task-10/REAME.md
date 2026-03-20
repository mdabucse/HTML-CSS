# Interactive Multi-Page Website Simulator with CSS Only

## Overview
This project demonstrates the creation of an **Interactive Multi-Page Website Simulator** using only HTML and CSS. The website simulates navigation between multiple pages using the `:target` pseudo-class and CSS animations. The design is fully responsive, leveraging advanced CSS techniques like Flexbox, pseudo-classes, and animations to create a seamless user experience.

---

## Features
- **Multi-Page Simulation**:
  - Each section acts as a "page" that can be navigated using anchor links.
  - The `:target` pseudo-class is used to display the active section.
- **CSS Animations**:
  - Smooth transitions and animations (fade-in and flip effects) simulate page transitions.
- **Responsive Design**:
  - The layout adapts to different screen sizes, ensuring usability on mobile, tablet, and desktop devices.
- **Fixed Header**:
  - A fixed navigation bar remains at the top of the page while scrolling.
- **Accessible Navigation**:
  - A clean and intuitive navigation menu allows users to switch between sections easily.

---

## File Structure
```
Task-10/
├── index.html   # HTML file for the multi-page simulator
└── styles.css   # CSS file for styling the website
```

---

## Workflow

### 1. **HTML Structure**
- **Header**:
  - Contains a fixed navigation bar with links pointing to the `id` of each section.
- **Main Content**:
  - Each section (`<section>`) represents a "page" with a unique `id` (e.g., `#home`, `#about`).
  - The `:target` pseudo-class is used to display the active section.
- **Footer**:
  - A simple footer at the bottom of the page.

### 2. **CSS Styling**
- **Fixed Header**:
  - Styled with `position: fixed` to remain at the top of the page.
  - Includes a navigation menu styled with Flexbox for horizontal alignment.
- **Page Transitions**:
  - The `:target` pseudo-class is used to display the active section.
  - CSS animations (e.g., `@keyframes flipper`) create smooth transitions between sections.
- **Responsive Design**:
  - The layout adapts to smaller screens using media queries.
  - The navigation menu switches to a vertical layout on mobile devices.

---