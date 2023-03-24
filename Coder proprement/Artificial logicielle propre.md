## Echel d'urgence / importance : 
| Fonctionnel | Architecture  |
| ----------- | ------------- |
| Urgent      | Important     |
| Non Urgent  | Important     |
| Urgent      | Non Important |
| Non Urgent  | Non Important |

## Programmation Structurée : 
- La programmation structurée impose une discipline aux tranfert direct du controle d'éxecution 

- on passe de saut de prog -> conditionel. 

## Programmation Orienté Object : 
- pile d'appel de fonction peuvent être requisitionner dans la zone mémoire tas (permet d'avoir des variables d'instance ou attribut)

- le prog orienté objet  impose une discipline au transfert indirects du contrôled'éxecution 

## Programmation Fonctionelle :
- on empêche la modif des affectations de variable
- La programmation fonctionelle impose une discipline aux affectation des valeurs. (permet d'avoir un prog constant dans le temps ) 
- Les variables sont immuable.

## SOLID :
principe pour la structure : 
- tolérence au changemenet 
- facilité de compréhension 
- un jeu de composants fondamentaux pouvant être utiliser dans de nombreux 

Initial de : 
- SRP : Single Reponsibility Principle 
- OCP : Open Close Principle 
- LSP : Liskov Substitution Principle 
- ISP : Interface Segregation Principle 
- DIP : Dependance inversion Principle 

### SRP :
loi de conway : chaque module ne doit accepter qu'une seule raison d'évoluer. 

chaque module ne doit être responsable que d'un lecteur. 

### OCP : 
Bertrand Meyer (1980)

Pour qu'un code soit facile à évoluer il doit être conçu pour évoluer par ajout du code et non en modifiant le code existant. 

### LSP : 
Liskov (1988)

Pour qu'un système logiciel puisse être construit à partir de parties interchangeables, ces parties doivent se conformer à un contrat permettant aux parties d'être substitué l'une à l'autre.

### ISP : 
les concepteurs logiciel doivent éviter à tout prix de créer des dépendances par rapport à des éléments dont ils n'ont pas l'usage.

### DIP : 
Le code qui incarne les règles de haut niveau ne doivent pas dépandre du code qui implémente les règles de bas niveau 

## Cohésion des composents : 

### REP (Release Equivalence Principle) :
	- principe d'équivalence entre réutilisation et déploiments 
	- doit avoir l'information de version et aussi une cohérence dans les versions des librairies utilisé

## CCP (Common Closure Principle) :
	- on regroupe les classes évoluant pareil dans un même composant. Et on regroupe les classes évoluant différent dans deds composants différents. 
	- liaison avec le principe SRP

## CRP (Common Reuse Principle) :
	-il faut obliger les utilisateurs d'un composant à dépendre d'élément dont ils n'ont pas besoin

## Nature des composants : 
De base on stockait les librairie de fonction dans l'espace mémoire (mais débordements mémoire)
On les stockait dans les compilateurs avec lieur et chargeur (mais lieur prennait trop de temps car matériel trop faible).
Grâce à la loi de Moore plus de problèlme de temps de compilation. 
Loi de Murphy en opposition à Moore. 
Permis de créer les fichier possédent plusieurs code par exemple .jar

## Problème de dépendance : 
Code parfait -> lendemain erreur (bogue de lendemain) un autre la changer.

Car plusieur développeur travaille sur le même fichier source. La solution -> **1ere solution** : Weekly build, une version du code est enregistré en chaque fin de semaine car seulement 1 jour en équipe et 4 jour solo / **2eme solution** : Supression des cycles de dépendances : on donne à chaue dev un coposant déployabe, lorsque le composant est bon on le rajoute. il faut bien gérer la structure. 

## Graphe orient acyclique : 
diagrame des composants ou il n'y a pas "d'auto dépendance".

## Loi conway : 
Def : une organisation qui conçoit un système va aboutir à une structure que copie la structure de commencement dans cette organisation. 

## Cas d'usage : 
en effet l'architecture ordinateur doit soutenir les intentions du système.  (comment le système doit être exécuter et ou)
