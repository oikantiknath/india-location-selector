# 🇮🇳 India Location Selector Widget

A cascading dropdown widget for selecting **State → District → City/Town/Village** across all of India. Designed to be embedded in Notion (or any webpage) via an iframe.

## What's included

| File | Description |
|------|-------------|
| `india_data_fixed.json` | Full location data — 35 states/UTs, 774 districts, 6.7 lakh+ places |
| `index.html` | The widget — loads data from this repo and renders the dropdowns |

## Setup (one-time)

### Step 1 — Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under *Source*, select **Deploy from a branch**
4. Select branch: `main`, folder: `/ (root)` → click **Save**
5. Wait ~60 seconds, then your widget is live at:
   ```
   https://<your-username>.github.io/<your-repo-name>/
   ```

### Step 2 — Embed in Notion

1. Copy your GitHub Pages URL above
2. In Notion, type `/embed`
3. Paste the URL → click **Embed link**
4. Resize the embed block to your liking (recommended height: 500px+)

That's it! 🎉

## Data coverage

- **35** States & Union Territories
- **774** Districts
- **6,74,844** Cities, Towns & Villages

## Updating the data

To update place data, replace `india_data_fixed.json` with a new version. The widget fetches it fresh each time — no other changes needed.

---

*Widget built with vanilla HTML/CSS/JS. No dependencies, no build step.*
