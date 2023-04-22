## Code orienté object : 
facilite l'ajout de nouvelle classe sans modifier les fonctions existantes.
Mais il complexifie l'ajout de nouvelle fonction car les classes doivent être modifiées 

## Loi démeter : 
Une méthode f d'une classe C ne doit pas appelé les méthodes des éléments suivant : 
- C
- Un objet crée par f
- un objet passé en argument 
- un objet contenue dans une variable d'instance de C

## Exeption : 
Ne pas renvoyer de null essayer de remplacer par des listes 

## Limite :

| Utilisateur   | Dev                          |
| ------------- | ---------------------------- |
| Besoin précis | Doit faire un code pour tous |

Lorsqu'on emploie un paquetage tierce il faut définir définir ce que nous voulons nous servir et ce que nous ne voulons pas nous servir et ne pas hésité à redéfinir des fonctions.  

### Test d'apprentissage :
Faire des tests unitaires sur le code tiers apporté pour vérifier que l'on le comprenne bien. **Ne pas hésiter à** ***trop*** **en faire.** De plus elle permette de bien vérifier que suite à un changement de version on pourra voir si le code tiers est toujours en adéquation avec notre code. 

## Test unitaire : 

### Les règles du TDD (test Driven Developpement):
1) **Première loi** : Vous ne devez pas écrire un code de production tant que vous n'avez pas écrit un test unitaire d'échec
2) **2ème loi** : Vous devez uniquement écrire le test unitaire suffisant pour échouer; l'impossibilité de compiler est un échec
3) **3ème loi** : Vous devez uniquement écrire du code de production suffisant pour réussir le test d'échec courant.


Le code de test est aussi important que le code de production
Un bon code de test permet une modification du code moins problématique

### Test propre : 
il faut une bonne lisibilité  
assetion unique (bonne idée mais si pas possible faire sans) donc il faut minimiser les assertions et traiter un maximum de chose avec nos assertion