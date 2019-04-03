## Semaine 1:

  Elaboration du code permettant de donner les caractéristiques(age, allèle1, allèle2) d'un nombre donné d'individu. On a pris comme modèle de base (pour l'insant) le groupe sanguin avec les allèles A,B,O. Le programme consiste à attribuer deux de ces allèles aléatoirement à un individu et lui donner un age aléatoire entre 0 et 10 ans par exemple.
    On a programmé le code permettant de donner quel gene s'exprime en fonction des deux allèles d'un individu. Dans notre cas l'allèle O est récéssif et ne s'exprime donc pas. 
    
## Semaine 2:
  On a programmé une fonction qui donne une nouvelle liste de la population pour l'année suivante en fonction des probabilités de survie liées à l'age de l'individu et à son code génétique. Les inidivdus n'ayant pas survécu ne sont pas présent dans cette nouvelle liste. Nous avons donc estimé les probabilités de survie d'un individu en fonction de son age (plus il est vieux plus il a de chance de mourrir cette année) et de ses allèles. Puis nous avons determiné aléatoirement sa survie. En fonction de ces probabilités les individus survivront ou non. Ce progamme a encore des lacunes. Pour les prochaines séances nous voulons utiliser des modèles mathématiques afin d'obtenir la probabilité de survie en fonction de l'age plutôt que les determiner manuellement. 
  Nous avons ensuite codé une fonction donnant les caractéristiques(age,allèle1,allèle2) d'un individu issu de la reporduction de deux individus. Ces derniers transmettent l'un de leur deux gènes aléatoirement et le code génétique de l'enfant est donc la combinaison des allèles parents.
  A partir des fonctions précédentes et de nos paramètres nous avons élaboré un code donnant la nouvelle population l'année suivante avec son code génétique, elle est constitué des individus ayant survécu et des nouveaux nés. 
  Enfin nous avons coder une fonction permettant d'appliquer le code précédent sur un nombre défini d'années. On constate déjà que sur 20 ans soit la population s'éteind soit elle augmente énormement. Dans ce cas on remarque que les gènes des individus sont principalement ceux qui donne la meilleure chance de survie.
    
## Semaine 3:
  On a modifié nos codes d'attribution d'allèle et d'expression de l'allèle selon la dominance pour qu'ils fonctionnent avec un nombre indéfini de gène afin de se rapprocher de la réalité.
  On a codé une fonction qui change la probabilité de survie en fonction des gènes afin de simuler un changement dans l'environnement,selon l'ampleur de la modification les probabilités de survies seront plus ou moins altérées.
  On a codé une fonction permettant de simuler une mutation dans le code génétique d'un individu et que cette mutation se transmettent ou non selon les probabilités de survies qui lui sont attribuées.
  On a ajouté deux graphiques permettant de visualer les probabilités de survies selon les allèles et le nombre d'individu avec un certain code génétique par année.
  
  ## Semaine 4:
      Nous avons corrigés quelques problemes dans le code puis nous avons codé une fonction qui retourne un dictionnaire avec comme clé un gène et comme valeur une liste du nombre de porteur de ce gène chaque année. Nous avons ensuite utilisé cette fonction pour faire un graphique rerésentant l'évolution du nombre de personne portant chaque gène en fonction du temps. Nous avons pu tirer nos premières conclusions.

## Semaine 5:
  Nous avons modifié une erreur dans le code (fonction change_allele). 
  Nous avons ajouté une siganture avec description à chacune des fonctions. Et nous avons essayé de modéliser nos fonctions mais cela n'a pas encore abouti au résultat attendu. 
