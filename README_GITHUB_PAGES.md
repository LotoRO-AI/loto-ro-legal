# LotoRO - Legal Docs (GitHub Pages)

## Ce conține
- `index.html` - pagină index cu link-uri
- `privacy-policy.html` - Politica de Confidențialitate
- `terms.html` - Termeni și Condiții

## Cum publici (fără terminal)
1. Creează un repo pe GitHub (ex: `loto-ro-legal`)
2. Apasă "Add file" → "Upload files"
3. Încarcă toate fișierele din acest folder (inclusiv `index.html`)
4. Settings → Pages → "Branch: main, / (root)" → Save
5. URL devine: `https://<username>.github.io/loto-ro-legal/`
   - Privacy Policy: `https://<username>.github.io/loto-ro-legal/privacy-policy.html`
   - Terms: `https://<username>.github.io/loto-ro-legal/terms.html`

## Cum publici (cu terminal)
```bash
# în afara GitHub, local
mkdir loto-ro-legal && cd loto-ro-legal
cp -R /Users/liviu/Downloads/LotoRO/loto_ro/play_store_assets/legal_site/* .
git init
git add .
git commit -m "Add legal docs"
# pe GitHub: creează repo gol "loto-ro-legal" (fără README)
# apoi:
git remote add origin git@github.com:<username>/loto-ro-legal.git
git branch -M main
git push -u origin main
# activează GitHub Pages: Settings → Pages → Branch: main, / (root)
```
