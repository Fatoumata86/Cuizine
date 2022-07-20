Prêt à lancer **votre propre site web** ? Quelle meilleure idée que de parler de votre passion : la cuisine ? À vous de jouer, avec une page d'accueil, des recettes, des astuces et des informations à propos vous !

---

## 🧠 Comment démarrer

Pour démarrer l'exercice :

-   rendez-vous sur ce [repo GitHub](https://github.com/konexio/digitous-html-cuisine)
-   faites un **fork** du dossier pour le copier sur votre propre compte GitHub
-   faites un clone de la copie pour l'importer sur votre machine (`git clone`)

En fin de journée :

-   exécutez les commandes `git` suivantes :
    -   `git add .`
    -   `git commit -m "VOTRE MESSAGE"`
    -   `git push` vos changements pour les mettre à jour sur [GitHub.com](http://GitHub.com)

---

## Installation

Dans le dossier de travail `/digitous-html-cuisine`, ajoutez :

-   un fichier `index.html`
-   créez deux fichiers : `css/main.css` et `css/homepage.css`
    -   Faites attention à ce que le fichier `main.css` ne contienne que des règles CSS génériques à tout le site et que le `homepage.css` contienne le code CSS spécifique à la page d'index (la première page)
-   Téléchargez la dernière version compilée (_Compiled CSS and JS_) de Bootstrap [ici](https://getbootstrap.com/docs/5.0/getting-started/download/)
    -   copiez le fichier **CSS** de Bootstrap qui se trouve dans le répertoire `css/` du fichier .ZIP Bootstrap que vous venez de télécharger : `css/bootstrap.min.css`. Collez ce fichier dans le dossier `css/` de notre dossier de travail. Liez une balise `<link>` dans la section `<head>` de votre fichier `index.html` vers ce fichier.
    -   Copiez le fichier **JavaScript** (bundle) `bootstrap.bundle.min.js` de **Bootstrap** (qui se trouve dans le répertoire `js` du [même fichier .ZIP que vous avez téléchargé juste avant](https://getbootstrap.com/docs/5.0/getting-started/download/)), collez le dans le répertoire `js/` de votre dossier de travail, et ajoutez le balise HTML `<script>` qui charge ce fichier JavaScript juste avant la balise de fermeture `</body>`.

## Base

-   Les polices d'écritures utilisées sont : `[Oswald](<https://fonts.google.com/specimen/Oswald>)` et `[Courgette](<https://fonts.google.com/specimen/Courgette>)` qui sont disponibles sur [Google Fonts](https://fonts.google.com/)
-   Les couleurs utilisées sont le blanc `#FFFFFF` et le noir `#000000`

## Instructions

-   Reproduire l'image située ici : `templates/homepage/homepage.png`
-   Commencer par la **navigation** (`<nav>`)
-   Ensuite enchaîner par le `<header>`. Ne commencez que lorsque vous avez fini la navigation.
-   Continuer avec le contenu principal
-   Et finir par le `<footer>`
-   Une fois terminé, appliquez les changements pour les images `homepage_md.png` et `homepage_lg.png`

# Blog - Contact - Team

## Installation

-   Créer un fichier `contact.html`
-   Créer un fichier `team.html`
-   Créer un fichier dans le répertoire _css_ : `css/contact.css`
-   Créer un fichier dans le répertoire _css_ : `css/team.css`
-   Aller sur le site [embedgooglemap.net](https://www.embedgooglemap.net/) et générer un code HTML que vous pouvez inclure dans votre page

## Instructions

### Contact

-   Inclure dans la page `contact.html`, les fichiers CSS `main.css` et `contact.css`
    -   Faites attention à ce que le fichier `main.css` ne contienne que des règles génériques à tout le site
-   Inclure la _map_ que vous avez générée
-   Une fois terminé, appliquez les changements pour les images `contact_md.png` et `contact_lg.png`

### Team

-   Inclure dans la page `team.html`, les fichiers CSS `main.css` et `team.css`
    -   Faites attention à ce que le fichier `main.css` ne contienne que des **règles génériques à tout le site**
-   Une fois terminé, appliquez les changements pour les images `team_md.png` et `team_lg.png`

## Bonus

-   Inclure la map avec [Leaflet](https://leafletjs.com/)

# Blog - Team member - Post

## Installation

-   Créer un fichier `team-member.html`
-   Créer un fichier `post.html`
-   Créer un fichier dans le répertoire _css_ : `css/team-member.css`
-   Créer un fichier dans le répertoire _css_ : `css/post.css`

## Instructions

### Team member

-   Inclure dans la page `team-member.html`, les fichiers CSS `main.css` et `team-member.css`
    -   Faites attention à ce que le fichier `main.css` ne contiennent que des règles génériques à tout le site
-   Inclure la _map_ que vous avez générée

### Post

-   Inclure dans la page post.html, les fichiers CSS main.css et post.css
    -   Faites attention à ce que le fichier main.css ne contiennent que des règles génériques à tout le site

## Bonus 1

-   Creer la **page 2** de votre accueil
-   Reproduire la page `templates/recipe/recipe.png`

## Bonus 2

Créer des pages transitions en suivant ce [tutoriel](https://www.youtube.com/watch?v=1dJT-99KpiI)

## La page d'accueil

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/de2e0cf2-f02c-4ff6-ba37-4b5e8c854887/homepage_lg.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/de2e0cf2-f02c-4ff6-ba37-4b5e8c854887/homepage_lg.png)

> Chez Suzette, la nouvelle crêperie qui fait parler d'elle

> La franchise "Chez Suzette" qui fait un carton chez les bretons ouvre son premier restaurant à Paris dans le quartier latin. Antoine de Cui'zine a testé pour vous les saveurs sucrées, salées au froment ou au sarrazin!

> Le Métro dessert

> Germain est ferrovipathe (ndlr: fan de train), son fils Maxime est pâtissier. Ils ont décidé de réunir leur deux passions dans un restaurant à la déco inspiré du métro parisien. A voir absolument, mais qu'en est-il d'y aller pour manger ? Clémentine entre en gare et nous donne son avis

> Vitaly, le végan italien

> Quand on pense italien, on pense lasagne et jambon de Parme. Ils l'ont fait, les saveurs de l'Italie à portée des herbivores. Cette fois, c'est moi Tony qui vais le tester pour vous.

## Vos articles

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/05f3958f-ef68-432b-b8f8-e59f32796972/post_lg.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/05f3958f-ef68-432b-b8f8-e59f32796972/post_lg.png)

> La franchise "Chez Suzette" qui fait un carton chez les bretons ouvre son premier restaurant à Paris dans le quartier latin. Antoine de Cui'zine a testé pour vous les saveurs sucrés, salés au froment ou au sarrazin!

> A propos de l'auteur

> Antoine a découvert la nourriture dès le plus jeune âge, depuis il est fan. Ce qu'il préfére dans la cuisine c'est faire la vaisselle

> J'ai testé moi aussi, et j'ai été agréablement surpris.

> Merci pour votre revue excellente. Toutes les personnes qui viendront et diront qu'elles ont connu le restaurant grâce à cet article auront un dessert gratuit. Excellente journée à vous !

> Ca sent le coup marketing à plein nez !

## Vos recettes

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2bd16924-902c-4b5a-bd24-58beedace03f/recipe_lg.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2bd16924-902c-4b5a-bd24-58beedace03f/recipe_lg.png)

> Verser la moitié de l'huile dans une très large poêle, y faire dorer le poulet, le porc et la saucisse jusqu'à mi-cuisson, puis les retirer.

> Pendant ce temps, faire ouvrir les moules et les coques dans le vin blanc avec 2 cuillères à soupe d'oignons émincés et de persil haché.

> Les mettre de côté et réserver le jus filtré.

> Rajouter les crevettes ou langoustines dans la poêle avec la viande, les faire sauter puis retirer le tout et réserver.

> Remettre un peu d'huile et faire suer l'oignon d'Espagne et 2 gousses d'ail émincées dans la poêle.

> Rajouter les tomates pelées et coupées, les piments émincés et laisser cuire doucement pendant 5 min, en remuant constamment.

> Retirer tout le mélange de la poêle, et rajouter le reste d'huile.

> Faire chauffer l'huile et y verser le riz.

> Remuer à la spatule et laisser le riz devenir transparent et crépiter.

> A ce moment, verser le bouillon très chaud, l'eau des moules et le safran délayé dans un peu d'eau chaude.

> Remettre tous les ingrédients sauf les petits pois.

> Porter à ébullition doucement et laisser mijoter 15 min sans remuer.

> Rajouter les petits pois et le reste de la langouste, puis placer en surface quelques crevettes, moules, coques et morceaux de poulet.

> Couvrir, et prolongez la cuisson de 5 à 10 min, le riz doit avoir absorbé tout le jus tout en gardant une texture ferme

## Votre équipe

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f41a7d96-c784-468e-a8a2-0fe1854b3ed3/team_lg.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f41a7d96-c784-468e-a8a2-0fe1854b3ed3/team_lg.png)

> On apprend en enseignant

> Un pour tous et tous pour un

## Vous

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/be2b1eeb-ef50-44cc-88c2-3c4c847cb07d/team-member_lg.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/be2b1eeb-ef50-44cc-88c2-3c4c847cb07d/team-member_lg.png)

> Antoine, né à London, en Ontario, a été élevé dans une famille mormone. Son père est d'origine canadien-français. Il se destine d'abord à une carrière de danseur avant d'être engagé en 1993, à l'âge de 12 ans, sur The Mickey Mouse Club (All New Mickey Mouse Club) aux côtés de Britney Spears, Christina Aguilera et Justin Timberlake.

> À la suite de ses débuts d'acteur en 1991, Antoine enchaîne quelques apparitions à la télévision dans des séries canadiennes et américaines, puis endosse le rôle d'Hercule dans la série Hercule contre Arès (Young Hercules) de 1998 à 1999.

> En 2001, il apparaît pour la première fois sur grand écran dans le film de Boaz Yakin, produit par Jerry Bruckheimer, Le Plus Beau des combats (Remember the Titans) où il interprète un jeune joueur de football américain dans la première équipe scolaire de Virginie accueillant des noirs, Les Titans. La même année, Antoine obtient le rôle d'un néo-nazi juif dans Danny Balint (The Believer) de Henry Bean, le film remporte le « Grand Prix du Jury » au festival du film de Sundance et le « St. George d'or » au festival international du film de Moscou.

> De 2002 à 2004, il interprète surtout des rôles de jeunes gens tourmentés : un meurtrier perfide et sûr de lui face à Sandra Bullock dans Calculs meurtriers (Murder by Numbers) de Barbet Schroeder puis un adolescent énigmatique et fascinant dans The United States of Leland de Matthew Ryan Hoge, aux côtés de Don Cheadle. Le film sera présenté au Festival de Deauville et au Festival de Sundance en 2003. Il a également participé au film d'Andrew J. Smith, The Slaughter Rule en 2002, où David Morse l'entraîne dans son équipe de six-man football, un dérivé brutal du football américain.

> En 2004, Antoine tourne ensuite sous la direction de Nick Cassavetes dans N'oublie jamais (The Notebook) avec Rachel McAdams, un drame romantique sur l'amour éternel à travers la maladie d'Alzheimer, qui leur vaudra de nombreux prix du public aux Teen Choice Awards, et le MTV Movie Award du meilleur baiser. La même année, le New York Times parle de lui comme l'un des nouveaux talents en vue du cinéma américain.

> Également compositeur, musicien et chanteur, il participe à la composition de la bande originale du film Wild Roomies d'Oliver Robins en 2004.

## Vous contacter

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5c91a33d-3ae1-4e0b-85ec-a00649c00e69/contact_lg.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5c91a33d-3ae1-4e0b-85ec-a00649c00e69/contact_lg.png)

## Page 2

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/204d7634-65a4-458d-b6a3-ed498a1d3551/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/204d7634-65a4-458d-b6a3-ed498a1d3551/Untitled.png)
