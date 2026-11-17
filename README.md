# valentinascipione.com

Plain HTML and CSS. No build step, no external fonts or scripts, so the site sets no cookies.

## Files

- `index.html`: home page (valentinascipione.com)
- `relationships/index.html`: polyamory coaching page (valentinascipione.com/relationships)
- `impressum.html`, `datenschutz.html`: legal pages, paste the e-recht24 generator text in
- `styles.css`: shared styles
- `assets/valentina.jpg`: your photo (replace the placeholder, keep the file name, square crop works best)
- `CNAME`: tells GitHub Pages which domain to use

## Before publishing, replace these placeholders

- Nothing left. The legal pages are filled in (check the address and phone note below before going live)

## Publish with GitHub Pages

1. Create a new public repository on GitHub, for example `valentinascipione.com`.
2. Upload all files, keeping the folder structure, and commit to `main`.
3. In the repository: Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. Under "Custom domain", enter `valentinascipione.com` and save.

## Connect the domain in Hostinger

In Hostinger: Domains > valentinascipione.com > DNS / Nameservers > DNS records.

1. Delete any existing **A** records for `@` and any **CNAME** for `www` that point elsewhere (often a Hostinger parking page).
2. Add four **A** records, name `@`, pointing to:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
3. Add one **CNAME** record: name `www`, pointing to `YOUR_GITHUB_USERNAME.github.io`
4. Leave the **MX**, **TXT** (SPF, DKIM) and any mail related records exactly as they are, so your email keeps working.

DNS changes can take from a few minutes to a few hours. When GitHub shows the domain as verified, tick "Enforce HTTPS" in Settings > Pages.

## Legal pages (e-recht24)

Use the free Impressum generator and the free Datenschutz generator on e-recht24.de. For the privacy policy, the relevant facts are:

- Hosting: GitHub Pages (GitHub Inc., USA)
- No cookies, no analytics, no tracking, no embedded content, no contact form
- External links to Cal.com (booking) and LinkedIn
- Contact by email
