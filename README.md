# ✨ QR Studio

Petit site avec deux onglets :

- **Scanner** : affiche le QR code stylé qui mène à la liste d’envies Amazon.
- **Générer** : écris un lien ou un texte, le QR code se met à jour en direct (palettes de couleurs, styles de points et de coins).

## Fichiers

```
index.html                 La page (HTML, CSS et JavaScript dans un seul fichier)
assets/qr-wishlist.jpeg    Le QR code à scanner
README.md                  Ce fichier
```

## Mettre en ligne avec GitHub Pages

1. Crée un dépôt sur GitHub (par exemple `qr-studio`), en public.
2. Envoie-y ces fichiers : `index.html`, `README.md` et le dossier `assets` (avec l’image dedans).
3. Dans le dépôt, va dans **Settings → Pages**.
4. Sous **Build and deployment**, choisis **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`, et enregistre.
5. Après une minute environ, ton site est disponible à l’adresse `https://TON-PSEUDO.github.io/qr-studio/`.

## Changer le lien du QR code à scanner

Le QR code de l’onglet Scanner est une image (`assets/qr-wishlist.jpeg`). Pour le remplacer, génère-en un nouveau dans l’onglet Générer, enregistre-le, puis remplace l’image. Pense aussi à changer le lien du bouton « Ouvrir la liste d’envies » dans `index.html`.

## Notes

La bibliothèque [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) est chargée depuis le CDN jsDelivr : il faut une connexion internet pour que l’onglet Générer fonctionne.
