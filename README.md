# Hubert
site web de taxis
Hubert
Le menu déroulant

Cette fois-ci mon but était de reproduire le site d’Uber sans regarder le code source. Pour ce projet, j'ai utilisé le Framework W3 pour CSS.
J’ai décidé de le renommer Hubert afin de préserver la propriété intellectuelle de l’entreprise tout en le rendant plus Français.
J’ai commencé par la barre de navigation. La première difficulté était de reproduire le menu déroulant sous “entreprise”. Pour ce faire, j'ai d’abord donné la classe “w3-dropdown-hover” à une “div” ce qui crée un menu déroulant au survol de la souris. Ensuite, j’ai ajouté le bouton “Entreprise” avant de spécifier le contenu du menu à l’aide de “w3-dropdown-content”.
 On notera que les éléments de cette liste sont des liens qui ne dirigent pour l’instant nulle part. Points à améliorer : le menu ne reste pas affiché quand on clique dessus, les bords ne sont pas arrondis et les éléments ne sont pas surlignés en gris au survol.


La fenêtre “modal”

 Toujours dans le menu, il m’a fallu ajouter une fenêtre “modal” pour permettre à l’utilisateur de choisir sa langue. Cela a nécessité d’écrire un peu de Java Script. La fonction “modal” sélectionne l’élement “id01” quand l’utilisateur clique sur le bouton et ferme la fenêtre quand il clique ailleurs. 
J’ai fait le choix d’insérer une croix pour permettre de fermer la page avec “&times” plutôt que de me contenter d’un simple ”X”
Points à améliorer : les deux langues doivent être des liens et s’afficher côte à côte. 















La présentation en “slides”
Pour présenter plusieurs options sur un espace réduit, j’ai opté pour une présentation en slides. À nouveau, il me fallait un script. Avec le slideIndex égal à 1, showDivs() affiche le premier élément. PlusDiv() est trompeur, car il ajoute ou soustrait pour changer de slide La fonction showDiv() permet ensuite de cacher (display=none) ou d’afficher (display=block) les slides non utilisées. Si SlideIndex est supérieur au nombre d'éléments(x.length) alors, il est égal à 0.S’il est inférieur à 1 il est égal au nombre d’éléments.

A partir de là il ne restait qu’à créer deux div avec la bonne classe.

Et voilà!














Le menu en “accordéon”
Encore une excellente opportunité de franciser ce site web. J’ai commencé par ajouter une nouvelle fonction au script qui permet de jouer à cache-cache avec les éléments concernés.
Même si la fonction reste la même, il fallait bien entendu vérifier que chaque question ait un Id différent ainsi que la classe “hide”.

Le résultat est assez probant.
https://docs.google.com/document/d/e/2PACX-1vToDWO1mnNldmRJSA2wwN5QxQnTNR_9voGqQ09VJjI_JAoIypYadKysV2PVXrgshxPoTGT_WZ4FL9CQ/pub

