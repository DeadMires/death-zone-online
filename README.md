# GitHub Pages app-ads.txt

This folder contains the files needed for AdMob app-ads.txt verification.

## Files

- `app-ads.txt`
- `index.html`

## Recommended GitHub Pages setup

1. Create a GitHub repository named `USERNAME.github.io`, where `USERNAME` is your GitHub username or organization name.
2. Upload `app-ads.txt` and `index.html` to the root of that repository.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Wait for GitHub Pages to publish the site.
6. Open `https://USERNAME.github.io/app-ads.txt` and confirm it shows:

```txt
google.com, pub-5858243169773559, DIRECT, f08c47fec0942fa0
```

Use `https://USERNAME.github.io` as the developer website URL in Google Play / App Store, or use a custom domain and make sure the file is available at `https://YOURDOMAIN/app-ads.txt`.
