# Pilotage Formation Bloc Opératoire

Application HTML autonome pour le suivi pédagogique en bloc opératoire.

## Contenu
- suivi multi-apprenants
- pilotage des compétences par spécialité
- journal des vacations
- bilan formatif
- vue équipe
- export JSON local

## Usage local
Ouvrir `index.html` dans un navigateur moderne.

## Publication GitHub Pages
1. Créer un dépôt GitHub
2. Déposer `index.html` et `README.md`
3. Aller dans **Settings > Pages**
4. Choisir **Deploy from a branch**
5. Sélectionner `main` puis `/(root)`

Le site sera ensuite publié à une adresse du type :
`https://votre-utilisateur.github.io/nom-du-depot/`

## Important
Cette version stocke les données dans le navigateur via `localStorage`.
Elle convient à une démo, un prototype ou un usage individuel local.
Elle n'est pas conçue pour un usage multi-utilisateurs sécurisé ni pour héberger des données nominatives réelles.

## Structure
- `index.html` : application principale
- `README.md` : mode d'emploi
- `.nojekyll` : facilite GitHub Pages
