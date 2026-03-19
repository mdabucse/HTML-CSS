# Tabbed Content Interface

## Overview
This project demonstrates a **Tabbed Content Interface** using pure HTML and CSS. It uses hidden radio buttons and the `:checked` pseudo-class to switch between tabs without JavaScript.

---

## Features
- **Pure CSS Tabs**
  - No JavaScript required
  - Uses radio inputs for state control
- **Interactive Switching**
  - Click tabs to display different content
- **Active Tab Highlight**
  - Selected tab is visually distinct
- **Smooth Transitions**
  - Content fades in smoothly

---

## File Structure

```
Task-6/
├── index.html
└── styles.css
```

---

## Workflow

### 1. HTML Structure
- **Radio Buttons**
  - Hidden inputs control active tab
  - First tab is selected by default
- **Labels**
  - Act as clickable tabs using `for` attribute
- **Content Sections**
  - Each tab has its own content block

### 2. CSS Styling

- **Hide Inputs**

```css
input[type="radio"] {
  display: none;
}
```

- **Show Active Content**

```css
#tab1:checked ~ .tab-content .content1 {
  opacity: 1;
}
```

- **Active Tab Highlight**

```css
#tab1:checked ~ .tab-labels label[for="tab1"] {
  background: green;
  color: white;
}
```

---

## Conclusion

This project shows how to build interactive UI components using only CSS, demonstrating the power of `:checked` and sibling selectors.