# Mon Site — Starter statique (sans base de données)

Ce kit vous permet de publier des **photos** et des **articles** très facilement. Il fonctionne sur n'importe quel hébergement statique (Netlify, GitHub Pages, OVH Pages, etc.).

## Ajouter des photos
1. Placez vos images dans le dossier `photos/` (JPG, PNG, SVG…).
2. Ouvrez `photos.html` et dupliquez un bloc `<figure>` en changeant le chemin et la légende.

## Ajouter un article
1. Dupliquez `posts/mon-premier-article.html` → renommez-le (ex. `posts/mon-super-article.html`).
2. Éditez le titre et le contenu dans le fichier.
3. Ouvrez `articles.html` et ajoutez un `<li><a href="posts/mon-super-article.html">Titre</a></li>`.

## Modifier l'apparence
- Changez les couleurs, espacements, etc. dans `styles.css`.
- Modifiez les textes de navigation dans `index.html` et autres pages.

## Tester en local
Double‑cliquez sur `index.html` pour ouvrir dans votre navigateur.
> Astuce: si des images ne s'affichent pas, vérifiez simplement les chemins (ex. `photos/monimage.jpg`).

## Mettre en ligne (hébergement statique)
Option A (très simple): service à dépôt **par glisser‑déposer**. 
- Connectez-vous, créez un nouveau site, **glissez le dossier du projet** (tous les fichiers) dans l'interface → vous recevez une URL publique.
- Pour lier votre **nom de domaine**, ajoutez un **CNAME** `www` pointant vers l'URL technique fournie (ex. `votresite.netlify.app`) puis suivez les instructions de l'hébergeur pour le domaine racine.

Option B: **GitHub Pages**
1. Créez un dépôt et poussez tous les fichiers.
2. Dans **Settings → Pages**, choisissez la branche `main` et le dossier `/root`.
3. GitHub vous donne une URL. Pour votre domaine, ajoutez un fichier `CNAME` avec `votre-domaine.fr`.

## Légal minimum (France/UE)
- Remplissez `mentions-legales.html` (éditeur, contact, hébergeur).
- Si vous ajoutez des outils d'analyse/marketing, ajoutez un bandeau de consentement cookies.

Bonnes publications !
