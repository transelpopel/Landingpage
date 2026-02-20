# RepTrainer Landing Page

## Overview
Static HTML landing page for RepTrainer, an AI-powered sales training platform. Single-page marketing site with sections for features, pricing, how it works, and a lead capture form.

## Project Architecture
- **Type**: Static HTML website (single `index.html`)
- **Server**: `serve` (npm package) on port 5000
- **No backend or database required**

## Structure
- `index.html` - Complete landing page with inline CSS and JS
- `package.json` - Node.js config for the `serve` static file server

## Running
The site is served via `npx serve -s . -l 5000 --no-clipboard`.

## Deployment
Configured as a static site deployment serving the root directory.
