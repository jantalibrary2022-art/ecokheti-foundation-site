# EcoKheti Foundation website

Static site served at https://ecokhetifoundation.org.in from `public_html/ecokheti/` on the urban-kheti.com cPanel account (alias domain, routed by `.htaccess`).

- `site/` is the website. Edit here.
- `.cpanel.yml` copies `site/` into `public_html/ecokheti/` when you click **Deploy HEAD Commit** in cPanel → Git Version Control.
- `htaccess-lines.txt` holds the routing lines for `public_html/.htaccess` (above `# BEGIN WordPress`). They are not deployed automatically.
- Photos go in `site/images/` with the names in `site/images/PHOTO-NAMES.txt`.
