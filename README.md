# Earth Scope Company Ltd — Surveying Website

A responsive multi-page website for **Earth Scope Company Ltd**, showcasing professional land surveying, engineering survey, land planning, utility mapping, sectional property, mutation, deed plan, agricultural survey, and property consultancy services.

## Project status

This repository is currently being upgraded from an early static prototype into a polished, deployment-ready business website.

### Current pages

- Home
- About Us
- Projects
- Deed Plans
- Mutation Surveys
- Sectional Property Surveys
- Engineering Surveys
- Pipeline Surveys
- Water & Power Line Surveys
- Land Planning
- Rural & Agricultural Surveys
- General Property Consultancy

## Tech stack

- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Font Awesome
- Google Maps integration placeholder

## Planned improvements

- Replace placeholder contact information with real company details
- Replace the placeholder Google Maps API configuration
- Improve mobile navigation and responsive spacing
- Standardize the header, navigation, footer, and page branding
- Add stronger calls to action such as **Request a Survey**, **Get a Quote**, and **WhatsApp Us**
- Improve project portfolio cards with real project descriptions and categories
- Add a dedicated contact / quotation form
- Add SEO metadata and social sharing metadata
- Improve accessibility, semantic HTML, and alt text
- Optimize large images for faster loading
- Add consistent animations and modern visual styling
- Add a proper homepage entry point for deployment
- Validate all links and remove duplicated/broken HTML
- Prepare the site for Netlify or GitHub Pages deployment

## Running locally

Because this is currently a static website, no build step is required.

1. Clone the repository.
2. Open the project folder in VS Code.
3. Open `home.html` directly in your browser, or use the VS Code **Live Server** extension.

## Deployment

The finished website can be deployed using:

- GitHub Pages
- Netlify
- Cloudflare Pages
- Any standard static web host

For production deployment, the recommended homepage should be renamed or copied to `index.html`.

## Important configuration

The current Google Maps implementation still contains a placeholder API key:

```
YOUR_API_KEY
```

Replace it with a properly restricted Google Maps JavaScript API key before production deployment.

## Repository structure

```
survey-_website-/
├── Images/
├── home.html
├── about.html
├── project.html
├── deed.html
├── mut.html
├── sectionalprop.html
├── eng.html
├── pipe.html
├── waterpower.html
├── landplan.html
├── agri.html
├── landconsult.html
├── styles.css
└── README.md
```

## Development roadmap

### Phase 1 — Stabilize
- Fix malformed HTML and broken navigation
- Standardize shared visual components
- Ensure every service page is reachable
- Fix image paths and responsive behavior

### Phase 2 — Professional business experience
- Modern hero section
- Trust / credentials section
- Services overview
- Process section explaining how a survey engagement works
- Projects / portfolio showcase
- Testimonials
- Quote request and contact experience
- WhatsApp and phone CTAs

### Phase 3 — Production readiness
- SEO
- Performance optimization
- Accessibility review
- Real map/location configuration
- Real business contact details
- Analytics
- Production deployment

## License

This project is currently maintained as a private business/portfolio implementation unless a separate license is added.
