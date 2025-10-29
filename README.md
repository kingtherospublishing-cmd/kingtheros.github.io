# Publish on GitHub Pages — User: Kingtheros

Follow these steps to publish **for FREE** at **https://kingtheros.github.io/**

## 1) Create the repository
1. Go to https://github.com and sign in (or create a free account).
2. Click **New** repository.
3. Name the repository **kingtheros.github.io** (must match your username exactly).
4. Set visibility to **Public**. Click **Create repository**.

## 2) Upload the website files
1. On the new repo page, click **Add file → Upload files**.
2. Upload **all files** from this folder (keep the same structure):
   - `index.html`
   - `styles.css`
   - `script.js`
   - `.nojekyll`
   - `assets/logo.png`
3. Click **Commit changes**.

## 3) Turn on GitHub Pages (usually automatic for user sites)
- For a user site named `kingtheros.github.io`, Pages is automatic once files are in the **root**.
- Wait ~1–2 minutes and visit: **https://kingtheros.github.io/**

## 4) Contact form (Formspree)
- Create a free account at https://formspree.io/
- Create a new form and copy the endpoint (looks like `https://formspree.io/f/xxxxxx`).
- In `index.html`, replace `https://formspree.io/f/your-id` with your endpoint, then commit the change on GitHub.

## Optional: Custom domain (later)
1. Buy a domain (e.g., `kingtheros.com`) from any registrar.
2. In the repo: **Settings → Pages → Custom domain**, enter your domain.
3. At your registrar, add a CNAME record pointing to **kingtheros.github.io**.

You're live! 🎉
