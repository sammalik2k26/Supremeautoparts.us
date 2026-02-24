# Supreme Auto Parts (supremeautoparts.us)

This is a static copy of the Supreme Auto Parts website, migrated from supreme-autoparts.com and configured for the supremeautoparts.us domain.

## Contents

- **supremeautoparts.us/** – Full static website including:
  - Homepage, categories, product pages
  - About, Contact, Brands, Cart
  - Terms, Privacy Policy, Return Policy, Track Order
  - All images, CSS, and JavaScript assets

## Deploy to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **Add New** → **Project**
3. Import from Git or upload the `supremeautoparts.us` folder as a static site
4. Set the **Output Directory** to `supremeautoparts.us` (or use the folder as the root)
5. Add your custom domain `supremeautoparts.us` in Project Settings → Domains
6. Update DNS at GoDaddy to point to Vercel (see earlier setup instructions)

## Serve Locally

```bash
cd supremeautoparts.us
npx serve .
# or: python3 -m http.server 8000
```

Then open http://localhost:3000 (or http://localhost:8000)

## Note

This is a static snapshot. The original site (supreme-autoparts.com) is a Next.js app with dynamic features (search, cart, checkout). This copy provides the layout and content; product search and checkout will redirect to the live parts catalog/API.
