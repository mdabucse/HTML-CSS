# Responsive Grid Layout

## Overview
This project demonstrates the creation of a responsive grid layout using CSS Grid. The layout displays multiple items in a grid format, with three columns on desktop screens, two columns on tablets, and a single column on mobile devices. The design ensures consistent spacing, alignment, and responsiveness.

---

## Features
- **Grid Layout**:
  - Displays items in a structured grid format.
  - Uses CSS Grid for layout management.
- **Responsive Design**:
  - Adjusts the number of columns based on screen size:
    - **Desktop**: Three columns.
    - **Tablet**: Two columns.
    - **Mobile**: Single column.
- **Hover Effect**:
  - Adds a scaling effect to grid items on hover for interactivity.
- **Consistent Styling**:
  - Includes spacing, alignment, and shadow effects for a clean design.

---

## File Structure
```
Task-3/
├── index.html   # HTML file for the grid layout
└── styles.css   # CSS file for styling the grid
```

---

## Workflow

### 1. **HTML Structure**
- Created a grid container in `index.html`:
  - `<div class="grid-container">`: Parent container for the grid layout.
  - `<div class="grid-item">`: Individual items in the grid.

### 2. **CSS Styling**
- Styled the grid in `styles.css`:
  - **Grid Layout**:
    - Used `grid-template-columns` to define the number of columns.
    - Added `gap` for consistent spacing between items.
  - **Responsive Design**:
    - Used media queries to adjust the number of columns based on screen width.
  - **Hover Effect**:
    - Applied `transform: scale(1.05)` to enlarge items slightly on hover.

---