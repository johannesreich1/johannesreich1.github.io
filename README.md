# johannesreich.info

The website at https://johannesreich.info, served by GitHub Pages from `main`.

- `/halotone/` introduces Halotone, with its support page (`/halotone/support/`) and
  privacy policy (`/halotone/privacy/`); App Store Connect links to both.
- `/impressum/` is the legal notice German law asks for.

Plain HTML and one stylesheet, no build step. The colors follow Halotone's palette
(`web-ds/tokens.json` in the app's repository); the icons are resized from its app icon.

DNS lives at IONOS: GitHub's A and AAAA records on the apex, `www` as a CNAME to
`johannesreich1.github.io`, and the mail records for contact@johannesreich.info left as
IONOS set them.
