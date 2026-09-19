# EH OS Customer Operations Landing

Static landing page for secure access to the EH OS Customer Operations app.

## Deployment

Publish the repository with GitHub Pages from the `main` branch and repository root. The primary button sends authorized staff to the live Lovable app, where authentication occurs. This landing page never collects credentials.

## DNS

Do not change the existing `support.enrollhere.agency` DNS until the GitHub Pages deployment is live and verified. The email sender uses the separate delegated subdomain `notify.support.enrollhere.agency`.

The app currently redirects `ehos-csm.lovable.app` to `support.enrollhere.agency`. Before moving or delegating `support` for email, configure and verify a separate app hostname and update the button URL. Moving the landing page alone does not change the app's hostname or remove that redirect.
