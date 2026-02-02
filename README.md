# The Edible Index

**How do you eat a library?**

A blog exploring cookbooks as cultural touchstones, cooking as research, and the ways food intersects with heritage, memory, faith, politics, and identity.

## About

The Edible Index approaches food through access points: Korean food through residence life and H-Mart trips with exchange students, Indian food through the Hare Krishna movement, Chinese food through vegetarianism. Each essay examines a cookbook not just as a recipe collection, but as a cultural artifact that carries meaning, memory, and transformation.

## Design Philosophy

The site features a warm, bookish aesthetic inspired by library shelves and aged cookbook pages:
- Serif typography (Cormorant Garamond and Crimson Text)
- Warm, aged paper color palette (cream, sepia, burgundy)
- Editorial layout with generous spacing
- Recipe cards integrated into essay format
- Responsive, mobile-friendly design

## Structure

```
edible-index/
├── index.html              # Homepage with featured and recent posts
├── archive.html            # Full post archive (to be created)
├── cuisines.html           # Posts organized by cuisine (to be created)
├── cookbooks.html          # Index of cookbooks covered (to be created)
├── about.html              # About page (to be created)
├── css/
│   ├── styles.css          # Main site styles
│   └── post.css            # Post-specific styles
├── js/
│   └── main.js             # JavaScript functionality
├── posts/
│   └── sample-post.html    # Example post template
└── images/                 # Images and photography
```

## Content Format

Each post includes:
- **Essay**: Long-form cultural writing about the cookbook and its context
- **Featured Recipe**: One recipe from the book, fully formatted
- **Cookbook Information**: Details about the book, author, and significance
- **Metadata**: Cuisine tags, date, cookbook title

## Development

Built with:
- Pure HTML5, CSS3, and vanilla JavaScript
- No frameworks or build process required
- Google Fonts (Cormorant Garamond, Crimson Text)
- Responsive design with CSS Grid and Flexbox

### Local Development

1. Clone the repository
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   # or
   npx live-server
   ```

## Deployment

Designed to deploy on Netlify:
1. Connect repository to Netlify
2. No build command needed
3. Publish directory: `/` (root)
4. Free subdomain: `edibleindex.netlify.app`

## Content Guidelines

- Essays should be 1500-2500 words
- Focus on cultural context, not just recipe review
- Include personal access point to the cuisine
- Feature one recipe per essay minimum
- Use high-quality food photography
- Tag posts by cuisine and theme

## Future Enhancements

- RSS feed generation
- Search functionality
- Social media meta tags
- Image optimization
- Custom domain option
- Newsletter integration

## License

Content © 2026 The Edible Index. All rights reserved.

---

*Built with care, one cookbook at a time.*
