# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for developers, creators, and businesses.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR-BADGE/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Customization](#customization)
  - [Adding Directory Items](#adding-directory-items)
  - [Modifying Categories](#modifying-categories)
  - [Updating Hero Section](#updating-hero-section)
  - [Styling Changes](#styling-changes)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Support](#support)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing various AI tools and resources in a clean, three-column grid layout. Built with HTML, CSS, and JavaScript, it offers easy customization and quick deployment options.

## Features

- 🎯 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 💨 Fast loading times
- 📱 Mobile-friendly design
- 🎨 Customizable styling
- 🔗 SEO-friendly structure

## Getting Started

### Prerequisites

- Git
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS
- Node.js (optional, for development)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Open index.html in your browser
```

## Directory Structure

```
ai-tools-directory/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── responsive.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── data/
│   └── directory-items.json
└── README.md
```

## Customization

### Adding Directory Items

Add new items by editing `data/directory-items.json`:

```json
{
  "id": "tool-name",
  "title": "Tool Name",
  "description": "Tool description goes here",
  "category": "category-name",
  "url": "https://toolurl.com",
  "image": "tool-image.jpg"
}
```

### Modifying Categories

Edit categories in the `index.html` file:

```html
<div class="categories">
  <button class="category-btn active" data-category="all">All</button>
  <button class="category-btn" data-category="chatbots">Chatbots</button>
  <button class="category-btn" data-category="image-gen">Image Generation</button>
  <!-- Add more categories as needed -->
</div>
```

### Updating Hero Section

Modify the hero section in `index.html`:

```html
<section class="hero">
  <h1>Your New Title</h1>
  <p>Your new description text</p>
</section>
```

### Styling Changes

Customize colors in `assets/css/style.css`:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
  --background-color: #your-color;
}
```

## Deployment

1. Push your changes to GitHub
2. Deploy to Netlify:
   - Connect your GitHub repository
   - Set build settings (if needed)
   - Click "Deploy"

## Custom Domain Setup

1. Purchase domain from your preferred registrar
2. Add domain in Netlify:
   - Go to Site settings > Domain management
   - Click "Add custom domain"
   - Follow DNS configuration instructions

## Troubleshooting

Common issues and solutions:

- **Images not loading**: Ensure correct path in `directory-items.json`
- **Categories not filtering**: Check category names match in HTML and JSON
- **Styling issues**: Clear browser cache or check CSS specificity
- **Search not working**: Verify JavaScript console for errors

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## Support

- 📧 Email: support@aitools.com
- 💬 Discord: [Join our community](https://discord.gg/aitools)
- 📚 Documentation: [Full documentation](https://docs.aitools.com)
- 🐛 Issues: [GitHub Issues](https://github.com/yourusername/ai-tools-directory/issues)

---

Made with ❤️ by [Your Name]