# Yaourts

## Objectif

Vous êtes en charge de la réalisation d'un algorithme d'analyse d'une étude marketing sur l'emballage d'un nouveau yaourt bio issu de circuits courts. 
Vous recevez à ce titre les résultats d'une étude où des consommateurs indiquent la couleur qu'ils préfèrent pour l'emballage. 
Vous décidez de présenter les 2 couleurs les plus demandées à votre client.

## Consignes 
Démarrez à partir du fichier correspondant à votre langage de programmation (yaourts.php pour PHP, yaourts.js pour Javascript ....).
Implémentez le code de la méthode run() présente dans le fichier.
Le nom et paramètres de la classe et de la méthode ne doivent pas être modifiés !
Vous pouvez créer des méthodes privées supplémentaires si nécessaire.

## Données

### Entrée

**colors** : 
Un tableau indexé contenant entre 500 et 5000 entrées. 
Chaque élément du tableau correspond à la couleur choisie par une personne interrogée.
Ces éléments du tableau sont générés aléatoirement à chaque appel de votre algorithme.

*Exemple :*
> [ 'rouge', 'jaune', 'bleu', 'jaune', 'rouge', 'jaune' ]

### Sortie

Une chaine de caractère représentant les deux couleurs préférées. 
Les 2 valeurs sont séparées par un espace. 
La couleur la plus populaire doit apparaître en premier.
On vous garantit qu'il n'y aura jamais 2 couleurs ex-aequo.

*Exemple :*

Pour le tableau en entrée :
> [ 'rouge', 'jaune', 'bleu', 'jaune', 'rouge', 'jaune' ]

La réponse est :
> jaune rouge

Car le jaune a obtenu 3 votes, le rouge 2 votes et le bleu 1 vote.