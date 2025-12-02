# rilot
Omáda Téssera — Separated Files

This set contains the separated version of the single-file HTML you provided.

Files created:
- `coba.html` — HTML markup, links to CSS/JS, extracted styles, extracted script (catalog, cart, checkout, account simulation)

How to run:
1. From the project folder run a simple static server (recommended) and open `coba.html`.

Example using Python 3 built-in server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000/omada.html
```

Notes:
- Some product images reference local paths (e.g. `(https://github.com/aininuzulul21-prog/rilot/blob/main/coba.html)`). Those will work only on the machine where those files exist. Replace them with public URLs or add image files to the repo for consistent results.
- `omada.js` keeps the same behavior as the original single-file version (in-memory cart). Data is not persisted across refresh.
- If you want, I can update product image paths to use placeholders or add a small sample images folder.

