# Physics Blog

A modern physics blog built with Hugo and the PaperMod theme, exploring physics, mathematics, and scientific discovery.

## 🚀 Live Site

Visit the live site: [https://janithmalinga.github.io/physics-blog/](https://janithmalinga.github.io/physics-blog/)

## 📖 About

This blog covers various topics in physics and mathematics, from quantum mechanics to relativity, designed to make complex scientific concepts accessible to everyone.

## 🛠️ Built With

- **[Hugo](https://gohugo.io/)** - Static site generator
- **[PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod)** - Clean and responsive theme
- **GitHub Pages** - Hosting and deployment

## 🏃‍♂️ Getting Started

### Prerequisites

- Hugo (Extended version recommended)
- Git

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/janithmalinga/physics-blog.git
   cd physics-blog
   ```

2. Initialize and update submodules:
   ```bash
   git submodule update --init --recursive
   ```

3. Start the development server:
   ```bash
   hugo server -D
   ```

4. Open your browser and visit `http://localhost:1313`

### Creating New Posts

Create new blog posts in the `content/posts/` directory:

```bash
hugo new posts/my-new-post.md
```

## 📁 Project Structure

```
physics-blog/
├── archetypes/          # Post templates
├── assets/              # Asset files
├── content/             # Content files
│   ├── posts/           # Blog posts
│   └── _index.md        # Homepage content
├── layouts/             # Custom layouts (if any)
├── static/              # Static files
├── themes/              # Hugo themes
│   └── PaperMod/        # PaperMod theme
├── hugo.toml           # Hugo configuration
└── README.md           # This file
```

## 🎨 Customization

### Configuration

Edit `hugo.toml` to customize:
- Site title and description
- Author information
- Social media links
- Menu structure
- Theme settings

### Theme Customization

The PaperMod theme offers extensive customization options. Check the [PaperMod documentation](https://github.com/adityatelange/hugo-PaperMod) for details.

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions. The deployment workflow:

1. Builds the Hugo site
2. Deploys to the `gh-pages` branch
3. Serves the site via GitHub Pages

## 📝 Writing Posts

Posts are written in Markdown with front matter. Here's a template:

```markdown
---
title: "Your Post Title"
date: 2025-01-27T10:00:00+00:00
draft: false
tags: ['tag1', 'tag2']
categories: ['Category']
description: "Brief description of your post"
author: "Your Name"
---

Your post content goes here...
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

Janith Malinga - [@yourusername](https://twitter.com/yourusername)

Project Link: [https://github.com/janithmalinga/physics-blog](https://github.com/janithmalinga/physics-blog)

---

⭐ Star this repository if you found it helpful!
