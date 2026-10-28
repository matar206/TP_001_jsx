# Projet 001 : Mon CV en React

## Prérequis

- Node.js et npm installés (vérification avec `node -v` et `npm -v`)

## Étapes de création

1. Créer le projet avec Vite :
   ```bash
   npm create vite@latest 001
   ```
   Choix faits : framework **React**, variante **JavaScript**, linter **ESLint**, puis **No** à l'installation automatique.

2. Installer les dépendances :
   ```bash
   cd 001
   npm install
   ```

3. Lancer le projet :
   ```bash
   npm run dev
   ```
   Le site est accessible sur http://localhost:5173/

4. Nettoyer `src/App.jsx` pour retirer la page d'exemple de Vite.

5. Créer le dossier `src/components/` avec trois composants : `InfoPerso.jsx`, `Competences.jsx` et `Experiences.jsx`.

6. Importer et afficher les trois composants dans `App.jsx`.

## Rôle des dossiers et fichiers

- `node_modules/` : dépendances installées par npm (ne se modifie pas).
- `public/` : fichiers statiques servis tels quels (images, favicon).
- `src/` : code source de l'application.
  - `main.jsx` : point d'entrée, il affiche l'application React dans la page.
  - `App.jsx` : composant principal qui assemble le CV.
  - `components/` : les composants du CV.
  - `assets/` : images et ressources utilisées dans le code.
  - `index.css` : styles globaux.
- `index.html` : page HTML unique, avec la div `root` où React s'affiche.
- `package.json` : nom du projet, dépendances et scripts (`dev`, `build`...).
- `package-lock.json` : versions exactes des dépendances installées.
- `vite.config.js` : configuration de Vite.
- `eslint.config.js` : configuration du linter ESLint.
- `.gitignore` : fichiers que Git doit ignorer (par exemple `node_modules`).

## Les composants du CV

- `InfoPerso` : affiche mes informations personnelles.
- `Competences` : affiche la liste de mes compétences.
- `Experiences` : affiche mes expériences et projets.