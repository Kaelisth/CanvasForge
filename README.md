# CanvasForge — Digital Painting Studio

A browser-based digital painting application with two editions: **Basic** for quick sketches and **Professional** for advanced creative work.

## Project Structure

```
├── index.html        ← Landing page with navigation
├── app-basic.html    ← Basic Edition (standard tools)
├── app-pro.html      ← Professional Edition (advanced suite)
├── README.md         ← This file
└── about.txt         ← Project summary (< 250 words)
```

## Quick Start

Open `index.html` in any modern browser. No build step, no dependencies, no server required.

## Basic Edition

Designed for everyday drawing with a clean, focused interface.

- **Tools**: Brush, Eraser, Line, Rectangle, Circle, Fill, Eyedropper
- **Colors**: 24-color curated preset palette
- **Controls**: Brush size (1–50px), Opacity (10–100%)
- **Actions**: Undo / Redo (Ctrl+Z / Ctrl+Y), Clear canvas
- **Export**: PNG
- **Canvas**: 900 × 600 pixels

## Professional Edition

Full-featured studio for serious creative work.

- **Brush Engine**: Brush, Pencil, Marker, Airbrush, Watercolor, Calligraphy, Eraser, Smudge — each with unique rendering behavior
- **Color System**: HSL / RGB / HEX input modes, real-time Saturation-Value picker, Hue wheel, Alpha channel
- **Palette Management**: 30-color default palette, add custom colors, save/load palettes as JSON
- **Brush Controls**: Size (1–100), Opacity, Flow, Hardness, Spacing — with live preview
- **Shapes**: Line, Rectangle, Ellipse with current brush settings
- **Overlays**: Grid snap, Vertical symmetry, Horizontal symmetry
- **Transform**: Flip horizontal / vertical
- **Export**: PNG, JPEG (adjustable quality), SVG
- **Canvas**: 1000 × 660 pixels

## Multi-Language Support

All three pages support six languages with instant switching:

| Code | Language |
|------|----------|
| en   | English  |
| zh   | 中文     |
| ja   | 日本語   |
| ko   | 한국어   |
| fr   | Français |
| es   | Español  |

Language preference persists via `localStorage`.

## Keyboard Shortcuts (Pro)

| Key     | Action      |
|---------|-------------|
| B       | Brush       |
| P       | Pencil      |
| M       | Marker      |
| A       | Airbrush    |
| W       | Watercolor  |
| E       | Eraser      |
| G       | Fill        |
| I       | Eyedropper  |
| Ctrl+Z  | Undo        |
| Ctrl+Y  | Redo        |

## Technical Notes

- Pure HTML/CSS/JS — zero external dependencies (except Google Fonts)
- Canvas 2D API for all rendering
- History stack supports 50 states (Basic) / 80 states (Pro)
- Responsive dark theme with CSS custom properties
- Scroll-triggered animations on landing page

## Browser Support

Chrome 90+, Firefox 88+, Safari 15+, Edge 90+

## License

MIT
