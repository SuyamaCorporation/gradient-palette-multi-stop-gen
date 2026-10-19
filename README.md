# Multi-Stop CSS Gradient Palette Generator

A full-featured CSS gradient builder with interactive multi-stop editing and live previews.

## Features
- Visual gradient track (full-width, 80px): click to add stops, drag to move, double-click to remove
- Each stop: color picker, hex input, position (%), opacity slider
- Gradient type: Linear (angle 0–360°) or Radial (with position selector)
- Live previews: Card, Button, Hero Banner, Circle/Avatar
- CSS output with copy-to-clipboard button
- 8 beautiful presets: Sunset, Ocean, Forest, Candy, Night Sky, Aurora, Rose Gold, Midnight
- Save up to 5 custom gradients to localStorage
- "Randomize" button for random pleasant gradients
- XSS-safe CSS output via escapeHtml()

## Usage
Open `index.html` in any modern browser. No server required.
Saved gradients persist via localStorage across sessions.
