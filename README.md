# AtmousMind Portfolio

The AtmousMind portfolio site. It's a single-file static HTML page built with React 18 and Babel Standalone loaded from CDN — there is no build step, no bundler, and no package manager. Open `index.html` directly in a browser and it runs.

## Structure

- `index.html` — the entire site (markup, styles, and React components in `<script type="text/babel">` blocks)
- `assets/` — images referenced by the site

## Deploy to Vercel

1. Push this repo to GitHub.
2. On Vercel, click **Import Project** and select the GitHub repo.
3. Set **Framework Preset** to **Other**.
4. Leave **Build Command** empty.
5. Leave **Output Directory** empty.
6. Click **Deploy**.

Vercel will serve `index.html` and the `assets/` folder as static files.
