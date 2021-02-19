



#  JEU : (Français)


## Description du jeu (exigences fonctionnelles): 

Le jeu est un MMORPG à l'instar de travian. 
Il est constitué de joueurs possédant des villes.
Chacune de ces villes est nécessairement reliée à un héros.
 
Chaque ville permet de récolter des ressources, servant à la construction de bâtiments, ou à l'entraînement d'unité. 

Le joueur choisit un héros pour chacune de ses villes.

Les joueurs peuvent se regrouper au sein d'allianee.

Le héros pourra entraîner des unités à l'aide de la caserne.

## Caractéristiques structurelles  (exigences structurelles):


Il existe 4 routes : 

          <a routerLink="/city_overview" routerLinkActive="active">Tab 1 : City</a>
          <a routerLink="/superheroes" routerLinkActive="active">Tab 2 : Troops </a>
          <a routerLink="/admin" routerLinkActive="active">Admin</a>
          <a routerLink="/login" routerLinkActive="active">Login</a>

#### city_overview sert à l'aperçu des villes. 

Dans cet aperçu, il est possible de gérer le nom des villes. 
Il faudrait implémenter une solution de gestion de chacune des villes. 
Avec la mise en place : 
aperçu des bâtiments de la ville; 
Caractéristiques propres à la ville (ressources disponibles, population etc.);
possibilité de faire des actions (augmenter un bâtiment disponible, accéder à un bâtiment etc.);


#### superheroes donne accès à l'aperçu des héroes. 

#### Admin sert à accéder au détail de son compte. 

#### login/logoff permet de se connecter ou se déconnecter.



####(popup:compose) : permet d'afficher une boite de dialogue.

L'objectif étant d'avoir une messagerie qui permettra de communiquer avec les membres de l'alliance en live. 

Pour afficher cette messagerie, il suffit de ciquer sur "messagerie", le bouton contact, à ce moment dans l'url sera ajouté (popup:compose) 
et pour la retirer il suffit de supprimer dans l'url (popup:compose), il faudrait mettre un bouton "fermer messagerie" qui aurait pour 
utilité de supprimer de l'url (popup:compose).




#  GAME : (Anglais)

## Game's description (functional requirements)

The game is an MMORPG like travian. It is made up of players owning cities. Each of these cities is necessarily connected to a hero.

Each city allows you to collect resources, used for the construction of buildings, or for unit training.

The player chooses a hero for each of his cities.

The hero will be able to train units using the barracks.


## Structural characteristics (structural requirements)

(popup:compose): allows to display a dialog box.

The objective is to have a messaging system that will allow live communication with the members of the alliance. 

To display this messaging, just click on "messaging", the contact button, at this time in the url will be added (popup:compose) 
and to remove it you just have to delete it in the url (popup:compose), it would be necessary to put a button "close mail" which would have
for utility to delete url (popup:compose).



## Bibliography : 

Translated with www.DeepL.com/Translator (free version)




[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/jacques)
