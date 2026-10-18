# Deyi Zhu — Personal Homepage

Private source repository for Deyi Zhu's academic personal homepage.

## Structure

- `dist/index.html` — page content and semantic structure
- `dist/stylesheet.css` — responsive academic-site styling
- `dist/site.js` — lightweight progressive reveal and footer year
- `dist/imgs/` — profile, university, and publication imagery

The visitor map uses a dedicated SmallCounter ID for this homepage. Loading the
map sends the visitor's IP address to SmallCounter so the service can count the
visit and infer an approximate geographic location. The map begins collecting
real traffic when the public site is launched; it does not reuse another
website's analytics data.

## Local preview

Serve the `dist` directory with any static web server, for example:

```bash
python -m http.server 8000 --directory dist
```
