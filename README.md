# mrdivinn Portfolio

A clean, modern portfolio website with black and green color scheme.

## How to Use

1. **Replace the video placeholders** with your actual animation videos:
   - Open `index.html` in a text editor
   - Find the `<article class="video-card">` sections
   - Replace the `<div class="video-placeholder">` elements with your video embeds

2. **To add videos from YouTube**:
```html
<iframe 
  src="https://www.youtube.com/embed/YOUR_VIDEO_ID?autoplay=1&loop=1&muted=1&controls=0" 
  allow="autoplay; fullscreen; encrypted-media" 
  allowfullscreen 
  loading="lazy">
</iframe>
```

3. **To add videos from Streamable** (like the reference site):
```html
<iframe 
  src="https://streamable.com/e/YOUR_VIDEO_CODE?autoplay=1&loop=1&muted=1&controls=0" 
  allow="autoplay; fullscreen; encrypted-media" 
  allowfullscreen 
  loading="lazy">
</iframe>
```

4. **Update the video titles** by changing the text inside `<div class="video-title">`

5. **Customize the capabilities** in the "What I Can Do" section:
   - Edit the lists in the `.capability-card` divs
   - Add or remove items as needed

6. **To view the portfolio**:
   - Simply open `index.html` in any web browser
   - Or host it on GitHub Pages, Netlify, Vercel, etc.

## Folder Structure

```
portfolio/
├── index.html    # Main HTML file
└── README.md     # This file
```

## Color Scheme

The portfolio uses a black and green color palette:
- Background: Dark blacks (#0a0a0a, #111111)
- Accent colors: Various greens (#4caf50, #8bc34a, #2e7d32)
- Text: Light grays (#e0e0e0, #888888)

## Features

- Responsive design (works on mobile and desktop)
- Smooth hover effects on video cards
- Clean, modern aesthetic
- Easy to customize
