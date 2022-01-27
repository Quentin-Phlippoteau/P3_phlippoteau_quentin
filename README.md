## Projet 3 "Dynamisez une page web avec des animations CSS"

### LIEN GITHUB

https://quentin-phlippoteau.github.io/P3_phlippoteau_quentin/

### CONTEXTE

#### Intégrer les maquettes en HTML et CSS :

- Maquettes mobiles fournies (approche mobile-first).
- Adaptation desktop et tablette libre (supports non prioritaires).

#### Contraintes :

- Pas d'utilisation de framework ni de Javascript.
- Aucun code CSS via un attribut style dans une balise HTML.
- Aucune erreur ni alerte au validateur W3C HTML et CSS.
- Site compatible avec les dernières version de Chrome et Firefox.


##### Page d'accueil :

- Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

##### Page menu :

- Quatre pages contenant chacune le menu d'un restaurant.

##### Header :

- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

##### Footer :

- Footer identique sur toutes les pages.
- Au clic sur "Contact", un renvoi vers une adresse mail est effectué.



##### Effets graphiques et animations :

- Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser
- les animations ou transitions CSS, pas de JavaScript ni de librairie.

###### Boutons :

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
- L’ombre portée devra également être plus visible.
-  terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. 
- Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

###### Page d'accueil :

- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire.
- cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
graphique du site.


###### Pages menu :

-  l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
“Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni
-Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survolsur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension. Un exemple de l’effet attendu est fourni.

### TECHNOLOGIES UTILISÉES

- HTML5.
- CSS3.
- Visual Studio Code.
- Flexbox.
- Sass.
- Font Awesome.


