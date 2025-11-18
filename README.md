# Amos Bocelli - Personal Website

A clean, modern personal website with profile, bio, social media links, and an articles section.

## Features

- **Home Page**: Profile photo, bio, and social links (LinkedIn & X)
- **Articles Section**: Blog/article publishing system
- Responsive design that works on all devices
- Modern gradient background
- Animated effects and smooth transitions

## Structure

```
/
├── index.html          # Main homepage
├── articles.html       # Articles listing page
├── articles/           # Article files folder
│   ├── README.md       # Instructions for writing articles
│   ├── TEMPLATE.html   # Template for new articles
│   └── *.html          # Your published articles
├── css/
│   ├── styles.css      # Main styles
│   └── articles.css    # Article-specific styles
├── images/
│   └── Amos.png        # Profile photo
├── favicon_ab.ico      # Website favicon
├── .gitignore          # Git ignore file
└── README.md           # This file
```

## Customization

### Update Your Profile
1. **Profile Photo**: Replace `images/Amos.png` with your photo
2. **Bio**: Edit the bio text in `index.html` (line 23)
3. **Social Links**: Update LinkedIn and X URLs in `index.html`
4. **Tagline**: Modify the tagline under your name

### Writing Articles

See detailed instructions in `articles/README.md`, but here's the quick version:

1. **Copy the template**: Duplicate `articles/TEMPLATE.html`
2. **Rename it**: Use descriptive lowercase filename (e.g., `my-first-article.html`)
3. **Fill in content**: Replace all `[PLACEHOLDERS]` with your content
4. **Add to listing**: Add a card for your article in `articles.html`
5. **Preview**: Open the file in your browser

The dummy article `empowering-youth-through-technology.html` serves as a complete example.

## Local Development

Simply open `index.html` in your web browser to view the site locally.

To preview articles, navigate from the homepage or open `articles.html` directly.

## Deployment

This site can be deployed to any static hosting service such as:
- **GitHub Pages** - Free, easy setup
- **Netlify** - Free tier with automatic deployments
- **Vercel** - Free for personal projects
- Any web server that serves static files

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript (no dependencies!)
- Google Fonts (Inter)
- Font Awesome icons (CDN)
- Fully responsive with CSS Grid and Flexbox

## License

© 2025 Amos Bocelli. All rights reserved.