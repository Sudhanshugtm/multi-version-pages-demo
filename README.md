# Multi-Version Pages Demo

This repository demonstrates how to host multiple versions of a webpage using GitHub Pages from a single repository.

## 🚀 Live Demo

Once GitHub Pages is enabled, you can access the site at:
- Main page: `https://sudhanshugtm.github.io/multi-version-pages-demo/`
- Version 1: `https://sudhanshugtm.github.io/multi-version-pages-demo/v1/`
- Version 2: `https://sudhanshugtm.github.io/multi-version-pages-demo/v2/`
- Version 3: `https://sudhanshugtm.github.io/multi-version-pages-demo/v3/`

## 📁 Repository Structure

```
.
├── index.html          # Main landing page with links to all versions
├── v1/
│   └── index.html     # Version 1: Minimalist Design
├── v2/
│   └── index.html     # Version 2: Modern Dark Theme
├── v3/
│   └── index.html     # Version 3: Colorful & Playful
└── .github/
    └── workflows/
        └── static.yml  # GitHub Pages deployment workflow
```

## 🎨 Design Variations

1. **Version 1 - Minimalist Design**
   - Clean, sans-serif typography
   - Monochromatic color scheme
   - Focus on content and readability

2. **Version 2 - Modern Dark Theme**
   - Dark background with vibrant gradients
   - Smooth animations and transitions
   - Card-based layout

3. **Version 3 - Colorful & Playful**
   - Animated gradient background
   - Fun animations and emoji elements
   - Bright, vibrant colors

## 🛠️ How It Works

1. **Single Repository**: All versions are stored in one GitHub repository
2. **Subdirectories**: Each version lives in its own folder (v1/, v2/, v3/)
3. **GitHub Pages**: Serves all content from the repository
4. **URL Structure**: Each subdirectory becomes a path in the URL

## 💡 Benefits

- **Easy Testing**: Test multiple design variations without creating separate repositories
- **Single Branch**: All versions can be managed from the main branch
- **Version Control**: Track changes to all versions in one place
- **Simple Navigation**: Landing page provides easy access to all versions

## 🚦 Setting Up GitHub Pages

GitHub Pages should automatically deploy when you push to the main branch. If you need to manually enable it:

1. Go to Settings → Pages
2. Source: Deploy from a branch
3. Branch: main
4. Folder: / (root)
5. Save

The GitHub Actions workflow will handle the deployment automatically.

## 📝 Adding More Versions

To add a new version:

1. Create a new directory (e.g., `v4/`)
2. Add an `index.html` file in that directory
3. Update the main `index.html` to include a link to the new version
4. Push to the main branch

## 🔧 Customization

Feel free to:
- Modify the designs in each version
- Add more files (CSS, JS, images) to each version directory
- Create nested subdirectories for more complex structures
- Add version-specific assets and resources

---

Created with ❤️ to demonstrate GitHub Pages multi-version hosting