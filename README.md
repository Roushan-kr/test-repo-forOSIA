```bash
community-directory/
├── .github/
│   └── workflows/
│       └── render-quarto.yml       <-- GitHub Action
├── communities.csv                 <-- Editable by contributors
├── communities.qmd                 <-- Main Quarto page
├── _quarto.yml                     <-- Quarto config
├── README.md
└── docs/                           <-- Will hold rendered HTML for GitHub Pages
```

# 🌍 Community Directory

This site lists tech communities around the world in a filterable table.

- You can contribute new entries to [`communities.csv`](./communities.csv)
- The site is rendered via [Quarto](https://quarto.org/) and hosted with GitHub Pages.

## ✅ Contributing

Fork the repo → update `communities.csv` → open a pull request.
