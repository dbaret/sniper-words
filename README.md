# Tir aux Mots

Stand de tir de fête foraine pour apprendre à lire vite.

Décors : ballons, voitures, fusées, avions, poissons, fantômes.
Modes : détente, chrono, attaque.
Difficultés : débutant (mot cible en couleur), avancé (aucun indice de couleur), expert (aucun indice + police et casse variables sur les mots).
Bonus à ramasser en jeu (touches 1/2/3 ou boutons à l'écran) : horloge (ralenti), bombe (efface l'écran sans perdre de point), tête chercheuse (tir automatique sur le bon mot).
Arsenal : revolver → fusil → fusil sniper (zoom).
Espace parents protégé par une question de calcul, pour gérer la liste de mots.

- `index.html` : document HTML complet et autonome (peut s'ouvrir directement dans un navigateur ; utilise `localStorage` pour sauvegarder mots/scores/progression quand il tourne hors de Claude).
- `artifact-fragment.html` : le même contenu, sans les balises `<!doctype>/<html>/<head>/<body>`, au format attendu par l'outil Artifact de Claude (utilise la base de données de l'artifact pour la sauvegarde partagée). C'est ce fragment qui est publié en ligne.

Version publiée (à jour) : https://claude.ai/code/artifact/cdfebe72-0d1d-4245-8fc9-ebe6fd21c6d3
