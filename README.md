# 🌌 Nebula Studios

**Modern Digital Solutions & Web Development**

A cutting-edge web template built with **[Astro 5.0](https://astro.build/)** and **[Tailwind CSS](https://tailwindcss.com/)**. Designed for performance, scalability, and beautiful user experiences.

[![GitHub Stars](https://img.shields.io/github/stars/baalaganeshr/framer-nebula-0.1?style=social)](https://github.com/baalaganeshr/framer-nebula-0.1)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## ✨ Features

- ⚡ **Lightning-fast Performance** - Optimized for speed with Astro's static site generation
- 🎨 **Modern UI Components** - Beautiful, responsive components built with Tailwind CSS
- 🌓 **Dark Mode Support** - Seamless dark/light theme switching
- 📱 **Fully Responsive** - Perfect on all devices and screen sizes
- 🔍 **SEO Optimized** - Built-in best practices for search engine visibility
- 🎯 **Production Ready** - Clean, maintainable code following industry standards
- 📊 **Blog System** - Full-featured blog with MDX support, categories, and tags
- 🖼️ **Image Optimization** - Automatic image optimization for faster loading
- 🚀 **Easy Deployment** - Deploy to GitHub Pages, Vercel, or Netlify with one command
- ✨ **Enhanced Hover Effects** - Smooth animations and transitions throughout the UI

## 🚀 Quick Start

### Prerequisites

- Node.js 18.17.1 or higher
- npm or yarn package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/baalaganeshr/framer-nebula-0.1.git

# Navigate to project directory
cd framer-nebula-0.1

# Install dependencies
npm install

# Start development server
npm run dev
```

Visit `http://localhost:4321` to see your site in action! 🎉

## 📦 Project Structure

```
/
├── public/             # Static assets
│   ├── robots.txt
│   └── _headers
├── src/
│   ├── assets/         # Images, styles, fonts
│   │   ├── images/
│   │   └── styles/
│   ├── components/     # Reusable components
│   │   ├── widgets/
│   │   ├── ui/
│   │   └── common/
│   ├── layouts/        # Page layouts
│   ├── pages/          # Page routes
│   ├── utils/          # Utility functions
│   └── config.yaml     # Site configuration
├── astro.config.ts     # Astro configuration
├── tailwind.config.js  # Tailwind CSS configuration
└── package.json
```

## 🛠️ Commands

| Command | Action |
|---------|--------|
| `npm install` | Install dependencies |
| `npm run dev` | Start dev server at `localhost:4321` |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview build locally before deploying |
| `npm run check` | Check project for errors |

## 🎨 Customization

### Update Site Configuration

Edit `src/config.yaml` to update:
- Site name and URL
- Metadata and SEO settings
- Social media links
- Blog configuration

### Modify Styles

- **Global styles**: `src/assets/styles/tailwind.css`
- **Theme colors**: `tailwind.config.js`
- **Custom styles**: `src/components/CustomStyles.astro`

### Update Content

- **Homepage**: `src/pages/index.astro`
- **Navigation**: `src/navigation.ts`
- **Blog posts**: `src/data/post/`

## 🚀 Deployment

### GitHub Pages (Recommended)

This project is configured for automatic deployment to GitHub Pages:

1. Push your changes to the `main` branch
2. GitHub Actions will automatically build and deploy
3. Your site will be live at: `https://[username].github.io/framer-nebula-0.1/`

### Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Netlify

1. Connect your repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Deploy!

## 🌐 Live Demo

Check out the live site: [https://baalaganeshr.github.io/framer-nebula-0.1/](https://baalaganeshr.github.io/framer-nebula-0.1/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 👨‍💻 Author

**Baalaganesh R**
- GitHub: [@baalaganeshr](https://github.com/baalaganeshr)
- Website: [Nebula Studios](https://baalaganeshr.github.io/framer-nebula-0.1/)

## 🙏 Acknowledgments

Built with:
- [Astro](https://astro.build/) - The web framework for content-driven websites
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- Modern web technologies and best practices

---

<div align="center">
  Made with ❤️ using Astro and Tailwind CSS
</div>
