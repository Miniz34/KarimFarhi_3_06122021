# P3

Lien du projet : https://miniz34.github.io/OhMyFoodP3/

## Description :

> Implémentez la version mobile d'un site de foodtech avec des animations CSS.
>
> #### Compétences évaluées
>
> -   Mettre en œuvre des effets CSS graphiques avancés
> -   Assurer la cohérence graphique d'un site web
> -   Mettre en place une structure de navigation pour un site web

### Situation (fictive) du projet :

Développeur web junior chez une jeune startup qui souhaite se faire une place sur le marché de la restauration

L’objectif du projet est de réaliser un site 100% mobile répertoriant les menus de restaurants gastronomiques, il sera possible à terme de réserver une table ainsi que les plats à l’avance pour qu’ils soient déjà prêts à l’arrivé du client au restaurant

Mon rôle a été de réaliser le site en intégrant les maquettes mobiles en HTML et CSS et de rendre le site dynamique avec diverses animations en CSS


### Cahier des charges :
#### Contraintes techniques :

- Respecter les maquettes mobiles et réaliser le site en utilisant une approche Mobile first
- Adapter le site pour les tablettes et le desktop
- Couleur de la charte graphique :
  - Violet : ![#9356dc](https://via.placeholder.com/15/9356dc/000000?text=+) `#9356dc`
  - Rose : ![#ff79da](https://via.placeholder.com/15/ff79da/000000?text=+) `#ff79da`
  - Turquoise : ![#99e2d0](https://via.placeholder.com/15/99e2d0/000000?text=+) `#99e2d0`
- Police : _[Shrikhand](https://fonts.google.com/specimen/Shrikhand)_ pour le logo et les titres et _[Roboto](https://fonts.google.com/specimen/Roboto)_ pour le texte
- **Pas de framework ou de JavaScript** : uniquement du HTML et CSS (SASS serait un plus) et le HTML ne doit contenir aucun attribut style
- Le code ne doit contenir aucune erreur ni alerte au validateur W3C [HTML Accueil](https://validator.w3.org/nu/?doc=https%3A%2F%2Fminiz34.github.io%2FOhMyFoodP3%2F), [HTML Page Menu](https://validator.w3.org/nu/?doc=https%3A%2F%2Fminiz34.github.io%2FOhMyFoodP3%2Fdelice_sens.html) et [CSS](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fminiz34.github.io%2FOhMyFoodP3%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=fr)
- Le site doit être compatible avec les dernières versions de Chrome, Firefox et Safari

#### Fonctionnalités, effets graphiques et animations :

- **Header :** Un bouton de retour à l’accueil qui ne doit apparaître que sur les pages de menu
- **Boutons :** Au survol, la couleur de fond doit s’éclaircir et l’ombre portée doit être plus visible
- **Bouton “J’aime” :** En forme de coeur, il doit se remplir progressivement au survol
- **Footer :** Au clic sur “Contact” un renvoi vers une adresse mail est effectué
- **Page d’accueil :** Un “loading spinner” couvrant tout l’écran doit apparaître sur la page d’accueil pendant 1 à 3 secondes (uniquement en CSS)
- **Page de menu :** Les plats doivent apparaître progressivement avec un décalage
Une “coche” doit coulisser au survol des plats. Si l’intitulé du plat est trop long, il doit être rogné avec des points de suspension
