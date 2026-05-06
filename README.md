# Proxima Novum Website

A secure, responsive, professional static website for the Proxima Novum / NOVUM IMPACTA brand and its suite of productivity apps for African SMEs.

## Project Structure

- `index.html`: Main landing page with hero, apps overview, and contact sections.
- `privacy.html`: Detailed Privacy Policy page.
- `apps/`: Individual detail pages for each app.
- `styles.css`: Core design system and responsive layouts.
- `script.js`: Basic interactivity and smooth scrolling.
- `assets/images/`: Directory for icons and screenshots.
- `_headers`: Security headers for Netlify deployment.
- `_redirects`: Redirect rules for Netlify.
- `robots.txt` & `sitemap.xml`: SEO configuration.

## How to Use

### 1. Replace Placeholders
The website uses placeholders for images. You should add your real assets to `assets/images/`:
- **App Icons**: Replace the `app-icon-placeholder` divs in HTML with `<img>` tags pointing to your icons (e.g., `tailorpro-icon.png`).
- **Screenshots**: Replace the gallery placeholders in the app detail sections and pages with your real app screenshots.
- **Favicon**: Add a `favicon.png` to `assets/images/`.
- **Social Sharing**: Add an `og-image.png` (1200x630px) for social media previews.

### 2. Update Links
- **WhatsApp**: Search for `+234XXXXXXXXXX` in `index.html` and replace it with your actual support number.
- **Download Links**: Update the `#` links in the download buttons with your actual Google Play, Palmstore, or APK download URLs.

### 3. Deployment to Netlify
1. Log in to your [Netlify](https://www.netlify.com/) account.
2. Click **Add new site** > **Deploy manually**.
3. Drag and drop the entire `proxima-novum-web` folder into the upload area.
4. Netlify will automatically detect the `_headers` and `_redirects` files for security and routing.

## Security Features
- **CSP (Content Security Policy)**: Restricts where scripts and styles can be loaded from.
- **X-Frame-Options**: Prevents your site from being embedded in iframes (clickjacking protection).
- **Permissions-Policy**: Disables access to camera, microphone, and location for maximum user privacy.
- **Referrer-Policy**: Protects user privacy when navigating to external links.

## SEO & Accessibility
- Semantic HTML tags (header, main, section, footer).
- Proper meta tags for search engines and social media.
- Mobile-first responsive design.
- Fast-loading static architecture.
