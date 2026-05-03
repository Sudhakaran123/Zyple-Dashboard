# ⚡ Zyple Insights — AI Excel Dashboard Generator

> Upload any Excel or CSV file → Get instant professional dashboards with real charts, KPIs, and AI business insights. Download as PDF, PNG, Excel, or CSV.

🌐 **Live Demo:** [https://YOUR-USERNAME.github.io/zyple-insights](https://YOUR-USERNAME.github.io/zyple-insights)

---

## ✨ Features

- 📊 **Upload Excel / CSV** — Drag & drop or browse (.xlsx, .xls, .csv)
- 🤖 **AI Column Detection** — Auto-detects numeric, date, and categorical columns
- 📈 **7 Dashboard Types** — Executive Summary, Trend Analysis, Category Breakdown, Top 10, Distribution, Multi-Metric Comparison, Data Table
- 💡 **Business Insights** — Auto-generated KPIs, totals, averages, top performers
- 📥 **4 Download Formats:**
  - 🖼 PNG — High-resolution dashboard image
  - 📄 PDF — Single or multi-page report
  - 📗 Excel (.xlsx) — Multi-sheet workbook with raw data + KPIs + aggregations
  - 📊 CSV — Clean aggregated data export
- 🔒 **100% Private** — All processing happens in your browser. No data is uploaded anywhere.
- 🚀 **No Backend Required** — Pure HTML/CSS/JavaScript. One file.

---

## 🗂️ Project Structure

```
zyple-insights/
├── index.html      ← Main app (entire application in one file)
└── README.md       ← This file
```

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **"New repository"** (green button)
3. Name it: `zyple-insights`
4. Set visibility to **Public**
5. Click **"Create repository"**

### Step 2 — Upload Files
1. Click **"uploading an existing file"** on the repo page
2. Drag and drop both `index.html` and `README.md`
3. Click **"Commit changes"**

### Step 3 — Enable GitHub Pages
1. Go to your repository → **Settings** tab
2. Scroll down to **"Pages"** (left sidebar)
3. Under **Source**, select **"Deploy from a branch"**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**

### Step 4 — Your site is live! 🎉
After 1–2 minutes, your site will be live at:
```
https://YOUR-GITHUB-USERNAME.github.io/zyple-insights
```

---

## 🧰 Technologies Used

| Library | Purpose | Version |
|---------|---------|---------|
| [SheetJS (xlsx)](https://sheetjs.com) | Excel/CSV parsing & export | 0.18.5 |
| [Chart.js](https://chartjs.org) | Interactive charts | 4.4.0 |
| [html2canvas](https://html2canvas.hertzen.com) | PNG/PDF screenshot | 1.4.1 |
| [jsPDF](https://github.com/parallax/jsPDF) | PDF generation | 2.5.1 |

All libraries loaded from CDN — no npm, no build tools needed.

---

## 📋 Supported File Formats

| Format | Description |
|--------|-------------|
| `.xlsx` | Microsoft Excel (modern) |
| `.xls` | Microsoft Excel (legacy) |
| `.csv` | Comma-separated values |

---

## 🖥️ Browser Support

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |

---

## 📜 License

MIT License — Free to use, modify, and distribute.

---

## 👤 Built With

**Zyple Insights** — Turning raw data into smart dashboards instantly.

> ⭐ If you found this useful, please star the repository!
