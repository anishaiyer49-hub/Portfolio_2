# Portfolio Website

A personal portfolio website showcasing design work and creative projects with an elegant, vintage-inspired aesthetic.

## Overview

This portfolio website features a multi-page layout with smooth navigation, displaying various design projects including posters, zines, card games, and fashion magazines. The site uses a cohesive pink and pastel color scheme with decorative elements throughout.

## Project Structure

```
portfolio/
├── cover page/
│   ├── index.html          # Landing page with animated title
│   └── cover.css
├── about me/
│   ├── aboutme.html        # About page with illustrations
│   └── aboutme.css
├── index_page/
│   ├── tableofcontent.html # Table of contents with mind map
│   └── tableofcontent.css
├── preview/
│   ├── preview.html        # Work gallery overview
│   ├── preview.css
│   ├── poster.html         # Gardening book poster detail
│   ├── zine.html           # White Lotus zine detail
│   ├── card.html           # Card game detail
│   └── fashion.html        # Fashion magazine detail
└── assets/
    └── images/             # Project images and illustrations
```

## Pages

### Home (index.html)
- Animated landing page with spinning decorative frame
- Clean, minimal design with custom typography
- Entry point to the portfolio

### About Me (aboutme.html)
- Personal introduction page
- Illustrated with custom graphics (earphones, keychain decorations)
- Pink poster background

### Content (tableofcontent.html)
- Table of contents with mind map visualization
- Browser-styled interface design
- Navigation hub for the portfolio

### Work (preview.html)
- Gallery view of all projects
- Interactive preview cards for:
  - Gardening Book Poster
  - White Lotus Zine
  - Card Game Design
  - Fashion Magazine
- Each card links to detailed project pages

## Features

- **Consistent Navigation**: Fixed navbar across all pages for easy site traversal
- **Responsive Design**: Mobile-friendly layouts using viewport meta tags
- **Custom Styling**: Unique aesthetic with pastel backgrounds and decorative elements
- **Project Details**: Individual pages for each work with full-size images
- **Bootstrap Integration**: Uses Bootstrap 5.3.0 for layout and styling on detail pages

## Technologies Used

- HTML5
- CSS3
- Bootstrap 5.3.0 (CDN)
- Google Fonts (Monsieur La Doulaise, Poppins)

## Setup

1. Clone or download the repository
2. Ensure all image assets are in their respective folders
3. Open `index.html` in your browser to view the site
4. No build process or dependencies required - pure HTML/CSS

## Navigation Structure

```
Home → About Me
  ↓      ↓
Content → Work → Individual Projects
  ↑      ↑
  └──────┘
```

All pages include a navbar with links to:
- Home
- About Me
- Content
- Work

## Color Scheme

- **Main Background**: Pink poster aesthetic (#f6e7f4, #e0e6f1, #f7f4da, #dcebd9)
- **Text**: Black
- **Accent**: Pastel variations per project

## Browser Compatibility

Works best in modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Future Enhancements

Consider adding:
- Smooth scroll animations
- Image lightbox for project details
- Contact form or email link
- Social media links
- More interactive elements
- Project descriptions and captions
