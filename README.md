



#  JEU : (Français)


## Synopsis

Après la chute de l'empire romain, l'Europe manque de stabilité.

Au fur et à mesure les féodalités apparaissent, il s'agit d'un système central dans lequel l'autorité centrale s'associe avec 
les seigneurs locaux et ceux-ci avec leur population. 

Dans ce contexte, reprenez le contrôle de votre terre en proie aux attaques des ennemis. 

Rejoignez une alliance, développez votre cité, et combattez ceux qui s'opposent à vous. 

Dans medieval war : une nation parmi  et une féodalité parmis cette nation. 

Chaque féodalité est constitué de village et/ou villes permettant d'aggrandir votre territoire. 

Pour chaque village, et pour chaque ville, on lui associe un héros. 

Ce héros aura pour objectif de mener à développer votre cité. 

Par avance, je présente mes excuses aux historiens car il est possible que subsiste des anachronismes (comme le fait que Clovis soit un 
héros sélectionnable et potentiellement puisse s'allier ou combattre d'autres héros n'ayant pas vécu à la même époque, néanmoins dans des 
soucis d'équilibrage les armées de clovis bien que potentiellement plus faible que des armées où la technologie était plus avancée comme 
avec les arbalétriers seront également plus forte en terme de cohésion par exemple, ce qui pourra entraîner une victoire d'une unité 
militaire issue de l'armée de CLovis contre un arbalétrier par exemple).




## Description du jeu (exigences fonctionnelles): 

Le jeu est un MMORPG à l'instar de travian.

Il se déroule à l'époque médiévale. 

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


# Caractéristiques : 


### Caractéristiques des bâtiments 

|   Emoji   |   Nom |   level max |   fonction |   Prix (Ressource : 1;2;3;4)   |
|---    |:-:    |:-:    |:-:    |--:    |
|   &#x1F600;   |   Bâtiment principal        |   10 |   Permet d'accélerer la construction des autres bâtiments et également passer de village à ville au niveau 10 (et débloquer ainsi de nouveaux bâtiments)  |   10;10;15;5  |
|   &#x1F600;   |   Bâtiment de ressource 1   |   10 |   Permet la production de ressource de type 1  |   10;10;15;5  |
|   &#x1F600;   |   Bâtiment de ressource 2   |   10 |   Permet la production de ressource de type 2  |   10;10;15;5  |
|   &#x1F600;   |   Bâtiment de ressource 3   |   10 |   Permet la production de ressource de type 3  |   10;10;15;5  |
|   &#x1F600;   |   Bâtiment de ressource 4   |   10 |   Permet la production de ressource de type 4   |
|   &#x1F923;   |   Bâtiment de stockage de ressource  |   10 |   Permet le stockage des ressource de tous types  |   10;10;15;5  |
|   &#x1F923;   |   Bâtiment de recrutement d'unités basiques   | 10 |  Offre la possibilité de recruter des unités basiques (unités militaires, former des villageois etc ...) |   10;10;15;5  |
|   &#x1F923;   |   Bâtiment de recrutement d'unités spécifiques   |   10 | Octroie le recrutement d'unités plus spécifiques (missionnaires, unités militaires avancées, scribes etc ...)|   10;10;15;5  |
|   &#x1F923;   |   Bâtiment d'amélioration : Académie.   |  10| Recherches à débloquer afin d'améliorer des capacités ou des compétences de vos unités et/ou bâtiment |   10;10;15;5  |
|   &#x1F923;   |   Bâtiment défensif 1 (Mur)      |   10 | Le mur sert à se défendre contre l'opposant et octroie un bonus défensif |   10;10;15;5  |
|   &#x1F923;   |   Bâtiment défensif 2 (Douve)      | 10 | Les douves servent à se défendre contre l'opposant et octroie un bonus défensif |   10;10;15;5  |
|   &#x1F923;   |   Bâtiment habitation : Maison   |  10 | Permet de loger la population disponible |   10;10;15;5  |


#  GAME : (Anglais)

## Game's description (functional requirements)

The game is an MMORPG like travian. 

It takes place in medieval times.

It is made up of players owning cities. Each of these cities is necessarily connected to a hero.

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

https://fr.wikipedia.org/wiki/Moyen_%C3%82ge

https://fr.wikipedia.org/wiki/Chronologie_du_Moyen_%C3%82ge

https://www.caminteresse.fr/histoire/les-chevaliers-super-heros-du-moyen-age-11122556/

https://fr.wikipedia.org/wiki/M%C3%A9rovingiens

https://www.histoire-pour-tous.fr/chronologies/3302-chronologie-des-rois-de-france.html

https://pixabay.com/fr/images/search/cath%C3%A9drales/

https://pixabay.com/fr/images/search/rois%20de%20france/

https://pixabay.com/fr/images/search/eveques/




Translated with www.DeepL.com/Translator (free version)



[See project here :] (https://jacques.stackblitz.io/)
