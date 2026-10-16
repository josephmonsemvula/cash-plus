# Cash Plus — application web installable (PWA)

## Publier gratuitement (GitHub Pages)
1. Créez un dépôt GitHub (ex. `cash-plus`) et envoyez-y **tout le contenu de ce dossier** (index.html, manifest.webmanifest, sw.js, les 3 icônes).
2. Dépôt > **Settings > Pages** > Source : branche `main`, dossier `/ (root)` > Save.
3. Après 1 à 2 minutes, votre lien est `https://VOTRE-NOM.github.io/cash-plus/`.
Alternative sans Git : glissez le dossier sur https://app.netlify.com/drop (ou Cloudflare Pages / Vercel).

## Installer sur un téléphone
- Android (Chrome) : ouvrez le lien, puis Plus > « Installer Cash Plus », ou menu ⋮ > Installer l’application.
- iPhone (Safari) : Partager > Sur l’écran d’accueil.
L’icône et l’écran de démarrage Cash Plus apparaissent, et l’application s’ouvre en plein écran, même sans internet.

## Mise à jour
Après avoir modifié index.html, changez `cashplus-v1` en `cashplus-v2` dans sw.js pour que les téléphones reçoivent la nouvelle version.

## Important
- **Administration intégrée** : dans l’application, appuyez 10 fois de suite sur le logo, entrez votre code secret, et l’espace administrateur s’ouvre. La clé de signature est chiffrée avec ce code : choisissez un code long et gardez-le confidentiel.
- Les licences sont liées à l’appareil : un code ne fonctionne que sur le téléphone pour lequel il a été généré.
