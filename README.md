# vzev.be

Static marketing website for www.vzev.be (single `index.html`).

## Deploy

Not automated. The live copy is `~/vzev.be/` on the Plesk server (`ssh hof5`).
Copy changed files manually, e.g.:

```bash
scp index.html hof5:~/vzev.be/index.html
```

## Contact form

Uses [FormSubmit](https://formsubmit.co) with `action="https://formsubmit.co/contact@vzev.be"`.
Do not add the `_honey` honeypot field or switch to a FormSubmit alias:
submissions stopped arriving with either (tested 03.11.2026).
