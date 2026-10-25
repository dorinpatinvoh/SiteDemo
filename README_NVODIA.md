# NVODIA — Site vitrine

## Installation sans casser les démos

Copie les fichiers de cette archive **à la racine** de ton dépôt `SiteDemo` existant, dans `D:\demos_commerciales\demos_commerciales`.

Conserve absolument tes dossiers `boutique/` et `restaurant/` actuels, avec leurs images. Les nouvelles pages les utilisent **sans les modifier** :

```
SiteDemo/
├── index.html                    ← nouvelle page NVODIA
├── services.html
├── realisations.html
├── tarifs.html
├── processus.html
├── contact.html
├── assets/
│   ├── style.css
│   └── app.js
├── boutique/                     ← dossier existant à conserver
│   ├── index.html
│   └── assets/
└── restaurant/                   ← dossier existant à conserver
    ├── index.html
    └── assets/
```

Ouvre `index.html` dans ton navigateur. Les deux démonstrations apparaissent via les chemins relatifs et leurs images existantes.

## Avant publication

- Vérifie le WhatsApp dans `contact.html`, `assets/app.js` et les liens de pages (actuellement **+229 01 56 23 04 06**).
- Vérifie que la marque **NVODIA** est libre avant toute formalisation (marque et domaine non vérifiés).
- La page utilise des polices Google Fonts ; si le réseau est coupé, elle utilise des polices système.
- Les prix sont des **offres commerciales proposées**, à confirmer en devis.
- Le formulaire ne stocke aucune donnée ; il prépare seulement un message WhatsApp.
- Le site ne revendique ni réalisations clients, ni société légalement enregistrée.

## Publication GitHub / Netlify

```powershell
git add .
git commit -m "Transformer la page demo en site vitrine NVODIA"
git push origin main
```

Netlify publiera les fichiers racine si le dépôt est déjà connecté à la branche `main` avec le publish directory `.`.
