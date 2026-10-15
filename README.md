# StudySpark SEO Assignment Website

A lightweight, static, multi-page website prepared for an SEO assignment.

## Pages
- `/` — homepage
- `/articles/ai-note-taking.html`
- `/articles/ai-research.html`
- `/articles/student-productivity.html`

## Run locally
This is a static website. You can open `index.html` directly, or run a local server from this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to Vercel
1. Create a GitHub repository and upload all files in this folder.
2. In Vercel, choose **Add New → Project**, import that repository, and deploy.
3. Framework preset: **Other**. Build command: leave blank. Output directory: `.` (root).
4. Once Vercel gives you a domain such as `your-project.vercel.app`, replace every occurrence of `YOUR-VERCEL-DOMAIN` in the HTML canonical tags, `robots.txt`, and `sitemap.xml` with the domain only (do not include `https://` in the placeholder replacement).
5. Commit and push the edits; Vercel redeploys automatically.

## Keyword table
See `KEYWORD-RESEARCH.md`. Match its columns to the exact format in your Session 1 notes PDF if needed.

## Important
The website content is educational sample content. The site has been built and is runnable, but it is not publicly hosted until you deploy it to a Vercel account. No live URL can be honestly supplied before that deployment exists.
