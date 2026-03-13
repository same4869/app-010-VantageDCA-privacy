# Privacy HTML Pages

This folder contains the multi-language Privacy Policy pages for GitHub Pages hosting.

## Structure

- `index.html`: language redirect entry
- `en/index.html`: English
- `zh-Hans/index.html`: Simplified Chinese
- `zh-Hant/index.html`: Traditional Chinese

## Local preview

```bash
cd docs/privacy
python3 -m http.server 8080
```

Open: `http://localhost:8080/`

## GitHub Pages deployment

If your repo name is `app-010-VantageDCA` and user/org is `same4869`, expected URL is:

`https://same4869.github.io/app-010-VantageDCA/privacy/`

Recommended path in Pages branch:

- `privacy/index.html`
- `privacy/en/index.html`
- `privacy/zh-Hans/index.html`
- `privacy/zh-Hant/index.html`

When you finish deployment, you can optionally add the live URL to app config through Info.plist key:

- `PRIVACY_POLICY_URL`
