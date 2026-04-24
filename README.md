# Jinseok Lee - Research Portfolio

Welcome to my research portfolio website! This site showcases my academic research, publications, and projects.

## Quick Start Guide

### 1. Enable GitHub Pages

1. Go to your repository settings: https://github.com/JinseokLee9706/Jinseoklee.github.io/settings/pages
2. Under "Build and deployment":
   - **Source**: Select `Deploy from a branch`
   - **Branch**: Select `main` and `/root`
3. Click "Save"
4. Your site will be live at: `https://JinseokLee9706.github.io`

### 2. Customize Your Portfolio

#### Edit `index.html`:
- Replace `Jinseok Lee` with your name
- Update research interests in the "Research Interests" section
- Add your publications in the "Publications" section
- Add your projects in the "Projects" section
- Update contact information and social links

#### Key sections to customize:

```html
<!-- Update your name -->
<h1 class="logo">Your Name Here</h1>

<!-- Update research interests -->
<h3>Your Research Topic 1</h3>
<p>Description of your research focus</p>

<!-- Add publications -->
<h3><a href="#">Your Paper Title</a></h3>
<p class="meta">Your Name, Co-authors | Journal/Conf | Year</p>

<!-- Add projects -->
<h3>Your Project Name</h3>
<a href="https://github.com/yourrepo">View on GitHub</a>
```

### 3. Add a Bio Section (Optional)

You can add a "Bio" or "About Me" section by adding this to `index.html`:

```html
<section id="about" class="about">
    <div class="container">
        <h2>About Me</h2>
        <p>Your bio here...</p>
    </div>
</section>
```

### 4. File Structure

```
Jinseoklee.github.io/
├── index.html          # Main page
├── styles.css          # Styling
├── README.md           # This file
└── .gitignore          # Git ignore file
```

### 5. Making Changes

1. Edit files directly in GitHub or clone locally:
   ```bash
   git clone https://github.com/JinseokLee9706/Jinseoklee.github.io.git
   cd Jinseoklee.github.io
   ```

2. Make changes and commit:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push
   ```

3. Your site will automatically update within seconds!

## Customization Tips

### Change Color Scheme
Edit `styles.css` and modify these colors:
- `#667eea` - Primary color (purple-blue)
- `#764ba2` - Secondary color (purple)
- `#333` - Dark text

### Add More Sections
Follow the same pattern:
```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2>Section Title</h2>
        <!-- Content here -->
    </div>
</section>
```

### Add More Publications
Copy the publication-item template:
```html
<article class="publication-item">
    <h3><a href="#">Paper Title</a></h3>
    <p class="meta">Authors | Venue | Year</p>
    <p class="abstract">Brief abstract</p>
    <div class="links">
        <a href="#">PDF</a>
        <a href="#">arXiv</a>
        <a href="#">DOI</a>
    </div>
</article>
```

## Useful Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Markdown Guide](https://www.markdownguide.org/)

## Support

For issues or questions about GitHub Pages, visit:
- [GitHub Pages Help](https://docs.github.com/en/pages)
- [GitHub Community Support](https://github.community/)

---

**Last Updated**: 2026-04-24
