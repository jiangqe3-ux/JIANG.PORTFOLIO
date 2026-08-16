# Jiang Yishan Portfolio

Personal portfolio website for Jiang Yishan (姜懿珊), an AIGC Creative Designer / Visual Storyteller.

## About

This is a static portfolio site showcasing:
- AIGC Operation Design
- Brand Design
- APP / UIUX Design
- IP & Character Design
- Internship Archive

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- GSAP for animations
- No build tools required — pure static site

## Deploy to GitHub Pages

1. Create a new repository on GitHub (can be public or private)
2. Upload all files from this folder to the repository root
3. Go to repository **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**
7. Wait 1-2 minutes for deployment
8. Your site will be live at `https://your-username.github.io/your-repo-name/`

## Local Preview

```bash
# Option 1: Direct open
double-click index.html

# Option 2: Local server (recommended)
python -m http.server 8000
# Then visit http://localhost:8000
```

## File Structure

```
├── index.html          # Homepage
├── about.html          # About page
├── archive.html        # Works archive
├── projects/           # Individual project pages
├── assets/
│   ├── css/style.css   # Styles
│   ├── js/
│   │   ├── data.js     # Site data
│   │   └── main.js     # Rendering logic
│   ├── portfolio-long-images/  # Project images
│   └── videos/         # Project videos
└── README.md
```
