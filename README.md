# Surendra Kumar S - Portfolio Website

A personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- Responsive design
- Smooth navigation
- Hero, About, Work, Services, and Contact sections
- Social media links (LinkedIn, GitHub, WhatsApp, Telegram)
- Custom fonts and modern color scheme

## Project Structure

```
My-Portfolio-Website/
├── website.html          # Main file
├── CSS/                  # Stylesheets (9 files)
├── Fonts/               # Custom fonts
├── images/              # Images
├── javascript/          # JavaScript files
└── README.md
```

## How to Use

1. Open `website.html` in your browser
2. Or use a local server:
   ```bash
   python -m http.server 8000
   # Then go to http://localhost:8000
   ```

## Sections

- **Header** - Navigation menu
- **Hero** - Welcome section
- **About** - Bio and tech stack
- **Work** - Portfolio projects
- **Services** - Services offered
- **Contact** - Get in touch
- **Footer** - Social links

## Customization

Edit `website.html` to update:
- Your name and bio
- Project descriptions
- Contact information
- Social media links

Change colors in CSS files by editing color variables:
```css
:root {
  --primary-color: rgba(255, 72, 72, 1);
  --secondary-color: rgba(0, 37, 116, 0.8);
}
```

## Known Issues

- Icons folder is missing (referenced in about section)
- Buttons don't have functional links yet
- Contact form not implemented

## Deployment

Deploy to GitHub Pages, Netlify, or Vercel:

**GitHub Pages:**
1. Push to GitHub
2. Go to Settings > Pages
3. Select main branch

**Netlify:**
1. Connect GitHub repo
2. Click Deploy

## Technologies

- HTML5
- CSS3
- JavaScript (Vanilla)
- Custom Fonts: Archivo, Satoshi

## Author

Surendra Kumar S

## License

MIT License - Free to use and modify
