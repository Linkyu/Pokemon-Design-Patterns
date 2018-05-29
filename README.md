# Pokemon-Design-Patterns
Design Pattern experiments based on a Pokémon TCG example

Open the XML files with http://draw.io

## TP design pattern pokemon

### STRATEGY
_Quels sont les problèmes engendrées par l'implémentation du code de chaque attaque dans la classe?_

Prévenir de la duplication de code dans le cadre d'un polymorphisme et d'une utilisation transverse de cette même methode pour d'autre cartes.

### DECORATOR
_Quels sont les problèmes engendrées par cette solution?_

Dans cette solution 
* Nous devrons créer une classe Energy à chaque combinaison possible
* Duplication de code
* Maintenabilité médiocre

_L'aggrégation entre les classes pokemon et energie a t'elle une incidence?_

Non, il n'y a pas d'incidence directe due a cette aggregation entre la classe abstraite energie qui sera décorée et la classe pokemon.




