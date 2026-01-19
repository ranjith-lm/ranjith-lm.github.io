# Ranjith's Salesforce Development Blog

A Jekyll-based blog for publishing articles about Salesforce development.

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
├── _config.yml                    # Site configuration
├── _posts/                        # Blog post articles
├── assets/
│   └── images/                    # Blog post images
├── index.md                       # Home page
├── blog.md                        # Blog listing page
├── about.md                       # About page
├── Gemfile                        # Ruby dependencies
└── README.md                      # This file
```

## Creating a New Blog Post

### Step 1: Clone and Modify the Template

1. Copy the latest blog post file from `_posts/` folder
2. Rename it with the format: `YYYY-MM-DD-your-title.md`
3. Open the file and replace all "CHANGE THIS" sections:
   - **Title**: Update the `title` field in the front matter
   - **Date**: Update the `date` field
   - **Description**: Update the `description` field
   - **Image**: Replace `CHANGE_THIS_IMAGE.png` with your image name
   - **Content**: Replace all section content with your article
   - **Tags/Categories**: Update as needed

### Step 2: Add Your Image

1. Place your blog post image in the `assets/images/` folder
2. Update the image filename in the markdown frontmatter
3. Update the image path in the article body

### Step 3: Publish

```bash
git add .
git commit -m "Add new blog post: Your Title"
git push origin main
```

## Template Structure

Each blog post includes:
- **Front Matter**: Title, date, categories, tags, author, description, image
- **Header Image**: Visual representation of the post
- **Introduction**: Hook the reader
- **Main Sections**: 2-3 main content sections
- **Code Blocks**: For code examples (optional)
- **Tables**: For comparisons (optional)
- **Key Takeaways**: Summary of main points
- **Conclusion**: Call-to-action or wrap-up

## Publishing to GitHub Pages

Your blog will automatically deploy to `https://ranjith-lm.github.io` when you push to the main branch.

## License

This project is open source and available under the MIT License.
