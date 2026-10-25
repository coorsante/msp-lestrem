# Site de la Maison de Santé de Lestrem

Site statique, un seul fichier : `index.html` (images incluses).

## Mise en ligne avec GitHub Pages
1. Créer un dépôt public, par ex. `msp-lestrem`.
2. Add file → Upload files → déposer `index.html` → Commit.
3. Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/ (root)` → Save.
4. Le site est en ligne après 1 à 2 minutes sur `https://<compte>.github.io/msp-lestrem/`.

## Nom de domaine (optionnel)
Settings → Pages → Custom domain (ex. `maisonsantelestrem.fr`), puis chez le registrar :
un enregistrement CNAME `www` → `<compte>.github.io`, et des enregistrements A vers
185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153. Cocher « Enforce HTTPS ».
