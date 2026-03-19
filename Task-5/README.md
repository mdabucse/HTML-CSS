# Modal Popup Using CSS (:target)

## Overview
This project demonstrates how to create a modal popup using only HTML and CSS without JavaScript. The modal appears when a button is clicked and disappears when closed. It uses the `:target` pseudo-class to control visibility, along with smooth transitions and an overlay background.

---

## Features
- **Modal Popup**:
  - A popup window that appears when clicking a button.
  - Displays a message inside a centered box.
- **Overlay Background**:
  - A dark semi-transparent background that covers the entire screen.
- **CSS Only Functionality**:
  - Uses `:target` pseudo-class instead of JavaScript.
- **Smooth Transitions**:
  - Fade-in and scaling animation when modal appears.

---

## File Structure
## File Structure
```
Task-4/
├── index.html   # HTML file for the pop up
└── styles.css   # CSS file for styling the pop up 
```


---

## Workflow

### 1. **HTML Structure**
- Created the modal structure in `index.html`:
  - `<a href="#modal">`: Button to trigger the modal popup.
  - `<div id="modal" class="modal">`: Outer container for overlay and visibility control.
  - `<div class="modal-content">`: Inner container for popup content.
  - `<a href="#">`: Close button to hide the modal.

---

### 2. **CSS Styling**
- Styled the modal in `styles.css`:

  - **Modal (Overlay)**:
    - `position: fixed`: Covers the full screen.
    - `background: rgba(...)`: Creates dark overlay effect.
    - `opacity: 0` and `visibility: hidden`: Hides modal by default.

  - **:target Pseudo-Class**:
    - `#modal:target`: Displays the modal when URL matches the ID.
    - Changes `opacity` and `visibility` to show the modal.

  - **Modal Content**:
    - Centered using `display: flex`, `justify-content`, and `align-items`.
    - Styled with background, padding, and border-radius.

  - **Transitions**:
    - `transition`: Adds smooth fade and scale animation.

---

## How It Works
1. Click the **Submit** button.
2. URL changes to `#modal`.
3. CSS `:target` activates and shows the modal.
4. Click **Close** to remove `#modal` from URL.
5. Modal disappears.

---

## Notes
- The `href` value must match the `id` exactly: