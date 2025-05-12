# Deck Masters AK Website

This repository contains the source code for the Deck Masters AK website, Anchorage's premier deck building company.

## Project Overview

Deck Masters AK specializes in custom deck design and construction in Anchorage, Alaska. This website showcases their services, portfolio, team, and customer testimonials.

## Features

- Responsive design for all device sizes
- Modern UI with Tailwind CSS
- Multi-page structure with dedicated sections for:
  - Home page with hero section and service highlights
  - Services page detailing all offerings
  - Portfolio page showcasing completed projects
  - Team page introducing the company staff
  - Videos page with project showcases
- Contact form integration
- Customer testimonials
- Image galleries

## Tech Stack

- HTML5
- CSS3 (with Tailwind CSS)
- JavaScript (Vanilla)
- Vite.js (Build tool)
- Netlify (Deployment)

## Project Structure

```
002-DeckMasters-website-repo/
├── index.html              # Home page
├── services.html           # Services page
├── portfolio.html          # Portfolio page
├── team.html               # Team page
├── videos.html             # Videos page
├── src/                    # Source JavaScript files
│   ├── main.js             # Main JavaScript for the site
│   ├── counter.js          # Counter functionality
│   └── videos.js           # Videos page functionality
├── package.json            # Project dependencies
├── package-lock.json       # Locked dependencies
├── vite.config.js          # Vite configuration
└── netlify.toml            # Netlify deployment configuration
```

## Getting Started

### Prerequisites

- Node.js (v14.18.0 or higher)
- npm (v8.0.0 or higher)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd DeckMasters
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Building for Production

To build the project for production:

```bash
npm run build
```

This will generate optimized files in the `dist` directory.

## Deployment

The site is configured for deployment on Netlify. The `netlify.toml` file contains the necessary configuration.

To deploy:

1. Push changes to the main branch
2. Netlify will automatically build and deploy the site

## Content Management

The website content is primarily managed through HTML files. Key content areas:

- Service descriptions in `services.html`
- Project showcases in `portfolio.html`
- Team member information in `team.html`
- Video content in `videos.html` and `src/videos.js`

## Browser Support

The website is designed to work on all modern browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

[Specify license information here]

## Contact

[Specify contact information here]
