# FWC 26 Album

Suivi de collection de vignettes pour la Coupe du Monde 2026. Marquez vos vignettes manquantes et doubles, exportez votre collection en QR code et trouvez les echanges possibles avec d'autres collectionneurs.

**[Ouvrir l'application](https://Vtik.github.io/fwc26-album/)**

## Fonctionnalites

- 48 equipes officielles classees par groupe (A-L) + sections speciales FWC et Coca-Cola
- 3 etats par vignette : collectee (defaut), manquante, double
- Recherche rapide par nom ou code FIFA
- Navigation clavier (fleches, Ctrl+K)
- Progression globale et par equipe
- Export QR code avec pseudo et lien du site
- Import QR code (image) pour comparer deux collections
- Calcul automatique des echanges possibles (mes doubles vs leurs manquantes)
- Copier les echanges pour envoi par messagerie
- Historique des imports pour comparer plusieurs collectionneurs
- Donnees sauvegardees localement (localStorage)
- Interface responsive (desktop + mobile)
- Zero dependance build, HTML/CSS/JS pur

## Utilisation

1. Entrez votre pseudo
2. Parcourez les equipes et marquez vos vignettes (clic = cycler l'etat)
3. Exportez votre QR code et partagez-le sur un forum ou par messagerie
4. Importez le QR d'un autre collectionneur pour voir les echanges possibles

## Deploiement

Le site se deploie automatiquement sur GitHub Pages via le workflow inclus.

```bash
git remote add origin https://github.com/Vtik/fwc26-album.git
git push -u origin main
```

Puis activer Pages dans Settings > Pages > Source : GitHub Actions.

## Tech

- HTML / CSS / JavaScript vanilla
- [qrcode-generator](https://github.com/nicoschmidt/qrcode-generator) pour la generation QR
- [jsQR](https://github.com/nicoschmidt/jsQR) pour la lecture QR
- GitHub Actions pour le deploiement

## Licence

MIT
