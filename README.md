# ruksana.farooks.com

GitHub Pages site for **ruksana.farooks.com** — part of the [farooks.com](https://farooks.com) family.

## Repo Structure

```
ruksana/
├── index.html   # Single-page site (inline CSS, rose/pink theme)
├── CNAME        # Custom domain: ruksana.farooks.com
├── .gitignore
└── README.md
```

## Enable GitHub Pages

1. Go to **Settings → Pages** in this repo.
2. Under **Source**, select branch `main` and folder `/ (root)`, then click **Save**.
3. Under **Custom domain**, enter `ruksana.farooks.com` and click **Save**.
4. Check **Enforce HTTPS** once the DNS certificate provisions (may take a few minutes).

## Namecheap DNS — Add CNAME Record

In your Namecheap dashboard for **farooks.com**, go to **Advanced DNS** and add:

| Type  | Host    | Value                   | TTL       |
|-------|---------|-------------------------|-----------|
| CNAME | ruksana | meshameer.github.io.    | Automatic |

> **Note:** GitHub Pages requires the CNAME to point to `<username>.github.io` (not the repo URL).
> DNS propagation can take a few minutes to 48 hours.
