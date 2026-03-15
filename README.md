# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and vanilla JavaScript.

## Features

- **Hero** – Name, tagline, and call-to-action buttons
- **About** – Bio section with avatar placeholder
- **Projects** – Grid of project cards with descriptions and tech stack
- **Skills** – Categorized skills (Frontend, Backend, Tools)
- **Contact** – Email and social links

## Customization

1. **Personal info**: Replace "Your Name", tagline, and intro text in `index.html`
2. **Projects**: Update project titles, descriptions, tags, and links
3. **Skills**: Edit the skill categories and items to match your experience
4. **Contact**: Replace email and social URLs with your own
5. **Photo**: Add your image by replacing the `.avatar-placeholder` div with an `<img>` tag
6. **Project images**: Replace `.project-placeholder` divs with real screenshots

## Setup

1. Open `index.html` in a browser, or
2. Use a local server (recommended):
   ```bash
   # Python 3
   python -m http.server 8000

   # Node.js (npx)
   npx serve .
   ```
3. Visit `http://localhost:8000`

## Deployment

- **GitHub Pages**: Push to a repo and enable Pages in Settings
- **Netlify**: Drag the folder to netlify.com/drop
- **Vercel**: Run `npx vercel` in the project directory

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge).
