# La Lueur — Déploiement sur GitHub Pages (5 minutes)

## Étapes (depuis github.com, connecté au compte Design-Effect)

1. **Nouveau dépôt** : github.com → bouton "New" → nom : `la-lueur` → Public → Create repository
2. **Upload** : lien "uploading an existing file" → glisser les **7 fichiers** de ce dossier
   (index.html, enfants.html, manifest.json, manifest-enfants.json, sw.js, icon-192.png, icon-512.png)
   → bouton "Commit changes"
3. **Activer Pages** : Settings → Pages → Source "Deploy from a branch" → Branch `main`, dossier `/ (root)` → Save
4. **Attendre 1-2 minutes**, puis ouvrir :
   - Jeu principal : **https://design-effect.github.io/la-lueur/**
   - Version enfants : **https://design-effect.github.io/la-lueur/enfants.html**

## Installer comme une application

Sur le téléphone, ouvrir l'URL dans Chrome → menu ⋮ → **"Installer l'application"**
(ou "Ajouter à l'écran d'accueil"). Faire pareil depuis enfants.html pour installer
la version enfants comme une appli séparée, avec sa propre icône.

Une fois installé : plein écran, icône dorée, et jouable même sans connexion.

## Mises à jour futures

Remplacer index.html (ou enfants.html) dans le dépôt et, dans sw.js, changer
`la-lueur-v1` en `la-lueur-v2` pour forcer la mise à jour du cache chez les joueurs.
