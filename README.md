# InboxKeep Website

This folder contains the static website for InboxKeep, hosted on GitHub Pages.

## Files

- `index.html` - Home page with features and download information
- `privacy.html` - Privacy Policy
- `terms.html` - Terms of Service
- `style.css` - Stylesheet
- `CNAME` - Custom domain configuration (add your domain here)

## Deployment

1. Create a new GitHub repository named `inboxkeep` under the `aigamer-dev` organization
2. Copy the contents of this `site/` folder to the repository root
3. Enable GitHub Pages in repository settings (Settings > Pages > Source: main branch)
4. Add your custom domain in the GitHub Pages settings
5. Update DNS records with your domain registrar

## Custom Domain Setup

1. In the repository, go to Settings > Pages > Custom domain
2. Add your domain (e.g., `inboxkeep.app`)
3. Create the following DNS records:
   - A record pointing to GitHub Pages IPs
   - CNAME record for www subdomain

## Local Development

Simply open `index.html` in a web browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## License

MIT License - See main project repository for details.