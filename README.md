# "Kemar"

> HTML exercise given at HEPL

* * *

**"Kemar"** is an educational project, which will be used for `HTML`/`CSS` courses.

**Note:** the school where the course is given, the [HEPL](http://www.provincedeliege.be/hauteecole) from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in french. Sorry.

* * *

> Lors de vos cours de *web*, vous allez découvrir les langages HTML et CSS et les mettre en pratique pour apprendre à créer des pages web.  

* * *

## Kemar

Cette page présente le top 5 musical de Kemar.  

Votre mission est :

1. de créer le fichier **index.html** qui permet d’afficher ce contenu dans un navigateur web&nbsp;;
2. de valider votre code HTML dans un validateur&nbsp;; 
3. de lier la feuille de style qui donnera à cette page le rendu suivant&nbsp;:

![rendu final](./rendu.png)

### 1. Création du fichier HTML

Pour vous aider, voici les étapes que vous pouvez suivre&nbsp;:

1. avant tout, et avant de commencer à taper du code dans un fichier, prenez le temps d’analyser le contenu fourni pour identifier les balises à utiliser. Si vous hésitez, vous pouvez également consulter l’aide fournie dans la section **«&nbsp;Aides&nbsp;»** ci-dessous&nbsp;;

2. créer le fichier HTML et y placer les balises de départ qui fournissent un template de base complet, ce qui implique notamment de bien indiquer que le document est en français, et aussi&nbsp;:
    - au niveau de l'en-tête du document, de bien définir les méta-informations grâce aux balises `meta`, `title`et `link` appropriées (si vous avez besoin d’aide, voir la section **«&nbsp;Ressources&nbsp;»** ci-dessous) pour&nbsp;: 
        * déclarer correctement l’encodage des caractères utilisé (pour ne pas avoir de problème d’affichage des caractères spéciaux et accentués dans le navigateur)&nbsp;;
        * renseigner que vous êtes l’auteur du document&nbsp;;
        * prévoir que, si on recherche votre page sur un moteur de recherche comme Google, les mots-clés suivants soient associés&nbsp;: Kemar, top 5 musical, top 5 musical de Kemar&nbsp;;
        * prévoir que, si on recherche votre page sur un moteur de recherche comme Google, le moteur de recherche affiche la description suivante pour votre page dans la page qui présente les résultats de recherche&nbsp;: «&nbsp;Découvrez le top 5 musical de Kemar&nbsp;»&nbsp;;
        * faire en sorte que le titre du document qui s’affiche dans l’onglet du navigateur soit «&nbsp;Kemar&nbsp;»&nbsp;;
        * lier la feuille de style à votre page HTML&nbsp;;
    - au niveau du corps du document, de baliser, en utilisant les balises et les attributs HTML corrects&nbsp; (voir la section **«&nbsp;Aides&nbsp;»** ci-dessous)&nbsp;:
         * l’image (afficher l’image représentée dans le fichier `kemar.jpg` avec, comme texte alternatif au cas où elle ne s’affiche pas, «&nbsp;Kemar en chemise bleue qui fait des oreilles de lapin avec ses mains&nbsp;»)&nbsp;;
         * le titre principal&nbsp;;
         * la liste&nbsp;;
    - ouvrir le fichier dans le navigateur Firefox, observer le résultat&nbsp;;
    - avec l’aide de votre professeur de labo, ajouter dans le code HTML ce qu’il faut pour que la feuille de style CSS s’applique complètement à la page et donne le rendu final souhaité.

### 2. Validation du code HTML

1. lancer un validateur&nbsp;:
    - soit **Total Validator** (de préférence) *offline*&nbsp;;
    - soit le [validateur HTML5 du W3C](https://validator.w3.org/#validate_by_upload) *online*&nbsp;;
2. interpréter les erreurs éventuelles fournies par le validateur&nbsp;;
3. corriger&nbsp;;
4. valider à nouveau jusqu'à ce qu’il n’y ait plus d'erreur.  

### 3. Aides

#### 3. 1. Liste des balises

Étant donné que vous n’avez peut-être pas encore vu en cours théorique toutes les balises requises, voici la liste des balises HTML dont vous aurez besoin pour réaliser cet exercice : `html` (avec l’attribut `lang`), `head`, `meta` (avec les attributs `charset`, `name`, `content`), `title`, `link` (avec les attributs `rel` et `href`), `body`, `h1`, `img` (avec les attributs `src`, `alt`, `width`, `height`), `ol`, `li`. Consultez la [Référence des éléments HTML](https://developer.mozilla.org/fr/docs/Web/HTML/Element) (voir la section **«&nbsp;Ressources&nbsp;»** ci-dessous) ainsi que votre «&nbsp;HTML 5 Pocket Reference&nbsp;» pour vous aider à décider quelle balise et quels attributs utiliser pour quel usage et vérifiez à la fin de l’exercice que vous avez bien utilisé toutes les balises de cette liste.

#### 3. 2. Rappel concernant les commentaires en HTML

- les commentaires en HTML s’indiquent entre les symboles `<!--` (marqueur de début de commentaire) et `-->` (marqueur de fin de commentaire). Tout ce qui se trouve entre ces deux marqueurs est ignoré par le navigateur, ce sont des textes qui ne sont ni affichés dans la page, ni interprétés par le navigateur. Ils sont réservés à l’usage exclusif du développeur. Vous pouvez y indiquer tout ce qui vous aide à comprendre, à organiser ou à relire votre code. Voici un exemple :

```html
    <!-- balise meta pour l’encodage des caractères --> 
    <meta charset="utf-8"> <!--  déclare au navigateur que l’encodage des caractères du document courant
                                 est réalisé en UTF-8 --> 
```

#### 3. 3. Astuce pour démarrer beaucoup plus vite

Si vous utilisez Sublime Text et que l’extension *Emmet* est installée, il existe un raccourci clavier qui vous permet d’obtenir beaucoup plus rapidement un *template* de base qu’il vous suffira de compléter / modifier en fonction de vos besoins.

Presser simplement les touches `!` et `TAB` de votre clavier. Cela vous donnera déjà le résultat suivant&nbsp;: 

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        […]
        <title>Document</title>
    </head>
    <body>
        
    </body>
</html>
```

Il vous suffit de changer la langue du document (de `en` en `fr`) et de compléter.


### Ressources

> Ces ressources sont à consulter impérativement, elles font partie de la matière de cours

- [Référence des éléments HTML](https://developer.mozilla.org/fr/docs/Web/HTML/Element) : Une documentation qui reprend la liste des balises et leur sens, facile, en français issue du *MDN Web Docs* de Mozilla, une excellente référence&nbsp;;
- [HTML Living Standard](https://html.spec.whatwg.org/#toc-semantics) : **LA** spécification officielle du w3c/whatwg pour le langage HTML, c’est elle qui détient la vérité et qui fait loi en cas de doute. Il s’agit d’une documentation plus technique, en anglais, très complète, qui comporte une page par balise où on trouve toutes les informations nécessaires (sens, règles de grammaire, attributs, …). Votre «&nbsp;*Précis et Concis*&nbsp;» est une version imprimée de ce site&nbsp;; 
- [Comment indiquer la langue d’un contenu en HTML&nbsp;?](https://www.alsacreations.com/astuce/lire/1151-langue-du-contenu.html) : Aidez-vous de cette ressource pour savoir où et comment utiliser l’attribut lang dans les différents cas de figure&nbsp;;
- [ISO 639-1 Language Codes](https://www.w3schools.com/tags/ref_language_codes.asp) : Aidez-vous de cette ressource pour trouver quel est le code de langue à utiliser pour remplir correctement la valeur de l'attribut lang&nbsp;;
- [À quoi servent les balises META ?](https://www.alsacreations.com/article/lire/628-balises-meta.html) : Aidez-vous de cette ressource pour correctement baliser les méta-informations à indiquer dans l’en-tête de votre document.
