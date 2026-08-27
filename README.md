# torrecaparatta.com

Personal CV / portfolio website for Torre Caparatta, Ph.D.

## Deploy with GitHub Pages

1. Create a GitHub repository named `torrecaparatta.github.io` (replace `torrecaparatta` with your GitHub username).
2. Upload `index.html`, the `assets` folder, and `Torre_Caparatta_CV.pdf` if you have it.
3. In **Settings → Pages**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. In **Custom domain**, enter `torrecaparatta.com`.
5. In Cloudflare DNS, use GitHub Pages' four A records for the apex domain and a CNAME for `www` pointing to `YOURUSERNAME.github.io`.
6. Set the Cloudflare DNS records to **DNS only** while configuring GitHub Pages.
7. After GitHub verifies the domain, enable **Enforce HTTPS**.

## Before publishing

Search for these placeholders in `index.html` and replace them:

- `YOUR_EMAIL@example.com`
- `https://www.linkedin.com/`
- `https://github.com/`
- `Torre_Caparatta_CV.pdf`

The site is intentionally static, so it can be hosted for free with GitHub Pages.
