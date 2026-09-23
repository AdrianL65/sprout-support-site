# sprout-support-site

Public home and help pages for **Sprout**, served by GitHub Pages at
**https://sprout-support.mikrodev.net**.

| Path | What |
|---|---|
| `/` | Sprout home (features, Plus pricing) - store "Marketing URL" |
| `/faq/` | Help and contact - store "Support URL" |
| `/icon.png` | 512 px app icon, used by the auth email templates |

Policies live in the sibling site `sprout-legal-site` (https://sprout-legal.mikrodev.net).

## Editing
Plain HTML + `assets/site.css`. No build step: edit, commit, push, and Pages redeploys in about a minute.

- `assets/site.css` is shared with `sprout-legal-site`. Change it here, then copy it there.
- Icons are Phosphor (MIT) SVGs pasted inline. Font is Outfit (SIL Open Font License), self-hosted in `assets/fonts/`.
- Preview locally: `python3 -m http.server 8000` in this folder, then open http://localhost:8000.
- Prices on the home page must match `lib/utils/plus_config.dart` in the app repo.
