# G-RAMA Turnstile Ltd — Website

Official corporate website for **G-RAMA Turnstile Ltd**, deployed automatically via **GitHub Pages** with **Jekyll**.

**Live URL:** [https://gramaturnstile.com](https://gramaturnstile.com)

---

## Overview

This repository contains the complete static website for G-RAMA Turnstile Ltd — a multidisciplinary solutions provider delivering integrated expertise across access control & security systems, smart IT and automation, sustainable agriculture, infrastructure development, and strategic procurement.

## Technology Stack

- **Jekyll** — Static site generator (GitHub Pages native)
- **GitHub Actions** — CI/CD build and deployment pipeline
- **Custom Domain** — `gramaturnstile.com` (DNS verified + SSL)
- **HTML5 / CSS3 / JavaScript** — Custom template, no external theme

## Project Structure

| Path | Description |
|------|-------------|
| `index.html` | Home page |
| `home.html` | Alternate home landing |
| `about.html` | About / Company overview |
| `services.html` *(planned)* | Services & divisions |
| `projects.html` | Portfolio / Projects |
| `project-details.html` | Individual project case studies |
| `contact.html` | Contact page + form + FAQ |
| `website-content.md` | Master content reference document |
| `_config.yml` | Jekyll site configuration |
| `CNAME` | Custom domain pointer |
| `.github/workflows/pages.yml` | GitHub Actions deployment workflow |

## Local Development

### Prerequisites

- Ruby 3.1+
- Bundler

### Setup

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Open in browser
open http://localhost:4000
```

## Deployment

Pushing to the `main` branch automatically triggers the GitHub Actions workflow (`.github/workflows/pages.yml`), which builds the Jekyll site and deploys it to GitHub Pages.

**No manual build step is required.**

### Custom Domain

- Domain: `gramaturnstile.com`
- DNS: A records / CNAME configured and verified
- SSL: Automatically provisioned by GitHub Pages

## Contact

- **Company:** G-RAMA Turnstile Ltd
- **Address:** Flat B15, Block B, Wing B, Katampe Estate, FCT, Abuja
- **Phone:** +234 814 546 5852
- **Email:** info@gramaturnstile.com
- **Website:** https://gramaturnstile.com

---

© 2026 G-RAMA Turnstile Ltd. All rights reserved.
