# SIRH Intelligence Pro

Presentation HTML du projet SIRH et juridique augmentes par IA, avec automatisation complete.

## Fichiers principaux

- `index.html` : page a publier via GitHub Pages
- `presentation_sirh_ia.html` : version source de la presentation

## Publication sur GitHub Pages

1. Creez un depot GitHub vide, par exemple `sirh-intelligence-pro-presentation`.
2. Dans ce dossier local, executez :

```bash
git branch -M main
git add index.html presentation_sirh_ia.html README.md .gitignore .nojekyll
git commit -m "Initial presentation"
git remote add origin https://github.com/VOTRE-UTILISATEUR/sirh-intelligence-pro-presentation.git
git push -u origin main
```

3. Sur GitHub, ouvrez `Settings` > `Pages`.
4. Dans `Build and deployment`, choisissez `Deploy from a branch`.
5. Selectionnez la branche `main` et le dossier `/ (root)`.
6. Enregistrez.

Votre presentation sera ensuite accessible a l'adresse :

`https://VOTRE-UTILISATEUR.github.io/sirh-intelligence-pro-presentation/`

## Apercu local

Ouvrez simplement `index.html` dans un navigateur pour verifier le rendu.
