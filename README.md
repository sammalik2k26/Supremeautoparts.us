# Supreme Auto Parts (supremeautoparts.us)

Static copy of the Supreme Auto Parts website, migrated from supreme-autoparts.com.

## Deploy to Vercel via GitHub

### 1. Create GitHub repo and push

```bash
# Create a new repo at github.com/new (e.g. "supreme-autoparts-us")
# Then run:

cd "/Users/Shared/Supreme Auto Parts"
git remote add origin https://github.com/YOUR_USERNAME/supreme-autoparts-us.git
git branch -M main
git push -u origin main
```

### 2. Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) → **Add New** → **Project**
2. **Import** your GitHub repository
3. Vercel auto-detects static files — leave settings as default
4. Click **Deploy**
5. Add custom domain: **Settings** → **Domains** → Add `supremeautoparts.us` and `www.supremeautoparts.us`
6. Update DNS at GoDaddy to point to Vercel

## Serve locally

```bash
npx serve .
# or: python3 -m http.server 8000
```
