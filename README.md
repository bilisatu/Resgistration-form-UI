# Practice Form with Hover

A minimal HTML/CSS practice project that showcases a small registration form with modern gradients and subtle hover animations on the card, inputs, and button.

## Features

- Gradient background and card styling
- Card hover: scale-up with highlighted border
- Input hover: gentle scale and glow
- Button hover: color shift, subtle translate, and shadow
- Zero build setup: just open the HTML file in a browser

## Project structure

```
practice-form with hover/
├─ index.html   # Markup for the demo form
└─ style.css    # Gradients, layout, and hover animations
```

## How to run

- Double-click `index.html` to open it in your default browser, or
- Open the folder in VS Code and use an HTML preview or a live-server extension to see changes as you edit.

## Customize

- Colors
  - Page background gradient: edit `body { background: ... }` in `style.css`.
  - Card gradient: edit `.form { background: ... }`.
  - Button gradient and hover: edit `button` and `button:hover`.
- Sizing and spacing
  - Card width/height/margins: `.form { width, height, margin, border-radius }`.
  - Input padding and spacing: `input { padding, margin }`.
- Animations
  - Adjust transition speeds in `.form`, `button`, and `input` rules.
  - Modify transform scale/translate values in the `:hover` rules.

## Notes and next steps (optional)

- Semantics: If you plan to submit data, wrap the controls in an actual `<form>` element and include an `action` or client-side handling.
- Accessibility: Ensure labels are correctly associated with inputs, add `name` attributes to all fields, and consider focus styles for keyboard users.
- Validation: Add HTML `pattern`, `minlength`, or client-side validation as needed.

## Browser support

This is plain HTML/CSS using standard gradients and transforms. It should work in all modern browsers (Chromium, Firefox, Safari, Edge).