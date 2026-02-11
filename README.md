# Positivus Landing Page

A modern landing page for Positivus digital marketing agency.

## Project Structure

```
week-1/
├── index.html              # Main HTML file
├── styles/
│   ├── main.scss          # Main SCSS file (imports all partials)
│   ├── _variables.scss    # Design tokens (colors, typography, spacing)
│   ├── _base.scss         # Reset and base styles
│   ├── _layout.scss       # Layout utilities (grid, flex, spacing)
│   └── _components.scss   # Component styles (buttons, cards, sections)
├── scripts/
│   └── main.js            # JavaScript functionality
└── README.md              # This file
```

## Getting Started

### Compile SCSS

You'll need to compile the SCSS files to CSS. You can use:

1. **Live Sass Compiler** (VS Code extension)
2. **Command line:**
   ```bash
   sass styles/main.scss styles/main.css --watch
   ```

### Open the Project

Simply open `index.html` in your browser after compiling the SCSS.

## Design System

- **Primary Color:** #B0FF66 (Bright Green)
- **Dark Color:** #191A23
- **Typography:** Space Grotesk
- **Border Radius:** 7px, 14px, 45px

## Next Steps

1. Compile SCSS to CSS
2. Add content to HTML sections
3. Build out individual components
4. Add responsive styles
5. Implement JavaScript interactions
