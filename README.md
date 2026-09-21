# boxaroo-legal

Pages publiques de Boxaroo (`com.crossover.boxaroo`).

Ce depot ne contient que du texte a publier. Le code du jeu vit ailleurs.

- `index.html` — politique de confidentialite, francais et anglais sur la
  meme page. C'est l'URL exigee par la Play Console.
- `.nojekyll` — sert la page telle quelle, sans passer par Jekyll.

## Publication

GitHub Pages sert directement la branche `main` :
**Settings > Pages > Build and deployment > Source : Deploy from a branch,
`main` / `/ (root)`**.

Aucun workflow n'est necessaire. Une tentative d'activation automatique par
`actions/configure-pages` a echoue : le jeton d'Actions n'a pas le droit de
creer un site Pages sur ce depot.

La source de verite de la page est `store/confidentialite.html` dans le depot
Boxaroo ; `index.html` en est la copie publiee.
