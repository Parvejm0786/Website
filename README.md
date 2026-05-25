# Website

This repository contains the static website for ProcessEdge.

Instructions to publish via GitHub Pages (private repo):

1. Create a new **private** repository on GitHub named `Website`.
2. Add this repo as remote and push the `main` branch.

Commands (run locally from project root):

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin git@github.com:<your-username>/Website.git
git push -u origin main
```

Notes:
- Keep the repository private (GitHub supports private repos with Pages for user/org sites depending on plan). If you need GitHub Pages for a private repo, ensure your account plan supports it; otherwise, use a public repo or deploy to Netlify/Vercel.
- The file `CNAME` (if present) maps the site to processedges.com; do not share the repository publicly if you want files private.
