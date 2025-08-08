# Telegram Emoji Splitter 🧩

Split static images or animated GIFs into 100x100 px tiles, export as PNG or WebP, and prep for `.tgs` animated emoji format.

## 🔧 Features
- Resize images to 500x500px
- Split into 100x100px tiles
- Export tiles as `.png` and `.webp`
- GIF animation frame splitting
- Notes for `.tgs` conversion (vector-based)

## 🚀 Usage
1. Open `index.html` in your browser
2. Drag & drop any image or GIF
3. Download the PNG/WebP tiles
4. Use your own tooling or scripts to:
   - Convert GIF → SVG (e.g. imagetracerjs)
   - Build Lottie JSON
   - Convert to `.tgs` using: `npx lottie-tgs`

## 🔁 TGS Conversion Notes
Telegram animated emojis must be:
- Vector-based
- 100x100 px
- `.tgs` format (gzip’d Lottie JSON)

GIFs must be vectorized before TGS export.

## 🧪 Coming Soon
- CLI tool for GIF → SVG → Lottie → TGS
- Web-based Lottie JSON builder
