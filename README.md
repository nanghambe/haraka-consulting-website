# Haraka Consulting Website

This repository contains the static site for Haraka Consulting (Paulus Ndamanomhata). The site is served via GitHub Pages.

Quick Start:
1. Ensure the main HTML file is `index.html` at the repository root.
2. Push to branch `main`.
3. In the GitHub repository settings, enable GitHub Pages: Branch = `main`, Folder = `/` (root).
4. Add DNS records for the custom domain `username.github.io` (see notes below).

Custom domain and DNS:
- Add A records for the apex domain to:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- Add CNAME for `www` -> `nanghambe.github.io` (or the final Pages hostname).
- After DNS propagation, enable "Enforce HTTPS" in the Pages settings.

CI:
A small GitHub Actions workflow (html-lint.yml) is recommended to lint HTML with HTMLHint.

Author: Paulus Ndamanomhata
