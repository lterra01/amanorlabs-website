# Amanor Labs Website

Static institutional website for Amanor Labs and Amanor TrustOps One.

## Local preview

```powershell
python -m http.server 8088
```

Open `http://localhost:8088`.

## GitHub Pages

This repository is ready for GitHub Pages with the custom domain:

```text
amanorlabs.com
```

In GitHub, enable Pages using **GitHub Actions** as the source. The workflow in `.github/workflows/pages.yml` publishes the repository root as a static site.

## DNS target

For an apex domain on GitHub Pages, configure these A records:

```text
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

For `www`, configure a CNAME pointing to the GitHub Pages host, usually:

```text
<github-owner>.github.io
```

