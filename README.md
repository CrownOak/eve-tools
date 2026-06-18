# Crown & Oak - EVE Tools (hub)

A small public landing page linking the EVE tools. Served via GitHub Pages.

- **Live: https://crownoak.github.io/eve-tools/**

Links to:
- [Lowsec Scout](https://crownoak.github.io/eve-lowsec-scout/) (hourly; password-protected) -- repo `eve-lowsec-scout`
- [BONK Prospect Finder](https://crownoak.github.io/eve-bonk-prospects/) (daily; password-protected) -- repo `eve-bonk-prospects`

The hub itself is open (no password); the individual tool pages are client-side
encrypted (password held in the `EVE_PAGE_PASSWORD` env var on the build machine,
never committed). Edit `index.html` to add tools.
