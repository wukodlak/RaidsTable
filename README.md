# RaidsTable
Script permettant de gérer les rapports d'espionnages liés à ogame

Bug connus:
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Non affichage du tableau :
Menu OPTION (ogame) > Général > Dialogue en Ligne > COCHER la case Désactiver le dialogue en ligne > Sauvegarder les options


A une ligne correspond un rapport d'espionnage, nous y retrouvons
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
l'id du message dans la liste : un clique permet de descendre dans la page et arriver sur le rapport.
le joueur : avec les attributs de couleurs (bandit/honorable/inactif/grand inactif) et de timing d'activité lors du rapport d'espionnage.
les coordonnées : avec le symbole lune si ce n'est pas la planète, un clique permet d'aller dans la page galaxie.
la flotte : une infobulle indique le nombre de recycleurs qu'il faudrait fonction du pourcentage CDR de l'uni.
la défense : valeur de la défense.
le pillage : total des ressources présentes sur le RE. l'infobulle rappel le pourcentage pillé de ce butin fonction du joueur.
GT / PT : calcul le nombre de vaisseaux nécessaires pour obtenir le pillage maximum + 10 %.
PT2 : calcul le nombre de vaisseaux nécessaires pour une seconde vague de pillages.
Bouton attaque : ouverture d'une nouvelle page au clique avec les coordonnées pré indiquées (le bouton passe rouge au clique).
Bouton espionner : espionne directement la cible (le bouton passe en orange au clique).
Bouton SpeedSim : simulateur de combat fonction de la cible.
Bouton plus d'infos : affiche le rapport complet.
Bouton supprimer : supprime le rapport de la liste.

Fonctionnalités du script :
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
rappel du total du butin théorique et du fret nécessaire en partie haute du tableau
coloration une ligne sur 2 pour facilité de lecture.
lors du passage de la souris surlignage de l'entête des colonnes.
lors du passage de la souris surlignage de la ligne.
infobulles spécifiques.
tri des colonnes.
clique sur les liens GT / PT / PT2 pour envoyer le bon nombre de fret
surlignage rouge des texte dans des lignes ayant des flottes en attaque.
clique sur l'id (ex : #1) pour amener directement au rapport dans la page
clique sur la coordonnée pour ouvrir la page galaxie
