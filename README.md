# FedRAMP Cybersecurity Service Recruiting Site

https://fedramp.gov/join

## AI Generated About

This project showcases the FedRAMP Cybersecurity Service that hires cloud security engineers for 2 year government terms. The site is built with [Zensical](https://zensical.dev/), a modern static site generator based on Material for MkDocs.

## Quick Start

### Prerequisites
- Python 3.10 or later
- Zensical (installed via pip)

### Building the Site

```bash
# Install dependencies
pip install zensical

# Build the site
zensical build
```

The site will be generated in the `html/` directory.

### Local Preview

```bash
zensical serve
```

Then open http://localhost:8000 in your browser.

## Project Structure

```
├── markdown/           # Source markdown pages
│   └── index.md       # Main landing page
├── overrides/         # Theme customizations
│   ├── main.html      # Custom HTML template
│   └── stylesheets/   # Custom CSS
├── html/              # Generated static site
├── zensical.toml      # Site configuration
└── README.md          # This file
```

## Configuration

The site is configured in `zensical.toml`. Key settings include:

- **Site metadata**: Name, description, author
- **Navigation**: Menu structure and links
- **Theme**: Material theme with custom features
- **Styling**: Custom CSS for typography and layout

## Customization

### Adding Pages

1. Create a new `.md` file in the `markdown/` directory
2. Update the navigation in `zensical.toml`
3. Rebuild the site with `zensical build`

### Styling

Custom CSS is in `overrides/stylesheets/custom.css`. This file customizes typography (Merriweather font) and heading weights.

## Deployment

The generated `html/` directory contains the complete static site and can be deployed to any web hosting service (GitHub Pages, AWS S3, etc.).

## Contact

For questions about the FedRAMP Cybersecurity Service recruiting program, reach out to pete@fedramp.gov
