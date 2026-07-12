# Millat Boutique & Garments — Website

Ladies formal & casual wear · Pakistan's famous clothing brands · Karachi, delivery all over Pakistan.

A single-file, self-contained lead-generation website (bilingual English/Urdu) with WhatsApp
inquiry capture. All brand logos are embedded — no external files or folders needed.

---

## How to publish (GitHub + Railway)

### Step 1 — Put the code on GitHub
1. Go to https://github.com and sign in (create a free account if needed).
2. Click the **+** (top-right) → **New repository**.
3. Name it `millat-boutique-website`, keep it **Public** (or Private — Railway works with both), click **Create repository**.
4. On the new repo page click **uploading an existing file**.
5. Drag in these 3 files: `index.html`, `package.json`, `.gitignore`.
6. Click **Commit changes**. Done — your code is stored on GitHub.

### Step 2 — Deploy on Railway
1. Go to https://railway.app and click **Login** → **Login with GitHub** (this links the two).
2. Click **New Project** → **Deploy from GitHub repo** → choose `millat-boutique-website`.
3. Railway auto-detects Node.js, installs the tiny `serve` package, and starts the site.
4. When the deploy turns green, open the service → **Settings** → **Networking** →
   **Generate Domain**. Railway gives you a public URL like
   `millat-boutique-website-production.up.railway.app`.
5. Open that URL — your website is live. Share it on Facebook and WhatsApp.

### Updating the site later
Whenever I give you a new `millat-boutique.html`:
1. Rename it to `index.html`.
2. On GitHub, open the repo → click `index.html` → pencil icon (or upload again replacing it).
3. Commit — Railway automatically redeploys within a minute or two.

### Custom domain (optional)
In Railway → Settings → Networking → **Custom Domain**, you can attach a domain like
`millatboutique.com` (purchased from any registrar) by adding the CNAME record Railway shows you.

### Notes
- Railway's Hobby plan has a small monthly cost after trial credits. If you ever want a 100% free
  option for this static site, **GitHub Pages** also works: repo → Settings → Pages →
  Deploy from branch `main` → root. Same repo, no Railway needed.
- The site is one file; `package.json` simply runs a static file server so Railway can host it.
