# Tir aux Mots

Stand de tir de fête foraine pour apprendre à lire vite (et à calculer).

Décors : ballons, voitures, fusées, avions, poissons, fantômes, immeubles (vitrine pour le sniper), zombies, licornes.
Modes : détente, chrono, attaque (les mots foncent sur toi, 3 vies), dragon (un dragon crache le feu si tu rates le bon mot à temps, 3 vies).
Matières : lecture (mots à reconnaître), maths (additions, soustractions, multiplications, divisions — au choix), ou tout mélangé au hasard.
Difficultés : débutant (mot cible en couleur), avancé (aucun indice de couleur), expert (aucun indice + police et casse variables sur les mots).
Bonus à ramasser en jeu (touches 1/2/3 ou boutons à l'écran) : horloge (ralenti), bombe (efface l'écran sans perdre de point), tête chercheuse (tir automatique sur le bon mot).
Comportement réglable pour un tir sur une mauvaise cible : « Ça élimine » (la cible est détruite, pas de perte de points), « Ça n'élimine pas » (par défaut — la cible reste affichée, -1 point), « Ça élimine (malus) » (la cible est détruite et on perd la moitié des points).

Arsenal, débloqué en ramassant des pièces qui volent pendant la partie (10 pièces = arme suivante, dans l'ordre) :
revolver → fusil (tire plusieurs balles à la fois) → fusil sniper (zoom) → mitraillette (tir en rafale tant qu'on maintient le tir).

Espace parents protégé par une question de calcul, pour gérer la liste de mots et suivre la progression (records, pièces d'armes collectées).

- `index.html` : document HTML complet et autonome (peut s'ouvrir directement dans un navigateur ; utilise `localStorage` pour sauvegarder mots/scores/progression quand il tourne hors de Claude).
- `artifact-fragment.html` : le même contenu, sans les balises `<!doctype>/<html>/<head>/<body>`, au format attendu par l'outil Artifact de Claude (utilise la base de données de l'artifact pour la sauvegarde partagée). C'est ce fragment qui est publié en ligne.

Version publiée (à jour) : https://claude.ai/code/artifact/cdfebe72-0d1d-4245-8fc9-ebe6fd21c6d3
