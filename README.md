# Personal Website

A minimalist personal website and blog built with Jekyll.

## Getting Started

### Prerequisites

- Ruby (version 2.5 or higher)
- Bundler

### Installation

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

3. Open your browser and visit `http://localhost:4000`

## Creating Blog Posts

Create a new file in the `_posts` directory with the following naming convention:
```
YYYY-MM-DD-title-of-post.md
```

Add front matter at the top of the file:
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
---
```

Then write your content in Markdown below the front matter.

## Customization

- Update site information in `_config.yml`
- Modify styles in `assets/css/style.css`
- Edit the homepage in `index.html`
- Customize the layout in `_layouts/default.html`

## Deployment

This site can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

## License

See LICENSE file for details.
