# Rifat Chronicles

Personal blog and portfolio site for Rifat, PhD student at Rutgers University WINLAB.

## 🔧 Build Issues Fixed

This repository has been updated to resolve several build errors:

1. **Added Gemfile** - Proper dependency management for Jekyll
2. **Updated _config.yml** - Complete configuration with all required plugins
3. **Created missing pages** - Added `/about/` and `/year-archive/` pages
4. **Fixed markdown formatting** - Cleaned up triple asterisk formatting issues
5. **Added .gitignore** - Proper version control setup

## 🚀 Setup Instructions

### For GitHub Pages (Recommended)

1. Push these files to your GitHub repository
2. Go to repository Settings → Pages
3. Set Source to "Deploy from a branch"
4. Select "main" branch and "/" (root) folder
5. Click Save
6. Your site will be live at: `https://rifat-chronicles.github.io`

### For Local Development

```bash
# Install Ruby and Bundler first
# Then in your project directory:

bundle install
bundle exec jekyll serve
```

Your site will be available at `http://localhost:4000`

## 📁 Project Structure

```
.
├── _config.yml          # Main Jekyll configuration
├── _data/
│   └── navigation.yml   # Site navigation menu
├── _pages/             
│   ├── about.md        # About page
│   └── year-archive.md # Posts archive
├── _posts/             # Blog posts go here
│   └── 2026-02-19-travel-post-1.md
├── assets/
│   └── images/         # Site images
├── index.md            # Homepage
├── Gemfile             # Ruby dependencies
└── .gitignore         # Git ignore rules
```

## ✍️ Adding New Posts

Create a new file in `_posts/` with the format: `YYYY-MM-DD-post-title.md`

```markdown
---
title: "Your Post Title"
layout: single
header:
  teaser: /assets/images/your-image.jpg
excerpt: "Brief description"
categories:
  - Category Name
tags:
  - tag1
  - tag2
---

Your content here...
```

## 🎨 Theme

This site uses the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme with the "air" skin.

## 📸 Images

- Keep images in `/assets/images/`
- Consider optimizing large images (current images are ~20MB total)
- Recommended max size: 1-2MB per image

## 🐛 Troubleshooting

If builds fail on GitHub Pages:
- Check the Actions tab for build logs
- Ensure all image paths are correct
- Verify YAML front matter in all posts/pages is valid
- Make sure the repository name matches your GitHub username

## 📝 Notes

- Images should be optimized for web (consider compressing the current 20MB images)
- Update your email in `_config.yml` author section
- The site uses Jekyll 3.9.x (GitHub Pages version)

## 📚 Resources

- [Minimal Mistakes Documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
