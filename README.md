# ondawater.org

Personal website of Kyle Onda. Plain HTML/CSS — no build step, no dependencies.

## Structure

- `index.html` — home (bio, experience, education, service)
- `publications.html` — peer-reviewed publications
- `software.html` — open-source and data infrastructure projects
- `styles.css` — all styling (light/dark via `prefers-color-scheme`)
- `CNAME` — custom domain for GitHub Pages
- `404.html` — not-found page

## Hosting

GitHub Pages, from the `main` branch root of `ksonda/ondawater.org`. Custom domain: `ondawater.org`.

## DNS (at the domain registrar)

| Type  | Host | Value               | Purpose            |
|-------|------|---------------------|--------------------|
| A     | @    | 185.199.108.153     | GitHub Pages       |
| A     | @    | 185.199.109.153     | GitHub Pages       |
| A     | @    | 185.199.110.153     | GitHub Pages       |
| A     | @    | 185.199.111.153     | GitHub Pages       |
| CNAME | www  | ksonda.github.io    | www redirect       |

**Do not modify MX or TXT records** — email for kyle.onda@ondawater.org depends on them.

## Editing

Edit the HTML directly and push — Pages redeploys automatically. To add a publication, copy a `<p class="pub">` block in `publications.html` under the right year.
