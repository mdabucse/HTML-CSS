# Static Webpage Layout

## Overview
This project demonstrates the creation of a static single-page website using semantic HTML elements and basic CSS styling. The webpage includes a responsive design that adjusts the layout for smaller screens.

---

## Features
- **Semantic HTML Structure**: Semantic tags in HTML are elements that clearly describe their meaning and purpose in a human- and machine-readable way which includes `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` elements.
- **Basic CSS Styling**: Typography, colors, and spacing are applied for a clean and structured layout.
- **Responsive Design**: Uses media queries to adjust the layout for screens smaller than 700px.

---

## File Structure
```
Task-1/
├── index.html   # HTML file for the webpage
└── styles.css   # CSS file for styling the webpage
```

---

## Workflow

### 1. **HTML Structure**
- Created a semantic structure in `index.html`:
  - `<header>`: Contains the title and navigation links.
  - `<main>`: Includes four sections: Home, About, Projects, and Contact.
  - `<footer>`: Displays copyright information.

### 2. **CSS Styling**
- Added styles in `styles.css`:
  - **Body**: Set a background color, font family, and text color.
  - **Header**: Styled with a fixed position, background color, and flexbox for layout.
  - **Navigation**: Styled links with larger font size and white color.
  - **Sections**: Added spacing and height for a clean layout.
  - **Footer**: Styled with a gray background and white text.

### 3. **Responsive Design**
- Used a media query for screens smaller than 700px:
  - Adjusted the header layout to stack elements vertically.
  - Increased spacing for sections to improve readability.