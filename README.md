# EcoKheti Foundation website

Static site served at https://ecokhetifoundation.org.in from `public_html/ecokheti/` on the urban-kheti.com cPanel account (alias domain, routed by `.htaccess`).

- `site/` is the website. Edit here.
- Every push to `main` that changes `site/` is uploaded to `public_html/ecokheti/` by GitHub Actions (`.github/workflows/deploy.yml`, FTPS, secrets FTP_SERVER, FTP_USERNAME, FTP_PASSWORD). `.cpanel.yml` remains as a manual fallback through cPanel → Git Version Control.
- `htaccess-lines.txt` holds the routing lines for `public_html/.htaccess` (above `# BEGIN WordPress`). They are not deployed automatically.
- Photos go in `site/images/` with the names in `site/images/PHOTO-NAMES.txt`.
