# Notebook Maker website

Four static pages for the Canva app listing. Deploy the folder as-is to any static host
(Vercel, Cloudflare Pages, Netlify, GitHub Pages). Then paste these into
Canva Developer Portal → App listing → Links:

- Company or Website URL → /index.html (or the site root)
- Support URL → /support.html
- Privacy policy URL → /privacy.html
- Terms and conditions URL → /terms.html

Quickest: Vercel → Add New → Project → drag this folder in, or `npx vercel --prod` from inside it.
