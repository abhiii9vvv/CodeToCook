# CodeToCook Restaurant Website

A responsive multi‑page restaurant website that fuses programming culture with culinary creativity.

## Features

- **Responsive Design**: Optimized for mobile and desktop
- **Interactive Menu**: Categorized dishes with images
- **Chef Profiles**: Team showcase with specialties
- **Photo Gallery**: Lightbox viewer with descriptions
- **Modern UI**: Glass morphism effects, smooth animations
- **Location Map**: Interactive contact section

## Tech Stack

- HTML5 for structure
- CSS3 for styling (glass effects, responsive grids)
- Vanilla JavaScript (mobile nav, lightbox, maps)
- No external dependencies

## Structure

```
CodeToCook/
├── src/                  # Source files
│   ├── About/           # About Us page
│   ├── Chef/            # Chef profiles
│   ├── Gallery/         # Photo gallery
│   ├── Menu/            # Restaurant menu
│   ├── images/          # Shared assets
│   └── main-page/       # Home page
├── .github/             # GitHub Actions
├── index.html          # Entry point
├── netlify.toml        # Netlify config
└── vercel.json         # Vercel config
```

## Setup & Deployment

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/abhiii9vvv/CodeToCook.git
   cd CodeToCook
   ```

2. Local Development:
   ```bash
   # Using Python
   python -m http.server 3000
   # OR using PHP
   php -S localhost:3000
   ```

3. Visit `http://localhost:3000`

### Deployment Options

#### Vercel
1. Import to Vercel:
   - Go to https://vercel.com
   - New Project → Import Git Repository
   - Select the repository
   - Deploy

#### Netlify
1. Deploy on Netlify:
   - Go to https://netlify.com
   - Add new site → Import existing project
   - Select the repository
   - Deploy

#### GitHub Pages
1. Enable GitHub Pages:
   - Go to repository Settings
   - Pages → Build and deployment
   - Source: "Deploy from a branch"
   - Branch: "main" → Save

## Customization

- Replace images in `images/` or update remote URLs
- Modify styles in CSS files for each section
- Add chef profiles in `Chef/chef.html`
- Update menu items in `Menu/menu.html`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

MIT License - Feel free to use for personal/educational purposes.
