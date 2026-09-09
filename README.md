# Tir aux Mots

Stand de tir de fête foraine pour apprendre à lire vite (décors : ballons, voitures, fusées, avions, poissons, fantômes ; modes détente/chrono/attaque ; arsenal revolver → fusil → sniper avec zoom ; espace parents pour gérer la liste de mots).

- `index.html` : document HTML complet et autonome (peut s'ouvrir directement dans un navigateur ; utilise `localStorage` pour sauvegarder mots/scores/progression quand il tourne hors de Claude).
- `artifact-fragment.html` : le même contenu, sans les balises `<!doctype>/<html>/<head>/<body>`, au format attendu par l'outil Artifact de Claude (utilise la base de données de l'artifact pour la sauvegarde partagée). C'est ce fragment qui est publié en ligne.

Version publiée (à jour) : https://claude.ai/code/artifact/cdfebe72-0d1d-4245-8fc9-ebe6fd21c6d3
