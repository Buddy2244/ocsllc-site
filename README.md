# Origin Code Systems LLC Website

Static landing page for Origin Code Systems LLC and Chiefs Desk, designed for straightforward deployment to Render from GitHub.

## Files

- `index.html` - Main landing page
- `privacy.html` - Basic privacy policy page
- `robots.txt` - Search engine crawl instructions
- `sitemap.xml` - Sitemap for deployed pages

## Local Preview

From this folder, run one of these commands:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Render Deployment

1. Push this folder to a GitHub repository.
2. In Render, create a new `Static Site`.
3. Connect the GitHub repository.
4. Set the publish directory to the repository root.
5. Leave the build command blank for this static site.
6. Deploy.

## Important Post-Deploy Update

Replace `https://your-domain.example` in `robots.txt` and `sitemap.xml` with your actual deployed domain.