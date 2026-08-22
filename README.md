# DVC Point Call

The DVC Point Call app, ready to host on GitHub Pages with a Porkbun domain.

## Files
- index.html          the app (this opens at your domain)
- dvc-import.json      optional starter data you can Restore inside the app

## Put it online (no terminal)
1. On GitHub, create a new public repository.
2. Add file -> Upload files. Drag in index.html and dvc-import.json. Commit.
3. Settings -> Pages -> Source: Deploy from a branch, branch main, folder /(root). Save.
4. Your app goes live at https://<username>.github.io/<repo>/

## Point your Porkbun domain at it
1. Settings -> Pages -> Custom domain: type your domain, save. GitHub shows the DNS records.
2. Porkbun -> your domain -> DNS: add the four A records GitHub lists, plus a CNAME for www -> <username>.github.io
3. Back on GitHub, tick Enforce HTTPS once available. Give DNS a few minutes.
