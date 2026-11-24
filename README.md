# Website SEO Toolkit

A static browser-based set of on-page SEO utilities. Plain HTML, CSS and JavaScript; no account or application backend.

## Features
- Audit pasted/uploaded HTML: title and description, canonical, H1, language, viewport, image alt attributes, heading order, Open Graph tags, visible text, links and robots directive. Export JSON.
- Search snippet preview with character counters.
- Generate title, description, canonical, robots, Open Graph and Twitter card tags.
- Basic robots.txt directive and XML sitemap syntax checks.
- JSON-LD JSON syntax and basic top-level structure check.

## Privacy and limitations
Analysis runs locally; pasted HTML is not uploaded. The static app does not crawl arbitrary URLs. Browser CORS restrictions prevent reliable cross-origin page fetching. To audit, view page source and paste it, or upload a saved HTML file (5 MB max). The audit checklist is heuristic, not a Google ranking score. Robots and sitemap checks inspect pasted text only, not server delivery, crawler behavior, URL reachability or sitemap submission. JSON-LD checks do not establish Schema.org validity or Google rich-result eligibility.

## Run
Open index.html in a modern browser or serve this directory with any static HTTP server. No build step required. GitHub Pages compatible. Manual browser testing is recommended.