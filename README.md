
# Housing Narrative (React + Vite + Tailwind)

## Zero-Terminal Deploy (Vercel + GitHub)
1. Create a new empty GitHub repo.
2. Upload all files from this folder to the repo (via GitHub web UI: Add file → Upload files).
3. Go to https://vercel.com/new → Import Git Repository → pick your repo.
4. Framework: Vite (auto-detected). Build: `vite build`. Output: `dist` (auto-detected).
5. Click **Deploy**. Copy the URL when done.

## Embed in WordPress
Add an HTML block with:
```html
<iframe src="https://YOUR-VERCEL-URL.vercel.app" width="100%" height="900" style="border:none"></iframe>
```
