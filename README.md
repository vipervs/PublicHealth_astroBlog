# 🩺 Public Health Analytics Dashboard

Modern public health monitoring platform with evidence-based visualizations powered by Astro & Markdown.

## ✨ Features

- 📈 5 Interactive data dashboards
- 📚 MDX-powered article system
- 🔄 Article navigation controls
- 📱 Mobile-optimized layout
- 🎨 Clean white/blue theme
- ♿ WCAG-compliant interface

## ⚙️ Installation

1. **Prerequisites**
   - Node.js ≥18.x
   - npm ≥9.x

2. **Setup**
   ```bash
   npm install
   ```

## 🚦 Usage

```bash
npm run dev
```
- Dashboard runs on `localhost:4321`
- Click navigation arrows between articles
- Automatic browser launch on dev start

## 🎨 Customization

- Add articles: `src/pages/blog/*.md`
- Modify metrics: Update markdown tables
- Adjust theme colors: `src/layouts/Layout.astro`
- Edit navigation: `src/components/ArticleNavigation.astro`

📌 **Pro Tip:** Use ASCII tables in markdown for clean data presentation!

## 🛠️ Tech Stack

- Astro 4.15
- Markdown/MDX
- CSS Modules
- Responsive Grid
- GitHub Flavored Markdown

## 📄 License

MIT
