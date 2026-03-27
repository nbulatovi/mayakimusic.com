# Mayaki Music Website

## Project Overview
Official website for Mayaki Music (DJ/producer/music artist). Currently a "Coming Soon" landing page.

## Repository
- **GitHub**: https://github.com/nbulatovi/mayakimusic.com
- **Live site**: https://mayakimusic.com

## Hosting & Deployment
- Hosted on **GitHub Pages** (legacy build from `main` branch, root `/`)
- Custom domain configured via `CNAME` file (`mayakimusic.com`)
- DNS managed on **Namecheap** (Advanced DNS tab)

### DNS Records (Namecheap)
- 4x A records (`@`) pointing to GitHub Pages IPs: `185.199.108-111.153`
- 1x CNAME record (`www`) pointing to `nbulatovi.github.io`

## File Structure
- `index.html` — Single-page coming soon site (Outfit font, dark theme)
- `CNAME` — Custom domain config for GitHub Pages
- `.gitignore`

## Notes
- HTTPS enforcement should be enabled in GitHub Pages settings once the SSL certificate is provisioned (Settings > Pages > Enforce HTTPS)
- Any push to `main` triggers a GitHub Pages rebuild automatically
