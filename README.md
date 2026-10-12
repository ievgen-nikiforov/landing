# The MET Landing Page

A responsive museum landing page showcasing The Met Fifth Avenue and The Met
Cloisters. Visitors can browse featured exhibitions, explore online collections
and tours, and find museum hours and contact information.

## Live Preview

[The MET landing page](https://ievgen-nikiforov.github.io/landing/)

Deployment pending: this URL returned HTTP 404 when checked on October 12, 2026.
Once the site is published, verify that it loads and works in an incognito window
without signing in.

## Technologies Used

- HTML5 for page structure and native form validation.
- SCSS (Sass) for styles, reusable mixins, and responsive layouts.
- CSS Grid and Flexbox for positioning content.
- Parcel for development and production builds.
- npm for dependency management and project scripts.
- ESLint, Stylelint, and Linthtml for code quality checks.

## Getting Started

Install Node.js and npm before running the following commands.

1. Clone the repository:

   ```bash
   git clone https://github.com/ievgen-nikiforov/landing.git
   cd landing
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the local development server:

   ```bash
   npm start
   ```

   Open the local URL printed in the terminal.

To create a production build:

```bash
npm run build
```

To run code quality checks:

```bash
npm run lint
```

## Features

- Responsive layouts for mobile, tablet, and desktop screens.
- Slide-in navigation menu and smooth scrolling between sections.
- Featured exhibition galleries and online exploration cards.
- Opening hours and contact details for both museum locations.
- Clickable phone numbers and links to locations on Google Maps.
- Contact form with required fields and email validation. The form resets after
  submission; it does not send messages to a server.
