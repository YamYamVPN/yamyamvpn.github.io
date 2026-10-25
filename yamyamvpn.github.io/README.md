# yamyamvpn.github.io

Landing page for **[YamYam VPN](https://yamyamvpn.top/)**, a free Android VPN with no signup,
served by GitHub Pages at <https://yamyamvpn.github.io/>.

<a href="https://play.google.com/store/apps/details?id=com.yamyam.vpn"><img alt="Get it on Google Play" src="assets/google-play-en.png" width="220"></a>

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole page: the YamYam mark, an animated braid (two strands leave the two Y stems, twist and merge) and the Google Play badge, all one link; Persian meta, inline CSS, JSON-LD (Organization, WebSite, MobileApplication) |
| `assets/og.png` | 1200 × 630 social preview (a still of the page) |
| `assets/google-play-en.*` | Official Google Play badge (English), trimmed |
| `manifest.webmanifest` | Icons and `related_applications` pointing at the Play listing |
| `robots.txt`, `sitemap.xml` | Crawling |

Product claims follow YamYam's facts file; never add numbers of servers, speeds, "unlimited" or "no logs".
Play links carry an install referrer (`utm_source=github_pages`) so Play Console can attribute installs.

Lighthouse (mobile, 2026-10-25): performance 100, accessibility 100, best practices 100, SEO 100.

Google Play and the Google Play logo are trademarks of Google LLC.
