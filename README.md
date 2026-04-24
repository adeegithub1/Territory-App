# TerritoryIQ — India Sales Territory Map

An interactive India district-level sales territory management tool. Assign salespersons to districts, track customers & pumps, export to Excel/PNG.

## 🚀 Live Demo
Once deployed, your app will be live at:
```
https://<your-github-username>.github.io/<your-repo-name>/
```

---

## 📁 File Structure
```
├── index.html          # Main app (all UI, logic, styles)
├── INDIA_DISTRICTS.js  # India district GeoJSON data
└── .github/
    └── workflows/
        └── deploy.yml  # Auto-deploy to GitHub Pages on every push
```

---

## ⚡ How to Deploy (One-Time Setup)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) → **New repository**
2. Name it anything, e.g. `territory-map`
3. Set it to **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 2 — Upload these files
Either use GitHub's web UI (drag & drop all files) or use Git:
```bash
git init
git add .
git commit -m "Initial deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **GitHub Actions**
3. Save

### Step 4 — Done! 🎉
GitHub will automatically run the deploy workflow. After ~1 minute, your app will be live at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO/
```

Every time you push changes to `main`, the site updates automatically.

---

## 🛠 Features
- Interactive India district map (all states & UTs)
- Assign districts to salespersons with color coding
- Track customers & pump counts per district
- Search districts & filter by state
- Bulk assignment support
- Import/Export via Excel (.xlsx)
- Download map as PNG
- Undo history & local storage persistence
