# Deploying this site

1. Copy these files (`index.html`, `style.css`, `script.js`, `assets/`) into the root of your
   `<your-github-username>.github.io` repo.
2. Commit and push to the `main` branch.
3. In the repo: Settings → Pages → set custom domain to `oskarzielinski.dev` (you've already got
   the DNS records pointed at GitHub via Porkbun).
4. Wait for the green checkmark, then tick "Enforce HTTPS."

To update your CV later, just replace `assets/oskar-zielinski-cv.pdf` with a new export using the
same filename — the download button won't need any changes.
