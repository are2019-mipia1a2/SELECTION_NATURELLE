## Semaine 1:

  Elaboration du code permettant de donner les caractéristiques(age, allèle1, allèle2) d'un nombre donné d'individu. On a prit comme modèle de base (pour l'insant) le groupe sanguin avec les allèles A,B,O. Le programme consiste à attribuer deux de ses allèles aléatoirement à un individu et lui donner un age aléatoire entre 0 et 10 ans par exemple.
    On a programmé le code permettant de donner quel gene s'exprime en fonction des deux allèles d'un individu. Dans notre cas l'allèle O est récéssif et ne s'exprime donc pas. 
    
## Semaine 2:
  On a programmé une fonction qui donne une nouvelle liste de la population pour l'année suivante en fonction des probabilités de survie liées à l'age de l'individu et à son code génétique. Les inidivdus n'ayant pas survécu ne sont pas présent dans cette nouvelle liste. Nous avons donc estimé les probabilités de survie d'un individu en fonction de son age (plus il est vieux plus il a de chance de mourrir cette année) et de ses allèles. Puis nous avons determiné aléatoirement sa survie. En fonction de ces probabilités les individus survivront ou non. Ce progamme a encore des lacunes. Pour les prochaines séances nous voulons utiliser des modèles mathétiques afin d'obtenir la probabilité de survie en fonction de l'age plutôt que les determiner manuellement. 
  Nous avons ensuite codé une fonction donnant les caractéristiques(age,allèle1,allèle2) d'un individu issu de la reporduction de deux individus. Ces derniers transmettent l'un de leur deux gènes aléatoirement et le code génétique de l'enfant est donc la combinaison des allèles parents.
  A partir des fonctions précédentes et de nos paramètres nous avons élaboré un code donnant la nouvelle population l'année suivante avec son code génétique, elle est constitué des individus ayant survécu et des nouveaux nés. 
  Enfin nous avons coder une fonction permettant d'appliquer le code précédent sur un nombre défini d'années. On constate déjà que sur 20 ans soit la population s'éteind soit elle augmente énormement. Dans ce cas on remarque que les gènes des individus sont principalement ceux qui donne la meilleure chance de survie.
    
    






## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/are2019-mipia1a2/SELECTION_NATURELLE/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/are2019-mipia1a2/SELECTION_NATURELLE/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
