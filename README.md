## Semaine 1:

  Elaboration du code permettant de donner les caractéristiques(age, allèle1, allèle2) d'un nombre donné d'individu. On a pris comme modèle de base (pour l'insant) le groupe sanguin avec les allèles A,B,O. Le programme consiste à attribuer deux de ces allèles aléatoirement à un individu et lui donner un age aléatoire entre 0 et 10 ans par exemple.
    On a programmé le code permettant de donner quel gene s'exprime en fonction des deux allèles d'un individu. Dans notre cas l'allèle O est récéssif et ne s'exprime donc pas. 
    
## Semaine 2:
  On a programmé une fonction qui donne une nouvelle liste de la population pour l'année suivante en fonction des probabilités de survie liées à l'age de l'individu et à son code génétique. Les inidivdus n'ayant pas survécu ne sont pas présent dans cette nouvelle liste. Nous avons donc estimé les probabilités de survie d'un individu en fonction de son age (plus il est vieux plus il a de chance de mourrir cette année) et de ses allèles. Puis nous avons determiné aléatoirement sa survie. En fonction de ces probabilités les individus survivront ou non. Ce progamme a encore des lacunes. Pour les prochaines séances nous voulons utiliser des modèles mathématiques afin d'obtenir la probabilité de survie en fonction de l'age plutôt que les determiner manuellement. 
  Nous avons ensuite codé une fonction donnant les caractéristiques(age,allèle1,allèle2) d'un individu issu de la reporduction de deux individus. Ces derniers transmettent l'un de leur deux gènes aléatoirement et le code génétique de l'enfant est donc la combinaison des allèles parents.
  A partir des fonctions précédentes et de nos paramètres nous avons élaboré un code donnant la nouvelle population l'année suivante avec son code génétique, elle est constitué des individus ayant survécu et des nouveaux nés. 
  Enfin nous avons coder une fonction permettant d'appliquer le code précédent sur un nombre défini d'années. On constate déjà que sur 20 ans soit la population s'éteind soit elle augmente énormement. Dans ce cas on remarque que les gènes des individus sont principalement ceux qui donne la meilleure chance de survie.
    
   
