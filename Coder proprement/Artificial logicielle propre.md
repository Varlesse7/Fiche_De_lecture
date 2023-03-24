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

Pour qu'un système logiciem