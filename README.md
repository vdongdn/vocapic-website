# VocaPic Website — Privacy Policy & Terms of Use

Static website for VocaPic app store submissions. Contains landing page, privacy policy, and terms of use.

## Files

| File | Description |
|------|-------------|
| `index.html` | Landing page with app features |
| `privacy.html` | Privacy Policy |
| `terms.html` | Terms of Use |
| `style.css` | Shared styles |

## Deploy to GitHub Pages (Recommended)

### Option 1: Separate Repository

1. **Create a new GitHub repository** named `vocapic-website` (or `vocapic.github.io` for custom domain):
   ```bash
   cd website
   git init
   git add .
   git commit -m "Initial website deployment"
   git remote add origin https://github.com/YOUR_USERNAME/vocapic-website.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to repository **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)`
   - Click **Save**

3. **Your site will be live at**:
   `https://YOUR_USERNAME.github.io/vocapic-website/`

### Option 2: From this repo (using `/docs` or subtree)

1. Push the `website/` folder to your existing repo
2. In **Settings** → **Pages**, set source to branch `main` and folder `/website`

## Deploy to Google Sites

Google Sites doesn't support custom HTML directly. Instead:

1. Create a new Google Site at [sites.google.com](https://sites.google.com)
2. Add pages: "Privacy Policy" and "Terms of Use"
3. Copy the text content from the HTML files into the Google Sites editor
4. Publish the site

> **Note**: GitHub Pages is recommended over Google Sites because it preserves the exact HTML/CSS styling.

## Customization Checklist

Before deploying, update these items:

- [ ] **Email address**: Replace `vocapic.app@gmail.com` with your actual contact email
- [ ] **App Store links**: Replace `#` in `index.html` hero badges with actual store URLs
- [ ] **Logo**: Replace the SVG placeholder with your actual app icon (add `favicon.png`)
- [ ] **Copyright year**: Update if needed
- [ ] **App name**: Confirm "VocaPic" is correct throughout

## URLs for App Store Submissions

After deploying, use these URLs in your store listings:

- **Privacy Policy URL**: `https://YOUR_USERNAME.github.io/vocapic-website/privacy.html`
- **Terms of Use URL**: `https://YOUR_USERNAME.github.io/vocapic-website/terms.html`
- **Website URL**: `https://YOUR_USERNAME.github.io/vocapic-website/`
