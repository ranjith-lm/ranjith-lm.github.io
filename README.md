# Jekyll Blog - Ranjith's Tech Blog

A Jekyll-based blog for publishing articles about Salesforce development and cloud technologies.

## Quick Start

### Prerequisites
- Ruby (v2.7 or higher)
- Bundler

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ranjith-lm/ranjith-lm.github.io.git
cd ranjith-lm.github.io
```

2. Install dependencies:
```bash
bundle install
```

3. Run the local server:
```bash
bundle exec jekyll serve
```

4. Open your browser and go to `http://localhost:4000`

## Project Structure

```
.
├── _config.yml           # Site configuration
├── _posts/               # Blog post articles
├── _layouts/             # HTML layouts
├── index.md              # Home page
├── blog.md               # Blog listing page
├── about.md              # About page
├── Gemfile               # Ruby dependencies
└── Gemfile.lock          # Dependency lock file
```

## Creating a New Blog Post

Create a new file in the `_posts/` directory with the format: `YYYY-MM-DD-title-of-post.md`

```markdown
---
layout: post
title: "Your Post Title"
date: 2026-01-19
categories: [Category1, Category2]
tags: [tag1, tag2]
author: Your Name
description: "Brief description of your post"
---

Your content here...
```

## Publishing to GitHub Pages

Push your changes to the `main` branch:

```bash
git add .
git commit -m "Add new blog post"
git push origin main
```

Your blog will be available at `https://ranjith-lm.github.io`

## License

This project is open source and available under the MIT License.
