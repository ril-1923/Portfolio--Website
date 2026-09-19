# Personal Portfolio Website

A responsive one-page portfolio built with plain HTML5 and CSS3 (no frameworks).

## Folder structure
```
portfolio-website/
├── index.html
├── css/
│   └── style.css
├── images/          (add your own photos here)
└── README.md
```

## Sections included
- **Home** — hero intro with name, tagline, and call-to-action buttons
- **About Me** — photo, bio, and a quick-facts list
- **Skills** — a table of skills with proficiency bars, plus a tools list
- **Projects** — a card grid (image, description, links) for 3 sample projects
- **Contact** — contact details, social links, and a working-layout contact form

## HTML elements used
Headings (h1–h3), paragraphs, hyperlinks, images (with fallback placeholders),
ordered/unordered lists, a `<table>`, and a `<form>` with text/email/textarea inputs.

## CSS techniques used
- Element, class, pseudo-class (`:hover`, `:focus`) and descendant selectors
- Custom properties (CSS variables) for color and font tokens
- The box model (padding, border, margin) throughout
- Flexbox for the navbar, hero, about, skills, projects, and contact layouts
- Media queries for tablet (860px) and mobile (700px, 480px) breakpoints
- Hover effects (buttons, nav links, table rows, tags, project cards) and
  `transition` for smooth state changes

## Before you submit
1. Replace the placeholder avatar and images:
   - Add a real photo as `images/about-photo.jpg`
   - Add project screenshots as `images/project1.jpg`, `project2.jpg`, `project3.jpg`
   - Optionally swap the initials circle in the hero for `<img src="images/profile.jpg" ...>`
     (the commented-out line is already in `index.html`)
2. Update the placeholder name, bio, email, phone, and social links with your own.
3. Open `index.html` directly in a browser to test, then resize the window
   (or use your browser's device toolbar) to check the mobile layout.
4. Take screenshots of the desktop and mobile views for your submission.

## Uploading to Google Drive
1. Upload the whole `portfolio-website` folder (or this zip, unzipped) to Google Drive.
2. Right-click the folder → **Share** → set access to **"Anyone with the link" → Viewer**.
3. Copy the share link and submit it before the deadline.
