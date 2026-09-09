# Andrew Hertzberg portfolio

Static HTML and CSS portfolio for GitHub Pages. No build step, account database, analytics, external font service or API keys are required.

## AI assistance

AI tools were used to help design and build this website, write and revise its HTML/CSS, organize content, and check layouts and links. Andrew provided the personal information and directed the wording and design revisions. This disclosure is included in the repository README, not in the displayed website pages.

## Local preview

```sh
python -m http.server 8765
```

Open http://localhost:8765. The site works at the root of `andrewhertzbergpsu2026.github.io`.

## Editing

- `index.html`: introduction, selected projects, education and experience, contact.
- `work.html`: project descriptions, limitations and source links.
- `research.html`: exploratory research methods and interests.
- `life.html`: books, games, shows, and outdoor interests.
- `life.css`: the warmer personal-page styling and shared small-screen refinements.
- `styles.css`: responsive layout, keyboard focus, reduced-motion support and print styles.
- `assets/`: selected saved project renders and the single resume. The same resume is used for SWE and ML applications; it omits the phone number for public sharing.

## GitHub Pages

Publish the `main` branch root of the repository `andrewhertzbergpsu2026.github.io`. This release uses the default GitHub Pages address. The existing andrewhertzberg.dev domain and its current hosting have not been changed.

To move the custom domain later, first back up its existing DNS records. Set the custom domain in GitHub Pages, update the domain's DNS following GitHub's current documentation, verify HTTPS, then update canonical URLs, sitemap and Open Graph URLs. Do not point DNS at an unconfigured or unverified Pages site.

Project images are saved outputs from Andrew's coursework. The personal page's landscape and typographic book cards are CSS illustrations, not borrowed artwork or reproductions of book covers. Read the graphics collection's attribution notes before reuse. Do not add planned projects to completed work until they actually exist.
