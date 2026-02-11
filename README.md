# ASAP Enterprises - Static Site Generator Projects

## Overview

This repository contains static site generator (SSG) projects for ASAP Enterprises. We use modern SSG frameworks to build fast, secure, and scalable websites.

## Repository Structure

```
asap-enterprises/
├── sites/              # Individual site projects
├── shared/             # Shared components and assets
│   ├── components/     # Reusable components
│   ├── styles/         # Global styles
│   └── utils/          # Utility functions
├── templates/          # Site templates
└── docs/               # Documentation
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager
- Git

### Installation

```bash
git clone https://github.com/asapklewis/asap-enterprises.git
cd asap-enterprises
npm install
```

## Supported SSG Frameworks

This repository supports multiple SSG frameworks:

- **Next.js** - React-based framework with SSG capabilities
- **Gatsby** - React-based SSG with GraphQL
- **Astro** - Modern SSG with component islands
- **Hugo** - Fast Go-based SSG
- **Eleventy (11ty)** - Simple JavaScript SSG

## Creating a New Site

To create a new site project:

```bash
cd sites
mkdir your-site-name
cd your-site-name
# Initialize your preferred SSG framework
```

## Development

```bash
# Navigate to your site directory
cd sites/your-site-name

# Start development server
npm run dev
```

## Building for Production

```bash
# Build your site
npm run build

# Preview production build
npm run preview
```

## Deployment

Sites can be deployed to:

- **Vercel** - Optimized for Next.js
- **Netlify** - Universal SSG hosting
- **GitHub Pages** - Free static hosting
- **AWS S3 + CloudFront** - Enterprise hosting

## Contributing

Please follow our contribution guidelines when adding new sites or shared components.

## License

Private repository - All rights reserved

## Contact

For questions or support, contact the ASAP Enterprises team.
