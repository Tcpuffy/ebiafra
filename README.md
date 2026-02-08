# EBiafra - Historical Website

A non-fiction historical website dedicated to documenting and exploring the history of Biafra.

## About

EBiafra is a Jekyll-based static website hosted on GitHub Pages. It serves as a comprehensive resource for historical research, documentation, and education about the Biafran conflict and its historical context.

## Features

- Responsive design using Jekyll's Minima theme
- Blog-style articles about Biafran history
- Easy-to-navigate structure
- GitHub Pages integration

## Getting Started

### Local Development

1. Clone this repository:
```bash
git clone https://github.com/Tcpuffy/ebiafra.git
cd ebiafra
```

2. Install Jekyll (requires Ruby):
```bash
gem install jekyll bundler
```

3. Install dependencies:
```bash
bundle install
```

4. Serve locally:
```bash
bundle exec jekyll serve
```

5. Visit `http://localhost:4000` in your browser

### Viewing Live

The website is hosted at: `https://tcpuffy.github.io/ebiafra`

## File Structure

```
ebiafra/
├── _config.yml          # Jekyll configuration
├── _posts/              # Blog articles
├── _layouts/            # Page layouts
├── assets/              # CSS, images, etc.
├── index.md             # Homepage
├── blog.md              # Blog listing page
└── README.md            # This file
```

## Contributing

To add new content:

1. Create a new markdown file in `_posts/` with the naming convention: `YYYY-MM-DD-title.md`
2. Include proper front matter (title, date, author, categories)
3. Write your content in markdown
4. Push to the main branch

## Example Post Structure

```markdown
---
layout: post
title: "Your Article Title"
date: 2026-02-08
author: "Author Name"
categories: category1 category2
---

Your article content here...
```

## Enabling GitHub Pages

If GitHub Pages isn't automatically enabled:

1. Go to repository Settings
2. Scroll to "GitHub Pages"
3. Set source to "main" branch
4. Site will be published at `https://tcpuffy.github.io/ebiafra`

## Theme Customization

The site uses the Minima Jekyll theme. To customize:

1. Copy theme files to your repository
2. Edit `_config.yml` for basic settings
3. Modify CSS in `assets/` directory

## License

Please specify your preferred license

## Contact

For inquiries, contact through GitHub: [@Tcpuffy](https://github.com/Tcpuffy)

---

**Last Updated:** February 8, 2026