# Personal Website

Minimal personal website for Bill Van Leeuwen - Embedded Linux Developer.

## Features

- Clean, minimal dark theme with monospace font
- Link aggregator for LinkedIn, GitHub, and Blog
- Organized skills section with categories
- Responsive design
- No tracking or analytics

## Local Development

To view the site locally, start a simple HTTP server:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Deployment to GitHub Pages

1. Create a new repository on GitHub named `yourusername.github.io`

2. Add the remote and push:
```bash
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git branch -M main
git push -u origin main
```

3. Go to your repository settings on GitHub:
   - Navigate to **Settings** > **Pages**
   - Under **Source**, select **Deploy from a branch**
   - Select **main** branch and **/ (root)** folder
   - Click **Save**

4. Your site will be live at `https://yourusername.github.io` in a few minutes

## Customization

### Replace Placeholder Content

Before deploying, make sure to:

1. **Replace `image.png`** with your actual profile photo
2. **Update the About section** in `index.html` (currently lorem ipsum)

### Modify Skills

Edit the skills in `index.html` under each category. Skills are organized into:
- Languages
- Embedded & Systems
- Build Systems
- Protocols & Networking
- Tools

## Tech Stack

- Pure HTML/CSS (no frameworks)
- Monospace font
- Dark theme (#1a1a1a background)
- Mobile-responsive

## License

Feel free to use this template for your own personal site.
