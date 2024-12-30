# Proofly Documentation

[![Documentation Status](https://img.shields.io/badge/docs-latest-brightgreen.svg)](https://docs.proofly.xyz)
[![Built with Nextra](https://img.shields.io/badge/built%20with-nextra-blue.svg)](https://nextra.site)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Updated](https://img.shields.io/badge/last%20updated-December%202024-orange.svg)](https://github.com/moroii69/proofly-docs)

Official documentation for [Proofly](https://github.com/moroii69/proofly) - Enterprise-grade health metrics analysis and prediction engine.

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/moroii69/proofly-docs

# Navigate to the project directory
cd proofly-docs

# Install dependencies
npm install

# Start development server
npm run dev
```

Visit `http://localhost:3000` to see the documentation.

## 🏗️ Built With

- [Next.js](https://nextjs.org/) - The React framework
- [Nextra](https://nextra.site) - Documentation generator
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [MDX](https://mdxjs.com/) - Markdown enhancement

## 📁 Directory Structure

```
docs/
├── pages/              # Documentation pages
│   ├── _meta.json     # Navigation structure
│   ├── index.mdx      # Homepage
│   ├── getting-started.mdx
│   ├── features.mdx
│   ├── installation.mdx
│   ├── usage.mdx
│   ├── api-reference.mdx
│   ├── health-conditions.mdx
│   ├── export.mdx
│   ├── error-handling.mdx
│   └── contributing.mdx
└── theme.config.js   # Nextra configuration
```

## 🛠️ Local Development

1. Fork the repository
2. Create your feature branch:
```bash
git checkout -b feature/amazing-feature
```
3. Make your changes
4. Run locally to test:
```bash
npm run dev
```
5. Commit your changes:
```bash
git commit -m 'Add amazing feature'
```
6. Push to the branch:
```bash
git push origin feature/amazing-feature
```
7. Open a Pull Request

## 📝 Contributing

1. Check our [Proofly Page](https://www.github.com/moroii69/proofly)
2. Look for existing issues or create a new one
3. Fork the repository
4. Create your feature branch
5. Commit your changes
6. Push to the branch
7. Open a Pull Request

## 🔄 Update Process

1. Make changes to the relevant MDX files
2. Test locally using `npm run dev`
3. Create a pull request
4. After review, changes will be deployed automatically

## 📦 Deployment

The documentation is automatically deployed to Vercel when changes are merged to the main branch.

Preview deployments are created for all pull requests.

## 🎨 Customization

### Theme Configuration

Modify `theme.config.js` to customize:
- Logo
- Navigation
- Footer
- Social links
- Color scheme

```js
// theme.config.js example
export default {
  logo: <span>Proofly Docs</span>,
  project: {
    link: 'https://github.com/moroii69/proofly'
  },
  // ... other configurations
}
```

### Adding New Pages

1. Create new `.mdx` file in `pages/`
2. Update `_meta.json` for navigation
3. Add content using MDX
4. Test locally
5. Create pull request

## 📄 License

This documentation is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Support

- Documentation Issues: [GitHub Issues](https://github.com/moroii69/proofly-docs/issues)
- Main Project: [Proofly Repository](https://github.com/moroii69/proofly)
- Email: support@proofly.xyz

## ✨ Acknowledgments

- All documentation contributors
- Nextra team for the amazing documentation framework
- Vercel for hosting
- Our amazing community of users and contributors

---
