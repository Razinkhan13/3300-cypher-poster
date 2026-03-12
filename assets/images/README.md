# Image Assets

This directory contains image assets for the 3300 CYPHER Poster Generator.

## Directory Structure

```
assets/images/
├── samples/          # Sample generated posters
├── backgrounds/      # Background images (if needed)
├── characters/       # Character artwork (if replacing SVGs)
└── logos/           # Logo files and branding
```

## Adding Images

### Character Images
If you want to replace the inline SVG characters with custom images:
1. Add your character images here (PNG or SVG format)
2. Recommended size: 200x300px for main character, 100x150px for supporting characters
3. Use transparent backgrounds (PNG with alpha channel)

### Background Images
For custom background textures or imagery:
1. Add images in JPG or PNG format
2. Recommended size: 1080x1920px (9:16 aspect ratio)
3. Keep file sizes optimized (< 500KB)

### Logo Files
For branding and watermarks:
1. SVG format preferred for scalability
2. PNG with transparency as alternative
3. Multiple sizes recommended

## Image Formats

- **SVG**: Vector graphics, best for logos and icons
- **PNG**: Raster images with transparency support
- **JPG**: Photos and complex images without transparency

## Optimization

Before adding images, consider optimizing them:
- Use tools like TinyPNG or ImageOptim
- Target file sizes under 200KB for web performance
- Consider WebP format for modern browser support

## Usage in Code

To use images from this directory in the poster generator:

```html
<!-- Replace SVG characters with images -->
<div class="char char-main">
  <img src="assets/images/characters/main-character.png" alt="Main Character">
</div>

<!-- Add background images -->
<div class="bg-custom" style="background-image: url('assets/images/backgrounds/cityscape.jpg')"></div>
```

## Sample Files

Currently, this directory contains placeholder files. Add your own images to customize the poster generator.
