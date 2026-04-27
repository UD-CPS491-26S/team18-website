# Camp AI — Project Site

Public-facing GitHub Pages site for the Camp AI capstone project at the University of Dayton (CPS 491, Spring 2026).

## Files

```
index.html          → main site
escape-room.html    → AI Escape Room activity (embedded as iframe)
defense-lawyer.html → AI Defense Lawyer activity (embedded as iframe)
README.md           → this file
```

## Sections

- Hero with quick stats
- Project overview + learning objective callout
- Six expandable feature cards
- Day 1 Canvas-style schedule (mirrors the actual Canvas module layout)
- **Two playable activities embedded live in the page** (Escape Room + Defense Lawyer)
- Video demo placeholder (drop in your YouTube/Vimeo/MP4 embed)
- Team and tech stack

## Adding the demo video

In `index.html`, find the comment block in the video section (search for "TO ADD YOUR VIDEO") and replace the `<div class="video-placeholder">` with one of:

**YouTube:**
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen></iframe>
```

**Local MP4:**
```html
<video controls poster="thumbnail.jpg">
  <source src="demo.mp4" type="video/mp4">
</video>
```

**Vimeo:**
```html
<iframe src="https://player.vimeo.com/video/YOUR_VIDEO_ID" allowfullscreen></iframe>
```

## Deploying to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Source: select your main branch and the root folder
4. Save — your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`

The activity HTML files need to live alongside `index.html` (same directory) so the iframes can load them.

## Brand system

Colors, typography, and spacing follow the Camp AI Brand Guide v1.1 — UD red `#CE1141` for primary accents, Arial throughout, and the locked emoji vocabulary for section headers.

## Team

- Edward "Quad" Kramer IV
- Khagendra Mishra
- Brock Hensley

Client: Dr. Poor
