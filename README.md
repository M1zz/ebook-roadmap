# Anonymous Ebook Brand · Roadmap

Private execution roadmap for the anonymous English ebook brand project.

## Pages

- **`index.html`** — Visual 6-month timeline (Gantt-style)
- **`todo.html`** — Interactive checklist with progress tracking (localStorage)

## Deploy to GitHub Pages

### 1. Create a **private** repository

```bash
# Option A: GitHub CLI
gh repo create ebook-roadmap --private --source=. --push

# Option B: Manual
# Go to github.com → New repository → Private → upload files
```

### 2. Enable GitHub Pages

```
Repository → Settings → Pages
Source: Deploy from a branch
Branch: main / (root)
→ Save
```

### 3. Access your site

```
https://[your-username].github.io/ebook-roadmap/
```

> ⚠️ GitHub Pages on **private repos** requires GitHub Pro ($4/mo).
> Free alternative: use [Netlify Drop](https://app.netlify.com/drop) — drag & drop the folder, instant URL.

## Local preview

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Then open `http://localhost:8000`

## Structure

```
ebook-roadmap/
├── index.html   ← Timeline view
├── todo.html    ← Todo checklist (progress saved in browser localStorage)
└── README.md
```
