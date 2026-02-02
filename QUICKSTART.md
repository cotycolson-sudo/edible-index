# The Edible Index - Quick Start Guide

## What You Have

✅ Complete blog structure with bookish, editorial design  
✅ Homepage with featured post and grid layout  
✅ Sample post showing essay + recipe format  
✅ Responsive design (works on mobile, tablet, desktop)  
✅ Git repository initialized  
✅ Ready to deploy to Netlify (free!)  

## Your Site URL (after deployment)

**Free Netlify subdomain:** `edibleindex.netlify.app`

## Immediate Next Steps

### 1. View Locally (Right Now!)

Open the `index.html` file in your browser to see the site.

Or run a local server:
```bash
cd edible-index
python -m http.server 8000
# Then visit: http://localhost:8000
```

### 2. Push to GitHub

```bash
# Create new repo on GitHub called "edible-index"
# Then:
cd edible-index
git remote add origin https://github.com/YOUR-USERNAME/edible-index.git
git branch -M main
git push -u origin main
```

### 3. Deploy to Netlify

1. Go to netlify.com and sign in
2. Click "Add new site" → "Import an existing project"
3. Choose GitHub → select "edible-index"
4. Leave build settings empty
5. Click "Deploy site"
6. Rename to `edibleindex.netlify.app` in settings

**Done! Your site is live.**

## Creating Your First Real Essay

### Step 1: Write the Essay
Copy `posts/sample-post.html` and rename it (e.g., `posts/kimchi-essay.html`)

### Step 2: Replace Content
- Update the title, meta tags
- Replace sample text with your writing
- Add your recipe
- Update cookbook information
- Replace placeholder images with real photos

### Step 3: Update Homepage
Edit `index.html`:
- Change featured post to point to your new essay
- Update title, excerpt, date
- Replace placeholder image

### Step 4: Deploy
```bash
git add .
git commit -m "Add first essay: [Your Title]"
git push
```

Netlify automatically publishes in ~30 seconds!

## Writing Structure (Your Essay Template)

1. **Hook/Access Point** - How you came to this cuisine  
2. **Context** - Cultural, historical, or personal background  
3. **Cookbook Introduction** - What makes this book significant  
4. **Recipe Deep Dive** - One recipe explored in depth  
5. **Broader Meaning** - What this reveals about food, culture, memory  
6. **Closing** - Return to access point, full circle  

**Length:** 1500-2500 words  
**Tone:** Academic yet conversational (think New Yorker food writing)

## Image Guidelines

Replace SVG placeholders with:
- **Featured image:** 800×600px (or larger, same ratio)
- **Card images:** 600×400px (or larger, same ratio)  
- **Cookbook cover:** 300×400px portrait
- **Format:** JPG or WebP, optimized for web

## Files to Create Next

- [ ] `archive.html` - Full chronological list of posts
- [ ] `cuisines.html` - Posts organized by cuisine tags
- [ ] `cookbooks.html` - Index of all cookbooks covered
- [ ] `about.html` - Your story and approach
- [ ] Real blog posts!

## Short URLs for Sharing

Use **Bitly** (bit.ly) or **TinyURL** for social sharing:

Example pattern:
- `bit.ly/edible-kimchi`
- `bit.ly/edible-mole`
- `bit.ly/edible-curry`

## Getting Help

**Documentation:**
- Netlify: docs.netlify.com
- Git basics: git-scm.com/book

**Questions?** Come back anytime - we can:
- Add new features
- Create additional pages
- Troubleshoot deployment
- Refine design elements
- Help with content structure

---

## Your Design Identity

**Typography:** Cormorant Garamond + Crimson Text (bookish serifs)  
**Colors:** Warm paper tones (cream, sepia, burgundy)  
**Aesthetic:** Library cookbook shelf meets editorial magazine  
**Vibe:** Intellectual but approachable, literary but practical

This isn't trying to be a recipe blog. It's a cultural research project that happens to involve cooking.

**Now go write something beautiful about kimchi.** 🥬
