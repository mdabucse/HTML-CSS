# Pure CSS Dropdown Menu

## Overview
This project demonstrates the creation of a dropdown menu using only HTML and CSS. The dropdown menu includes a main menu with options, a hover-based submenu, and a nested sub-dropdown. The design is responsive and interactive, with smooth transitions and hover effects.

---

## Features
- **Dropdown Menu**:
  - A main dropdown menu that appears on hover.
  - Includes multiple options, with one option containing a nested submenu.
- **Submenu**:
  - A nested submenu that appears on hover over a specific option.
- **Hover Effects**:
  - Smooth background color transitions for menu items on hover.
---

## File Structure
```
Task-4/
├── index.html   # HTML file for the dropdown menu
└── styles.css   # CSS file for styling the dropdown menu
```

## Workflow

### 1. **HTML Structure**
- Created a dropdown menu in `index.html`:
  - `nav` `class='menu'`: The main dropdown.used the `<ul>`
  - `class="submenu"`: The dropdown menu that appears on hover. A nested submenu inside the dropdown menu.

### 2. **CSS Styling**
- Styled the dropdown menu in `styles.css`:
  - **Dropdown Menu**:
    - `position: relative`: Ensures the dropdown menu is positioned relative to its parent.
    - `display: none`: Hides the dropdown menu by default.
    - `:hover`: Reveals the dropdown menu when the parent is hovered.
  - **Submenu**:
    - `position: absolute`: Positions the submenu to the right of the parent menu item.
    - `display: none`: Hides the submenu by default.
    - `:hover`: Reveals the submenu when the parent menu item is hovered.
  - **Hover Effects**:
    - To show the items of submenu `display:block`.

---