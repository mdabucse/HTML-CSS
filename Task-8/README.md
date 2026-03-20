# CSS Accordion Component

Pure CSS accordion using the checkbox hack technique - no JavaScript required.

## Project Structure

```
├── index.html       # Main HTML structure
├── styles.css       # Styling and animations
└── README.md        # Documentation
```

## How It Works

- Hidden checkboxes store open/closed state
- Labels act as clickable triggers
- CSS `:checked` selector shows/hides content
- Smooth animations via CSS transitions



## Customization

**Add more sections:**
```html
<div class="item">
  <input type="checkbox" id="item3">
  <label for="item3">Section 3</label>
  <div class="content">
    <p>Your content here</p>
  </div>
</div>
```

**Change colors:** Edit `label { background: #603eaf; }` in `styles.css`

**Adjust speed:** Change `transition: max-height 0.4s ease;`

---
