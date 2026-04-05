# CSCA website package for csca-canada.ca

This package is a complete static website for **Chinese Students in Canada Alliance (CSCA)** with the domain already set to **csca-canada.ca**.

## What is already configured
- Root domain set to `csca-canada.ca`
- Standard public inboxes set to:
  - `info@csca-canada.ca`
  - `partnerships@csca-canada.ca`
  - `communications@csca-canada.ca`
- `CNAME` file included for GitHub Pages
- `robots.txt` and `sitemap.xml` included
- Multi-page website with:
  - Home
  - About
  - Programs
  - Institutional Development
  - Governance
  - Partnerships
  - Resources
  - FAQ
  - Contact
  - Privacy Policy
  - Terms of Use

## Before you publish
Edit `assets/site-config.js` if you want to change:
- city / province
- organization tagline
- legal status wording
- future direction wording

## Best next edits
1. Replace governance role placeholders with real names and titles.
2. Add your real city if you want something more specific than `Ontario`.
3. Keep the three public emails even if they are not active yet; they make the site look organized.
4. Add one or two real updates to `resources.html` after launch.

## Deploy on GitHub Pages
1. Upload all files to a public GitHub repository.
2. In repository settings, enable **GitHub Pages** from the `main` branch.
3. Make sure your domain DNS points to GitHub Pages.
4. Because `CNAME` is included, GitHub Pages will already know the custom domain is `csca-canada.ca`.

## DNS note
If you want the root domain `csca-canada.ca` on GitHub Pages, make sure your DNS provider is configured correctly for an apex domain.
If you prefer the `www` version later, update both the DNS and the `CNAME` file.
