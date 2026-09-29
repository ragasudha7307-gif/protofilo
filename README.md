# Personal Portfolio Site

A clean, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive design** — works on desktop, tablet, and mobile
- **Smooth scroll** navigation between sections
- **Scroll reveal animations** — elements animate in as you scroll
- **Animated counters** — stats count up when visible
- **Hover effects** — cards lift, buttons glow, links underline
- **Mobile hamburger menu** — collapsible nav on small screens
- **Sticky navbar** — transparent → blurred background on scroll
- **Contact form** — with simulated send feedback

## Sections

1. **Hero** — Name, title, description, CTA buttons, social links
2. **About** — Bio, avatar, animated stats
3. **Skills** — 4 category cards with tech tags
4. **Projects** — 4 project cards with hover overlays
5. **Resume** — Experience & education timeline
6. **Contact** — Info cards + contact form

## Local Development

Open `index.html` in your browser, or use a local server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```

## Deploy to GitHub Pages

1. Push this folder to a GitHub repository
2. Go to **Settings → Pages**
3. Select source: **Deploy from a branch**
4. Choose `main` branch / root folder
5. Your site will be live at `https://<username>.github.io/<repo-name>/`

## Deploy to Netlify

1. Drag and drop this folder onto [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repo at [Netlify](https://netlify.com)
3. No build step needed — it's a static site

## Customization

| What | Where |
|------|-------|
| Name, bio, stats | `index.html` — search for "Alex Chen" |
| Skills & tags | `index.html` — `.skill-card` elements |
| Projects | `index.html` — `.project-card` elements |
| Experience | `index.html` — `.resume-item` elements |
| Colors & fonts | `styles.css` — `:root` CSS variables |
| Social links | `index.html` — `.hero-socials` section |
