# CSS Card Component with Hover Effects

## Overview
This project demonstrates the creation of a card component using HTML and CSS. The card includes an image, a title, and a description, styled with borders, shadows, and padding. A hover effect is implemented to enhance interactivity, along with responsive design for smaller screens.

---

## Features
- **Card Design**:
  - Includes an image, title, and description.
  - Styled with borders, shadows, and rounded corners.
- **Hover Effect**:
  - Slight scaling and background color change on hover.
  - Smooth transitions for a polished effect.
- **Responsive Design**:
  - Adjusts layout for smaller screens using media queries.

---

## File Structure
```
Task-2/
├── index.html   # HTML file for the card component
└── styles.css   # CSS file for styling the card
```

---

## Workflow

### 1. **HTML Structure**
- Created a card component in `index.html`:
  - `<container>`: Contains the list of card, aligns them.
  - `<div class="card">`: Contains an image, title, and description.
  - `<img>`: Displays the card image.
  - `<h3>`: Displays the card title.
  - `<p>`: Displays the card description.

### 2. **CSS Styling**
- Styled the card in `styles.css`:
  - **Card Styling**:
    - Added a border, shadow, and padding for a clean layout.
    - Rounded the corners using `border-radius`.
  - **Hover Effect**:
    - Used `transform: scale(1.05)` to enlarge the card slightly on hover.
    - Changed the background color on hover.
    - Applied `transition` for smooth scaling and color changes.
  - **Responsive Design**:
    - Used a media query to adjust the layout for screens smaller than 700px.
    - Stacked cards vertically and adjusted their width for smaller screens.
