# ArcGIS Maps SDK for JavaScript — Developer Guide

An end-to-end tutorial series and API reference for developers new to the ArcGIS Maps SDK for JavaScript. Covers map rendering, layer management, and spatial queries. Published as a GitHub Pages site.

**Live site:** `https://<your-username>.github.io/arcgis-sdk-guide/`

---

## What's inside

```
arcgis-sdk-guide/
├── index.html                  ← Homepage
├── css/
│   └── style.css               ← All styles
├── pages/
│   ├── map-rendering.html      ← Tutorial 01: initialise a map
│   ├── layer-management.html   ← Tutorial 02: FeatureLayer & GraphicsLayer
│   ├── spatial-queries.html    ← Tutorial 03: Query, queryFeatures()
│   ├── api-reference.html      ← Plain-English API reference
│   └── blog.html               ← Companion blog post
└── README.md
```

---

## Deploying to GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com/new](https://github.com/new)
2. Name the repository `arcgis-sdk-guide`
3. Set it to **Public** (required for free GitHub Pages)
4. Do not initialise with a README (you already have one)
5. Click **Create repository**

### Step 2 — Push the project

In your terminal, from inside the project folder:

```bash
git init
git add .
git commit -m "Initial commit: ArcGIS SDK Developer Guide"
git branch -M main
git remote add origin https://github.com/<your-username>/arcgis-sdk-guide.git
git push -u origin main
```

Replace `<your-username>` with your GitHub username.

### Step 3 — Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: `main`, folder: `/ (root)`
5. Click **Save**

Your site will be live at `https://<your-username>.github.io/arcgis-sdk-guide/` within a few minutes.

### Step 4 — Update your resume

Once live, add the URL to the ArcGIS SDK Developer Guide project entry in your resume:

```
GitHub Pages: https://<your-username>.github.io/arcgis-sdk-guide/
GitHub repo:  https://github.com/<your-username>/arcgis-sdk-guide
```

---

## What the tutorials cover

| Tutorial | Level | Time | Key concepts |
|----------|-------|------|-------------|
| Map Rendering | Beginner | ~15 min | `Map`, `MapView`, basemaps, zoom/center/extent |
| Layer Management | Intermediate | ~25 min | `FeatureLayer`, `GraphicsLayer`, `Graphic`, renderers, toggle visibility |
| Spatial Queries | Intermediate | ~30 min | `Query`, `queryFeatures()`, attribute & geometry filters, pagination |

---

## Notes

- All tutorials use the ArcGIS CDN (v4.29) — no build step required
- The earthquake dataset used in tutorials 2 & 3 is a publicly hosted Esri sample service
- This is an independent documentation project, not affiliated with Esri
- Official SDK docs: [developers.arcgis.com/javascript/latest/](https://developers.arcgis.com/javascript/latest/)
