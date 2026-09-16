# Abdul Gafoor Suleman Usman Mithaiwala — Website

Official brand website for Abdul Gafoor Suleman Usman Mithaiwala, a heritage mithai, halwa and Bombay bakery brand headquartered in Mumbai, operating across India and the Gulf since 1926.

Static single-page site — plain HTML, CSS and vanilla JS, no build step or dependencies.

## Structure

```
index.html          All markup, styles and scripts for the site
images/              Logos, favicon and gallery photography
```

## Running locally

Any static file server works. For example, with Python:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Deploying with GitHub Pages

1. Push this repository to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose the `main` branch and `/ (root)` folder, then save.
5. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/`.

No build step is required — the site is served as-is.

## Editing content

- All page copy, structure and styling lives in [`index.html`](index.html).
- Menu items are grouped into tabs inside the `#menu` section.
- Photo gallery images live in the `#gallery` section and in `images/`.
- Franchise enquiry form submissions open the visitor's email client or WhatsApp — there is no backend. To collect enquiries automatically, connect the form to a form backend service once the site is hosted on a domain.
