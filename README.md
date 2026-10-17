# usasweare.org

The placeholder landing page for **Us As We Are**, until the full website exists. A Rogue Media Initiative project by Keegan Van Hook.

- Static files only: `index.html`, the self-hosted Jost Bold font for the title (SIL Open Font License, `fonts/JOST-LICENSE.txt`), `robots.txt` and Cloudflare Pages `_headers`.
- Served by Cloudflare Pages at `https://usasweare.org`. `www.usasweare.org` redirects to the bare domain.
- Hidden from search engines for now: `noindex` in the page and headers, and `robots.txt` disallows everything. Lift these at the publishing push.
- No analytics, no trackers, no cookies of its own.
- **Owner Controls:** the page loads the platform script `https://news.usasweare.org/static/platform/owner-controls.js`, which asks UAWAggregate who is signed in. Anyone can still view the page without signing in; Owners get the Owner Controls button in the lower right corner (see `../PLATFORM.md`). If news.usasweare.org is down, the page just shows without it.

The news aggregator lives separately at `https://news.usasweare.org`, so this page stays up even if that server is down.
