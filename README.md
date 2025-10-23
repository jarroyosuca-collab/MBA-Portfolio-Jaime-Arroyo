# UCW MBA — One‑Page Portfolio (Quarto)

This repository hosts **Jaime Arroyo’s** one‑page MBA portfolio built with **[Quarto](https://quarto.org/)** and Markdown.

> **Live site:** https://<your-username>.github.io/<your-repo>/  
> *(Update this after enabling GitHub Pages in Settings → Pages → `main` + `/docs`.)*

---

## 🧭 Overview
- Single‑page site with sections: **About**, **Education**, **Professional Experience**, **Selected MBA Projects**, **Key Skills**, **Contact**.
- Built in **Quarto** with the **cosmo** Bootswatch theme.
- Output is generated to the **`docs/`** folder for GitHub Pages.

---

## 📁 Project Structure
```
.
├─ index.qmd          # Main Quarto page (rename from jaime-portfolio.qmd if needed)
├─ _quarto.yml        # Quarto project config (output-dir: docs)
├─ docs/              # Rendered site (index.html lives here)
└─ appendix-LLM-*.md  # Appendix files for submission (optional to publish)
```

---

## 🔧 Requirements
- **Quarto CLI** → https://quarto.org/download/
- (Optional) **Git** or **GitHub Desktop** for publishing

Verify:
```bash
quarto --version
```

---

## ▶️ Build Locally
From the repository root:
```bash
quarto render
```
This creates `docs/index.html`. Open it locally or serve via GitHub Pages.

---

## 🌐 Publish to GitHub Pages
1. Commit & push your files to GitHub (including `_quarto.yml` and `docs/`).  
2. In the repository: **Settings → Pages**  
   - **Source:** *Deploy from a branch*  
   - **Branch:** `main`  •  **Folder:** `/docs`  
3. Your site appears at `https://<your-username>.github.io/<your-repo>/`.

To update the website later:
```bash
quarto render
git add .
git commit -m "Update site content"
git push
```

---

## 📎 Appendix (for course submission)
The appendix with the **LLM-generated draft** and **commentary** is in `appendix-LLM-*.md`.  
You may render it to HTML for submission:
```bash
quarto render appendix-LLM-final.md -o appendix-LLM-final.html
```

---

## 🤖 LLM Disclosure
Parts of this project (initial outline and draft text) were generated with **ChatGPT** and then **reviewed and edited by Jaime Arroyo** for accuracy, tone, and authenticity. See the appendix for details of what was used and revised.

---

## 📬 Contact
- **LinkedIn:** https://www.linkedin.com/in/jaime-arturo-arroyo-su-200089a7  
- **Email:** jaimearturo.arroyosu@myucwest.ca
