# ⚡ Calculateur Énergie — PWA

Application web progressive (PWA) de simulation du coût énergétique sur 10 ans.

## Fichiers inclus

```
energie-pwa/
├── index.html       ← Application principale
├── manifest.json    ← Configuration PWA
├── sw.js            ← Service Worker (mode hors-ligne)
└── icons/           ← Icônes pour tous les appareils
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```

## Déploiement gratuit sur GitHub Pages

1. Créez un compte sur https://github.com
2. Cliquez sur **New repository**
3. Nommez-le `calculateur-energie`, cochez **Public**, cliquez **Create**
4. Cliquez **uploading an existing file**
5. Glissez-déposez TOUS les fichiers (index.html, manifest.json, sw.js) ET le dossier `icons/`
6. Cliquez **Commit changes**
7. Allez dans **Settings → Pages → Source** : choisissez `main` puis cliquez **Save**
8. Votre app sera disponible sur : `https://votre-pseudo.github.io/calculateur-energie`

## Installation sur téléphone

### iPhone (Safari)
1. Ouvrez l'URL dans Safari
2. Appuyez sur le bouton Partager (carré avec flèche)
3. Choisissez **"Sur l'écran d'accueil"**
4. L'icône ⚡ apparaît comme une vraie app !

### Android (Chrome)
1. Ouvrez l'URL dans Chrome
2. Une bannière apparaît automatiquement : **"Installer"**
3. Ou appuyez sur ⋮ → **"Ajouter à l'écran d'accueil"**

## Fonctionnement hors-ligne
Une fois installée, l'app fonctionne **sans connexion internet**.
