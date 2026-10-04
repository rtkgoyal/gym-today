GYM TODAY - install as a home-screen app

The page needs to be served over HTTPS for the offline cache and the
home-screen install to work. Opening index.html straight from Files
will show the app, but it will not install or work offline.

Fastest route (GitHub Pages, free):
1. github.com > New repository (public), name it gym-today.
2. "uploading an existing file" > drag in every file from this folder > Commit.
3. Settings > Pages > Source: Deploy from a branch > Branch: main, folder: / (root) > Save.
4. Wait about a minute. Open https://<your-username>.github.io/gym-today/ in Safari.
5. Share > Add to Home Screen.

Netlify, Vercel or Cloudflare Pages work the same way: upload this
folder as a static site, open the URL in Safari, Add to Home Screen.

Notes
- Ticks are saved on the phone (local storage). This copy does not sync
  with the Claude version of the app.
- Plan dates: Week 0 from Mon 5 Oct 2026, Month 1 from Mon 12 Oct 2026,
  then the 4-week cycle repeats. Day 5 (Sat or Fri) is in Settings.
- To update the app later, replace index.html and sw.js with new copies.
