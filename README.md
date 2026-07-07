# YuSleep Pre-Sell Landing Page

Static affiliate landing page for the YuSleep offer on ClickBank.

## Deployment (Hostinger Git Integration)

1. Push this repo to your Git provider (GitHub / GitLab / Bitbucket).
2. In Hostinger hPanel → **Hosting** → **Git** → connect repo → set branch to `main`.
3. Set the deploy path to `public_html/` (or the subdirectory you want).
4. Save — Hostinger will pull and serve `index.html` automatically.

## Files

- `index.html` — the landing page (single file, no dependencies)
- `.gitignore` — ignores OS clutter

## Customisation

- Swap the hop link in `index.html` if your tracking ID changes.
- Add a `<script>` tag for Google Analytics or Meta Pixel just before `</body>`.
