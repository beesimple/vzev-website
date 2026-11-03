# vzev.be

Static website for www.vzev.be (single `index.html`).

## Deploy

A push to `main` is deployed automatically via Plesk Git (GitHub webhook)
to the document root of vzev.be. Files outside the repo (`.well-known`, `cgi-bin`)
are managed by Plesk and left untouched.

## Contact form

Uses [FormSubmit](https://formsubmit.co) with `action="https://formsubmit.co/contact@vzev.be"`.
Do not add the `_honey` honeypot field or switch to a FormSubmit alias:
submissions stopped arriving with either (tested 03.11.2026).
