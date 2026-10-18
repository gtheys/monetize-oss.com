# monetize-oss.com

Landing page for https://monetize-oss.com — plain static HTML, no build step.
Deployed to GitHub Pages from the `main` branch root.

Stylesheet is hotlinked from https://blog.monetize-oss.com/style.css (single
source of truth). Landing-specific overrides live in a `<style>` block in
`index.html`.

## DNS

Apex domain needs A records pointing at GitHub Pages:

    185.199.108.153
    185.199.109.153
    185.199.110.153
    185.199.111.153

HTTPS certificate is issued automatically once DNS resolves.

## Edit

Edit `index.html`, commit, push — Pages redeploys within a minute.
