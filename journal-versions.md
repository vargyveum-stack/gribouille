# Gribouille — journal de versions

Numérotation : bêta 0.x jusqu'à la première version jouable, qui deviendra la 1.0 sur ta demande.
La version courante s'affiche en bas du menu de l'application.

## Bêta 0.30 (test) — 12 octobre 2026

- Petite bulle de Gribouille : elle apparaît alternativement à droite, puis à gauche de sa tête, et ainsi de suite (la pointe suit le côté).
- Un toucher ailleurs que sur Gribouille referme la bulle (comme un nouveau toucher sur la tête).
- Menu : les anecdotes s'espacent maintenant de 15 s (le message d'accueil reste aussi affiché 15 s).
- Sauvegarde de la version précédente : `gribouille-bêta-0.29.html`.

## Bêta 0.29 (test) — 12 octobre 2026

- Petite bulle de Gribouille : elle apparaît au 5e toucher sur sa tête (texte suivant de la liste de 5), un toucher la referme, et il faut de nouveau 5 touchers pour la bulle suivante (elle ne disparaît plus toute seule). Après la 5e bulle, la liste recommence.
- Texte corrigé : « Qu'est-ce que tu as à me toucher comme ça ? ».
- Sauvegarde de la version précédente : `gribouille-bêta-0.28.html`.

## Bêta 0.28 (test) — 12 octobre 2026

- Menu : la bulle de Gribouille garde son message d'accueil 10 s, puis une anecdote s'affiche toutes les 10 s (« Le savais-tu ? », « C'est surprenant : »…), écrite à la même vitesse que le reste du texte (délai porté à 15 s en 0.30). Base de 55 anecdotes d'une phrase sur le dessin, les peintres, les dessinateurs, la BD et ses personnages (Tintin, Astérix, Lucky Luke, Gaston, Schtroumpfs, Snoopy, Corto Maltese…), tirées sans répétition tant que toute la liste n'est pas passée.
- La bulle du menu a une taille fixe : la hauteur de l'anecdote la plus longue, 3 lignes maximum (vérifié en largeur 360 et 390 px).
- Toucher la tête de Gribouille : à partir du 5e toucher, une petite bulle apparaît à côté de sa tête, avec 5 textes qui se suivent (« Et fais attention où tu mets ton doigt ! » … « Sers-toi plutôt de ton doigt pour jouer. »), puis ça recommence. Elle disparaît seule après 4 s (modifié en 0.29).
- Après chaque dessin, Gribouille commente maintenant toujours (plus de tirage au sort), y compris après le dernier dessin, avant le classement. Trous bouchés : le dernier dessin n'avait aucune réaction.
- Réactions variées, un peu taquines et sarcastiques, jamais la même deux fois de suite : personne ne trouve (6), un seul trouve (6), plusieurs trouvent mais pas tous (5), tout le monde trouve (5), équipe qui marque (6), équipe qui ne marque pas (6).
- Sauvegarde de la version précédente : `gribouille-bêta-0.27.html`.

## Bêta 0.27 (test) — 12 octobre 2026

- Écran d'accueil : quand on touche l'écran, l'animation de présentation s'efface en fondu enchaîné d'environ 1 seconde sur le menu (au lieu d'un changement brusque). Le menu est déjà utilisable pendant le fondu.
- Sauvegarde de la version précédente : `gribouille-bêta-0.26.html`.

## Bêta 0.26 (test) — 12 octobre 2026

- Correction : en touchant Gribouille plusieurs fois de suite, des sons pouvaient rester bloqués en continu. Chaque nouveau son coupe désormais le précédent (et ses oscillateurs sont bien arrêtés), donc un seul son joue à la fois.
- Sauvegarde de la version précédente : `gribouille-bêta-0.25.html`.

## Bêta 0.25 (test) — 12 octobre 2026

- Réglages de chaque partie (tous modes, chacun pour soi ou équipes) : nouveau réglage « Temps pour dessiner », avec boutons − et + par pas de 5 s. La valeur par défaut du mode est le minimum, et on peut monter jusqu'au double (ex. Mot-valise 30 s → 60 s).
- Megamix : le réglage ajoute des secondes à chaque mode, jusqu'à +15 s (pour qu'aucun mode ne dépasse le double de sa durée).
- Le chrono, le tic-tac, les flashs, l'annonce de manche et l'écran de préparation suivent le temps choisi. La durée choisie est mémorisée par mode tant que l'appli reste ouverte.
- Sauvegarde de la version précédente : `gribouille-bêta-0.24.html`.

## Bêta 0.24 (test) — 12 octobre 2026

- Écran d'accueil : Gribouille se dessine deux fois plus vite (environ 2 secondes au lieu de 4 à 5).
- Sauvegarde de la version précédente : `gribouille-bêta-0.23.html`.

## Bêta 0.23 (test) — 12 octobre 2026

- Écran d'accueil : fond blanc, Gribouille se dessine au crayon (un crayon suit le trait), puis se colorie, s'anime et fait un petit saut. Un toucher n'importe où mène au menu, et débloque le son.
- Menu : Gribouille est en haut, avec une petite animation rigolote de temps en temps (mouvement, expression, petit cri de voix si le son est activé). Plus d'histoire de sommeil. La bulle en dessous est fixe : « Choisis un mode, puis passez-vous le téléphone… ». Si le narrateur est coupé, le texte d'origine revient.
- Après un dessin : quand personne n'a trouvé (ou que l'équipier n'a pas trouvé), Gribouille commente maintenant toujours. Le commentaire s'affiche dans un cadre blanc par-dessus l'écran, plus lisible.
- Bulles : la pointe est désormais toujours centrée sur le côté de la bulle (elle était décalée sur certaines bulles courtes, notamment au début des tours).
- Sauvegarde de la version précédente : `gribouille-bêta-0.22.html`.

## Bêta 0.22 (test) — 12 octobre 2026

- Narrateur : texte des bulles 2 fois plus rapide (une lettre toutes les 17 ms au lieu de 34). La voix suit : les glissements entre voyelles, les souffles et les fins de phrase sont accélérés dans la même proportion.
- Sauvegarde de la version précédente : `gribouille-bêta-0.21.html`.

## Bêta 0.21 (test) — 11 octobre 2026

- Narrateur, son : au lancement, Gribouille dort tant qu'on n'a pas touché l'écran (le navigateur interdit le son avant), puis se réveille et salue avec sa voix dès le premier toucher.
- Voix : une seule voix continue dont les voyelles glissent de l'une à l'autre, au lieu de petits sons séparés par des silences. Les mots sont séparés par un souffle, les fins de phrase retombent (ou montent pour une question).
- Bulle : elle s'affiche d'emblée à sa taille définitive, et le texte s'inscrit dedans. Texte plus rapide (une lettre toutes les 34 ms au lieu de 55).
- Résultat d'un dessin : Gribouille réagit en surimpression sur le même écran, une fois les points attribués, avant le joueur suivant (il se referme seul, ou au toucher / « Continuer »). Il ne commente plus sur l'écran du joueur suivant, qui garde seulement « C'est parti » au premier dessin et « Dernier dessin » à la fin.
- Sauvegarde de la version précédente : `gribouille-bêta-0.20.html`.

## Bêta 0.20 (test) — 11 octobre 2026

- Gribouille, le personnage animé, devient le narrateur du jeu (version de TEST, retour possible : copie de la 0.19 conservée dans `gribouille-bêta-0.19.html`).
- Il apparaît en grand, puis en petit : menu d'accueil (salutation), écran « La partie » au lancement (2-3 bulles qui expliquent le mode, les points et le nombre de tours, boutons « Suivant » / « Passer »), annonce de manche en Megamix, écran de préparation entre les dessins (réaction au résultat précédent), classement final (commentaire).
- Jamais pendant un dessin : il est masqué et son animation s'arrête dès « Je suis prêt ». Ses bulles ne bloquent rien. Les consignes écrites restent, il les complète.
- Présence mesurée : toujours au début et à la fin, sinon environ 6 tours sur 10, jamais deux silences de suite.
- Voix de synthèse : petits sons de voyelles proches du « waouh » de la révélation (coupés avec le bouton Son).
- Bouton « Narrateur : activé / coupé » en bas du menu (mémorisé sur l'appareil). Pour le retirer complètement : `GRIBOUILLE_TEST = false` dans le script.
- « Rejouer avec les mêmes joueurs » saute l'écran « La partie ».

## Bêta 0.19 — 11 octobre 2026

- Icônes sur les boutons, dans le style de la planche (trait arrondi, couleur du bouton) : « Comment jouer » (point d'interrogation), « Ajouter des mots » (plus), « Son » (haut-parleur, barré quand coupé), « Lancer la partie » (lecture), « Annuler » (retour), « Effacer » (corbeille), « Revoir le mot » et « Révéler le mot » (œil), « Terminé », « Je suis prêt » et « Trouvé » (coche), « Pas trouvé » (croix), « Rejouer » (flèche circulaire), « Réglages » (curseurs), « Menu » (maison).
- Une icône s'ajoute à un bouton avec l'attribut data-icon="nom" ; les dessins sont regroupés dans un bloc « ICÔNES DES BOUTONS » à la fin du CSS. Les boutons « ← Menu », « Continuer » et « Valider » gardent leur flèche.

## Bêta 0.18 — 11 octobre 2026

- Nombre de tours par défaut fixé à 3 pour tous les modes (Megamix compris, qui était à 5), en chacun pour soi comme en équipes. Le réglage reste modifiable de 1 à 10 tours.

## Bêta 0.17 — 11 octobre 2026

- Nouveau style graphique des boutons et des cartes, d'après la planche de boutons : pilules à contour vert par défaut, bouton principal bleu plein avec flèche, retour cyan, « Ajouter des mots » rose, « Son » en lien texte, boutons − et + ronds, cartes des modes plus arrondies avec pastille bleu clair. États survol, appui et désactivé inclus, thème sombre compris.
- Tout le style tient dans un seul bloc « THÈME GRAPHIQUE » à la fin du CSS du fichier, piloté par des variables (couleurs, arrondi, hauteur) : on peut le modifier sans toucher au reste. Le style est provisoire et sera probablement retouché.

## Bêta 0.16 — 11 octobre 2026

- Choix du type de partie : en touchant un mode (Megamix compris), une fenêtre demande « Chacun pour soi » ou « Équipes de deux ». L'écran de réglages s'adapte ensuite (joueurs ou équipes). La case à cocher des réglages est supprimée.

## Bêta 0.15 — 11 octobre 2026

- Jeu en équipes de deux : une case « Jouer en équipes de deux » dans les réglages de chaque mode (Megamix compris). On saisit le nom de chaque équipe (2 à 6 équipes).
- Dans une équipe, un joueur dessine et son équipier devine. Un tour, c'est chaque joueur de chaque équipe qui dessine une fois : les équipes passent dans l'ordre, puis le second joueur de chaque équipe.
- Validation en équipe : au lieu de cocher des noms, deux boutons « Trouvé » / « Pas trouvé ». Chaque mot trouvé rapporte 1 point à l'équipe.
- Classement, écran de préparation et « Comment jouer » adaptés (nouvelle carte « Jouer en équipe »). Le jeu sans équipe est inchangé.

## Bêta 0.14 — 11 octobre 2026

- Mots : un mot sorti ne revient plus avant 30 minutes, quel que soit le mode et même d'une partie à l'autre, tant que c'est sur le même téléphone. L'heure de sortie de chaque mot est mémorisée sur l'appareil (horloge du téléphone), et les mots plus anciens que 30 minutes sont oubliés automatiquement.
- Si une liste était presque épuisée par ce délai, l'application retombe sur la seule règle « pas deux fois dans la même partie » plutôt que de bloquer.
- « Comment jouer » : règle mise à jour.

## Bêta 0.13 — 11 octobre 2026

- Base de mots portée à 1200 mots : Mot-valise passe à 6 familles de 200 mots (mêmes familles qu'avant), et les modes à un seul mot (Aveugle, Lâche pas le trait, Recto verso, Tremblement de trait) à 1200 mots. Les mots ajoutés par les joueurs sont conservés, et un mot ne ressort toujours qu'une fois par partie.
- Tic-tac : le tempo de fin monte à 300 BPM (au lieu de 240), toujours de façon linéaire depuis 60 BPM sur la durée du mode.

## Bêta 0.12 — 11 octobre 2026

- Tic-tac : le tempo de fin monte à 240 BPM (au lieu de 200), toujours de façon linéaire depuis 60 BPM sur la durée du mode.

## Bêta 0.11 — 11 octobre 2026

- Mots : un mot ne ressort plus deux fois dans la même partie, tous modes confondus (en Megamix aussi, d'un mode à l'autre). Chaque nouvelle partie repart de zéro.
- Base de mots portée à 600 mots pour Mot-valise (6 familles de 100) et 600 mots pour les modes à un seul mot (Aveugle, Lâche pas le trait, Recto verso, Tremblement de trait). Les mots ajoutés par les joueurs sont conservés.
- Tic-tac : le tempo monte maintenant jusqu'à 200 BPM (au lieu de 180), toujours de façon linéaire sur la durée du mode.
- Nouveau son « tada » quand le chrono arrive à zéro (pas quand le joueur termine lui-même).
- Nouveau son « waouh » admiratif au clic sur « Révéler le mot » ou « Révéler les mots ».
- « Comment jouer » : mention du tada, du waouh et de la règle « un mot une seule fois par partie ».

## Bêta 0.10 — 11 octobre 2026

- Tic-tac : le tempo monte maintenant de 60 à 180 BPM (au lieu de 160), de façon linéaire sur toute la durée du chrono.
- Mot-valise : durée ramenée de 45 s à 30 s. Le tic-tac s'adapte tout seul à cette durée ; le menu et « Comment jouer » sont mis à jour.
- Correction de la version HTML autonome, où cliquer sur les modes ne faisait rien : le fichier n'avait ni déclaration d'encodage ni règle pour les éléments cachés, deux choses que la version en ligne ajoute d'elle-même. Les deux sont maintenant dans le fichier, et le nettoyage des accents dans l'ajout de mots n'en dépend plus.

## Bêta 0.9 — 11 octobre 2026

- Tic-tac pendant le dessin : il démarre à 60 BPM au premier trait et accélère de façon linéaire jusqu'à 160 BPM à la fin du chrono. La progression s'adapte à la durée de chaque mode (15, 20 ou 45 s). Il s'arrête dès que le dessin se termine.
- Bouton « Son : activé / coupé » en bas du menu, mémorisé sur l'appareil.
- « Comment jouer » : mention du tic-tac et du bouton Son.
- Version HTML autonome fournie dans un dossier.

## Bêta 0.8 — 11 octobre 2026

- Nouveau système de points : c'est le dessinateur qui marque, 1 point par joueur qui a deviné son dessin. Les joueurs qui devinent ne reçoivent plus de point.
- À l'écran de validation, le nombre de points gagnés par le dessinateur s'affiche au fur et à mesure qu'on coche les joueurs.
- « Comment jouer » : nouvelle carte « Les points » qui explique ce système, et le principe général est corrigé.

## Bêta 0.7 — 11 octobre 2026

- Tremblement de trait : durée ramenée à 15 s, un tremblement toutes les 3 s (à 3, 6, 9 et 12 s) de 0,5 s, annoncé par un flash 0,5 s avant. Mouvement un peu plus rapide (environ 20 changements de position par seconde), amplitude inchangée.

## Bêta 0.6 — 11 octobre 2026

- Tremblement de trait : tremblement plus rapide (environ 14 changements de position par seconde, contre 8), avec la même amplitude de 18 px.

## Bêta 0.5 — 11 octobre 2026

- Tremblement de trait : le tremblement dure 1 s (au lieu de 0,5 s), avec une amplitude plus large (18 px au lieu de 12 px) et un mouvement plus lent. Le flash d'annonce reste à 0,5 s avant.

## Bêta 0.4 — 11 octobre 2026

- Mot-valise : durée ramenée de 60 s à 45 s.

## Bêta 0.3 — 11 octobre 2026

- Nouveau mode : Tremblement de trait (20 s). Toutes les 5 s, un flash puis la zone de dessin tremble pendant 0,5 s. Si le doigt reste immobile, la zone bouge sous lui et ça trace quand même.
- Megamix : passe à 5 modes, séries de 5 tours (5 tours par défaut), chaque mode une seule fois par série.

## Bêta 0.2 — 11 octobre 2026

- Megamix : un écran d'annonce s'affiche avant chaque manche, avec le numéro de manche, le nom du mode, sa durée et son résumé.

## Bêta 0.1 — 11 octobre 2026

Première version numérotée.

- Quatre modes de jeu plus le Megamix.
  - Mot-valise (60 s) : deux mots à fusionner en un seul dessin.
  - Dessin à l'aveugle (15 s) : trait invisible, traînée blanche de 0,5 s, révélation animée.
  - Lâche pas le trait (20 s) : un seul trait, la partie s'arrête dès que le doigt se lève.
  - Recto verso (20 s) : le dessin se retourne en miroir haut/bas toutes les 5 s, avec un flash 0,5 s avant.
  - Megamix : un mode différent à chaque tour, tiré au hasard. Séries de 4 tours avec chaque mode une seule fois, puis nouvelle série.
- Joueurs nommés (2 à 8), tours réglables, 1 point par joueur qui devine, classement final.
- Mots ajoutés par les joueurs, gardés sur l'appareil, tirés avec le même hasard que les mots d'origine.
- Écran « Comment jouer » : le principe du jeu et les règles de chaque mode.
- Mention « version test » retirée du menu.

Abandonné pendant cette version : le mode « Tremblement de trait » (vibreur), remplacé par Recto verso.
