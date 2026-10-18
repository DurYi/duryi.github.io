# Deyi Zhu — Personal Homepage

Private source repository for Deyi Zhu's academic personal homepage.

## Structure

- `dist/index.html` — page content and semantic structure
- `dist/stylesheet.css` — responsive academic-site styling
- `dist/site.js` — lightweight progressive reveal and footer year
- `dist/imgs/` — profile, university, and publication imagery

The visitor map uses a dedicated MapMyVisitors ID for this homepage. Loading the
map sends visitor and page-request information to MapMyVisitors so the service
can count visits and infer approximate geographic locations. The map collects
real traffic after the public site is launched; it does not reuse another
website's analytics data.

## Local preview

Serve the `dist` directory with any static web server, for example:

```bash
python -m http.server 8000 --directory dist
```
