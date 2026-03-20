# Responsive Grid & Flexbox Layout

## Overview
This project demonstrates the creation of a **Responsive Layout** using a combination of CSS Grid and Flexbox. The layout includes a fixed header, a sticky sidebar, and a main content area with overlapping content. The design is fully responsive, adapting to different screen sizes with smooth transitions.

---

## Features
- **Fixed Header**:
  - The header remains fixed at the top of the page while scrolling.
- **Sticky Sidebar**:
  - The sidebar stays visible within the viewport as the user scrolls through the main content.
- **Grid Layout**:
  - The main content area is structured using CSS Grid, with two columns: one for the sidebar and one for the main content.
- **Flexbox Alignment**:
  - The main content section uses Flexbox to center its content vertically and horizontally.
- **Overlapping Content**:
  - A section of the main content is styled with `position: absolute` to overlap other elements.
- **Responsive Design**:
  - The layout adapts to smaller screens by switching to a single-column layout and repositioning the overlapping content.

---

## File Structure
```
Task-9/
├── index.html   # HTML file for the responsive layout
└── styles.css   # CSS file for styling the layout
```

---

## Workflow

### 1. **HTML Structure**
- **Header**:
  - Contains a fixed navigation bar with links.
- **Main Section**:
  - Uses a grid layout with two sections:
    - **Sidebar**: A sticky sidebar with additional content.
    - **Content**: The main content area, including overlapping content styled with `position: absolute`.
- **Footer**:
  - A simple footer at the bottom of the page.

### 2. **CSS Styling**
- **Fixed Header**:
  - Styled with `position: fixed` to remain at the top of the page.
  - Includes a navigation bar with links.
- **Sticky Sidebar**:
  - Styled with `position: sticky` to stay visible within the viewport.
- **Grid Layout**:
  - The main section uses `display: grid` with two columns for the sidebar and content.
- **Flexbox Alignment**:
  - The main content section uses `display: flex` to center its content both vertically and horizontally.
- **Overlapping Content**:
  - Styled with `position: absolute` to overlap other elements in the main content area.
- **Responsive Design**:
  - On smaller screens, the layout switches to a single-column grid, and the overlapping content is repositioned using `position: static`.

---