# Shivam Raj — Portfolio Site

A bold, dark-themed graphic design portfolio. Ready to deploy on Vercel.

## 📁 Structure

```
portfolio_site/
├── vercel.json
└── public/
    ├── index.html
    └── assets/
        ├── comics/
        │   ├── comics_page1.jpg
        │   ├── comics_page2.jpg
        │   └── ... (36 images)
        └── navratri/
            ├── Navratri_2025_page1.jpg
            └── ... (12 images)
```

## 🚀 Deploy on Vercel

### Option 1 — Vercel CLI (fastest)
```bash
npm i -g vercel
cd portfolio_site
vercel
```
Follow the prompts. Your site will be live at a `.vercel.app` URL.

### Option 2 — Vercel Dashboard (no CLI)
1. Zip the entire `portfolio_site` folder
2. Go to [vercel.com](https://vercel.com) → New Project
3. Drag & drop the zip file
4. Click Deploy — done!

### Option 3 — GitHub + Vercel (recommended for updates)
1. Push `portfolio_site/` to a GitHub repo
2. Connect the repo on [vercel.com](https://vercel.com)
3. Every `git push` auto-deploys

## ➕ Adding More Work

To add more designs:
- Put your images in `public/assets/your_project_name/`
- Update the `PROJECTS` object in `index.html`:
```js
your_project: {
  count: 8,          // number of images
  path: 'assets/your_project_name/filename_prefix_page',
  ext: '.jpg'
}
```
- Add a new `.project-card` block in the HTML

## 📬 Contact Info (already set)
- Instagram: @shiiivamraj
- LinkedIn: linkedin.com/in/shivamraj97
- Email: sraj77196@gmail.com
- Phone: +91 77599 93409
