# KHAIRDIDACT — Les fondamentaux

Page des **10 fondamentaux pédagogiques** pour l'alphabétisation, le FLE et l'illettrisme — adultes en apprentissage du français.

Destinée à être embarquée dans Google Sites via iframe, dans la section *Agir suivant des valeurs › Les fondamentaux* de l'écosystème ALPA-FLE des formateurs salutistes bénévoles.

## Contenu du dépôt

- `index.html` — page standalone (typographie DM Serif Display + DM Sans, charte KHAIRDIDACT)
- `fondamentaux-pedagogiques.jpg` — infographie des 10 fondamentaux *(à ajouter avant le premier commit)*

## Déploiement sur GitHub Pages

```bash
git init
git add .
git commit -m "Initial commit : page Les fondamentaux"
git branch -M main
git remote add origin https://github.com/<user>/khairdidact-fondamentaux.git
git push -u origin main
```

Puis dans **Settings › Pages** : *Source* = `main` / `/ (root)`.

URL publique : `https://<user>.github.io/khairdidact-fondamentaux/`

## Embed Google Sites

Dans l'éditeur Google Sites :
1. *Insérer › Intégrer › Par URL*
2. Coller l'URL GitHub Pages ci-dessus
3. Redimensionner le cadre en hauteur pour éviter la double barre de défilement

## Mise à jour de l'image

Pour remplacer l'infographie, conserver le nom `fondamentaux-pedagogiques.jpg` ou mettre à jour le `src` dans `index.html`.
