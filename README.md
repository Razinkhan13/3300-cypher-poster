# 3300 CYPHER — Ultimate Edition Poster Generator

An interactive web-based poster generator for creating customizable cyberpunk-themed music/game posters.

## Features

### 🎨 Multiple Themes
- **Inferno** - Fiery orange and gold palette
- **Cyber** - Neon cyan and purple aesthetic
- **Blood** - Deep red and crimson theme
- **Arctic** - Cool blue and white palette

### ✨ Interactive Elements
- **Particle System** - Click anywhere on the poster to create particle bursts
- **Music Visualizer** - Animated bars that pulse to create a dynamic effect
- **Custom Text** - Add your own name or label to personalize the poster
- **Animated Characters** - Six vector-based characters with unique animations
- **Theme Glow Effects** - Dynamic lighting and glow that changes with themes

### 📸 Export Functionality
- Export your customized poster as a high-quality PNG image
- One-click download with proper scaling (2x resolution)
- Preserves all visual effects and styling

## Usage

### Quick Start

1. **Open the Application**
   - Simply open `index.html` in your web browser
   - Or visit the live demo: [GitHub Pages URL]

2. **Choose a Theme**
   - Click any of the four theme buttons at the top:
     - 🔥 Inferno
     - ⚡ Cyber
     - 🩸 Blood
     - ❄️ Arctic

3. **Customize the Text**
   - Enter your name or custom text in the input field
   - Click "Apply" to update the poster

4. **Add Particle Effects**
   - Click anywhere on the poster for particle bursts
   - Or click the "💥 Burst!" button for multiple bursts

5. **Export Your Poster**
   - Click "📸 Export PNG" to download your customized poster
   - The file will be saved as `3300-CYPHER-POSTER.png`

## Technical Details

### Built With
- Pure HTML5, CSS3, and JavaScript (no frameworks)
- Canvas API for particle effects
- SVG for character illustrations
- CSS animations and gradients
- html2canvas library for PNG export

### Browser Compatibility
- Chrome/Edge (recommended)
- Firefox
- Safari
- Modern mobile browsers

### File Structure
```
3300-cypher-poster/
├── index.html          # Main application (self-contained)
├── assets/
│   └── images/         # Image assets directory
├── docs/               # Documentation images
├── LICENSE             # MIT License
└── README.md           # This file
```

## Customization

### Adding Your Own Images

The poster generator uses inline SVG for characters. To add custom images:

1. Place your images in the `assets/images/` directory
2. Modify the character sections in `index.html` (lines 523-684)
3. Replace SVG code with `<img>` tags pointing to your images

### Modifying Themes

Themes are defined in CSS variables (lines 126-181 in `index.html`):

```css
.theme-custom {
  --bg-deep: #000000;
  --accent: #FF0000;
  /* ... more variables ... */
}
```

Add your custom theme and corresponding button in the toolbar.

## Development

This is a static web application with no build process required.

### Local Development
1. Clone the repository
2. Open `index.html` in your browser
3. Make changes and refresh to see updates

### Deployment
The project is configured for GitHub Pages deployment via `.github/workflows/static.yml`.

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Credits

Created by 3300 Productions
