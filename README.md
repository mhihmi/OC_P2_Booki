# OC_P2_Booki : Transformez une maquette en site web avec HTML & CSS

[![HitCount](https://hits.dwyl.com/mhihmi/OC_P2_Booki.svg?style=flat&show=unique)](# "Unique view count")
[![HitCount](https://hits.dwyl.com/mhihmi/OC_P2_Booki.svg?style=flat)](# "All view count")
> Intégration de Maquette - Parcours Openclassrooms Développeur Web

Vous avez trouvé votre premier stage en tant que développeur web chez Booki, une petite entreprise proposant un outil de planification de vacances ! Son site permet aux usagers de trouver des hébergements et des activités dans la ville de leur choix. Les hébergements peuvent également être filtrés par thématique, par exemple leur budget ou leur ambiance.

Un nouveau design basé sur les principes du Material Design vient d’être réalisé par Loïc, designer UI.

![Maquette Desktop](https://github.com/mhihmi/OC_P2_Booki/blob/master/images/Desktop_maquette.png)

Avant de valider définitivement le design, l’entreprise a décidé de réaliser un prototype. Vous êtes chargé de créer ce prototype en intégrant la maquette en HTML et CSS.

Voici l’ensemble des points techniques et fonctionnels à prendre en compte pour le développement du nouveau site Booki. L’ensemble de ces éléments ont été validés par l’équipe Produit, il est donc important de les respecter.

## Spécifications fonctionnelles

Les usagers pourront rechercher des hébergements dans la ville de
leur choix. Le champ de recherche est un champ de saisie, le texte
doit donc pouvoir être édité par l’utilisateur. Il faut englober ce
champ dans un formulaire pour que ce dernier soit valide auprès du
W3C. La partie recherche ne doit pas être fonctionnelle.
* Chaque carte d’hébergement ou d’activité devra être cliquable dans
son intégralité (pas uniquement le titre). Pour l’instant, les liens sont
vides. On peut utiliser un attribut href=”#” pour simuler la
présence d’un lien.
* Les filtres doivent changer d’apparence au survol. Je te laisse décider
de l’effet approprié, je n’ai pas encore eu le temps de me pencher
dessus. Par contre, ils ne doivent pas être fonctionnels.
* Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont
des liens. Ils doivent mener respectivement vers la section
“Hébergements à Marseille” et “Activités à Marseille”.

## Spécifications techniques

* Deux maquettes ont été réalisées : l’une desktop et l’autre mobile. Le site devra être également adapté aux formats tablette. Pour les tablettes, nous sommes libres de faire les adaptations nécessaires. Il est important qu’aucun élément ne soit coupé, et que le texte ait une taille suffisante.
* Concernant les breakpoints, nous avons convenu avec le client
d’utiliser 992 px et 768 px.
992 px pour les écrans d’ordinateurs et 768 px pour les tablettes, et
tout ce qui est en dessous de 768 pour les téléphones portables.
* Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement
dit, en desktop first), puis les tablettes et enfin les téléphones.
L’utilisation des Media Queries nous permettra de réaliser
l’intégration pour les différents supports.
* Plusieurs formats et tailles d’images ont été exportés. Il faudra choisir
le format le plus adapté par rapport à la résolution et au temps de
chargement.
* Les icônes proviennent de la bibliothèque Font Awesome. Nous
pouvons passer par un CDN pour faciliter le chargement des icônes.
* Les couleurs de la charte sont le bleu (#0065FC), une version plus
claire de ce bleu (#DEEBFF) et le gris pour le fond (#F2F2F2).
* La police du site est Raleway. Nous pouvons passer par Google Font
pour importer facilement cette police dans le code :
[GoogleFont Raleway](https://fonts.google.com/specimen/Raleway).
* Il est important d’utiliser les pixels et les pourcentages plutôt que les
REM et les EM. Le client préfère cette solution pour des contraintes
techniques.
* Il est important d’utiliser Flexbox plutôt que Grid. Notre client est
plus à l’aise avec cette solution.
* Aucun framework CSS (type BootStrap ou Tailwind CSS) ou
préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
* Il est important d’utiliser des balises sémantiques (type main,
header, nav, etc.).
* Le code doit être valide aux validateurs W3C HTML et CSS.
* La maquette doit être compatible avec les dernières versions de
Google Chrome et de Mozilla Firefox. Il faudra tester le prototype sur
ces deux navigateurs.
* Le code ne doit pas être versionné avec Git.