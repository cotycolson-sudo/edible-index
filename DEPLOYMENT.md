# Deploying The Edible Index to Netlify

## Quick Start (Recommended)

1. **Push to GitHub**
   ```bash
   # Create a new repository on GitHub called "edible-index"
   # Then from your local directory:
   git remote add origin https://github.com/YOUR-USERNAME/edible-index.git
   git branch -M main
   git push -u origin main
   ```

2. **Connect to Netlify**
   - Go to [netlify.com](https://netlify.com) and sign in/sign up
   - Click "Add new site" → "Import an existing project"
   - Choose GitHub and select your `edible-index` repository
   - Build settings:
     - **Build command:** (leave empty)
     - **Publish directory:** `/` (root directory)
   - Click "Deploy site"

3. **Your Site is Live!**
   - Netlify will give you a random URL like `random-name-123.netlify.app`
   - You can change this to `edibleindex.netlify.app` in Site Settings → Domain Management → Options → Edit site name

## Alternative: Drag and Drop

If you prefer not to use Git/GitHub:

1. Go to [netlify.com](https://netlify.com) and sign in
2. Drag your entire `edible-index` folder onto the Netlify dashboard
3. Your site will deploy instantly at a random Netlify URL
4. Rename it to `edibleindex.netlify.app` in settings

## Custom Domain (Optional, ~$12/year)

If you want `edibleindex.com`:

1. Buy domain from Namecheap, Google Domains, etc.
2. In Netlify: Site Settings → Domain Management → Add custom domain
3. Update your domain's DNS settings with Netlify's nameservers
4. Netlify automatically provisions SSL certificate

## Short URLs for Social Sharing

### Free Options:
1. **Bitly** - Free tier gives 10 branded links/month
2. **TinyURL** - Completely free, no account needed
3. **is.gd** - Simple, free, no registration

### Example Usage:
- Long URL: `edibleindex.netlify.app/posts/kimchi-essay.html`
- Short URL: `bit.ly/edible-kimchi` or `tinyurl.com/edible-kimchi`

### Best Practice:
Create a consistent naming pattern:
- `bit.ly/edible-[topic]`
- Example: `bit.ly/edible-kimchi`, `bit.ly/edible-mole`, etc.

## Continuous Deployment

Once connected to GitHub:
- Every `git push` automatically deploys to Netlify
- Takes 20-30 seconds to build and publish
- Preview deploys for pull requests
- Rollback to any previous version instantly

## Adding New Posts

1. Create new HTML file in `posts/` directory
2. Use `sample-post.html` as template
3. Update navigation links as needed
4. Commit and push:
   ```bash
   git add posts/new-post.html
   git commit -m "Add new post: [Title]"
   git push
   ```
5. Site updates automatically!

## Environment Variables (Not needed yet)

If you add features later that need API keys:
- Site Settings → Environment Variables
- Add variables there (never commit API keys to Git)

## Analytics (Optional)

Netlify includes basic analytics, or integrate:
- Google Analytics (free)
- Plausible Analytics (privacy-focused, paid)
- Fathom Analytics (privacy-focused, paid)

## Performance Tips

- Netlify automatically serves files via CDN
- Images are currently SVG placeholders - replace with optimized JPGs/WebPs
- Consider image CDN like Cloudinary for large photo collections
- Netlify has built-in image optimization (paid feature)

## Troubleshooting

**Site not loading CSS/images:**
- Check that file paths are correct
- Use relative paths: `css/styles.css` not `/css/styles.css`

**Changes not showing:**
- Clear browser cache (Cmd/Ctrl + Shift + R)
- Check Netlify deploy log for errors

**404 errors:**
- Netlify automatically serves `404.html` if you create one
- Can redirect old URLs in `_redirects` file

## Next Steps

1. Replace placeholder images with real food photography
2. Create additional pages (archive.html, about.html, etc.)
3. Write your first real essay!
4. Set up custom domain if desired
5. Share on social media with short URLs

---

**Need help?** Netlify has excellent documentation at [docs.netlify.com](https://docs.netlify.com)
