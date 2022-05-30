# PS-2020-Fan-Site

*PS = Projet Scolaire*

📚 Projet Scolaire | Réalisation d'un Fan Site HTML CSS | Octobre 2020

Individuel

## 📎 Vidéo de démonstration :



## 📌 Consignes du projet :

Réalisation d'un Fan Site

But de l'exercice
Réaliser un site web en HTML-CSS (sans utiliser de template, ni aucune bibliothèque de fonctions ou framework) avec une page principale et quelques pages annexes accessibles depuis la page principale (Par exemple : Une page de détails pour chaque album/livre présent sur la page principale).

Ce Fan Site devra porter sur le groupe/artiste/auteur/éditeur que vous avez choisi (sobrement appelé "sujet" dans la suite des consignes).

Une archive (ZIP, 7Z ou RAR) contenant les différents fichiers (HTML + CSS + images) est à déposer sur MyLearningBox avant le **Vendredi 23 Octobre à 19H**.

Si vous avez des questions, posez-les moi sur Teams (ou par mail) avant le mercredi soir (21 octobre).

Attentes par rapport à cet exercice
- Le site web doit être créé à partir de rien ("From scratch" comme disent les développeurs ou "Ex nihilo" comme disent les latins) Donc pas d'utilisation de template, ni de Bootstrap, ...
- Votre site web doit être composé d'au moins 1 page principale et 2 pages annexes (accessibles depuis la page principale)
- Chaque page web doit correspondre à un fichier HTML et l'unique fichier CSS doit être partagé entre toutes les pages
- Tout le code CSS doit être dans un seul fichier .css. Du coup, aucun code CSS ne doit apparaitre dans le code HTML (pas d'attribut "style" dans le HTML)
- Vous devez utiliser au maximum la technique de mise en page "Flexbox" et les balises structurantes HTML5 (l'utilisation de la balise "div" est autorisée mais elle est à limiter)
- L'utilisation de balises HTML et/ou de propriétés CSS non vues en cours est évidemment autorisée (même conseillée)
- Votre code doit être lisible, organisé et un minimum commenté (au moins quelques commentaires pour organiser le code CSS)
- La site web doit être responsive : Sans devoir le tester sur votre smartphone, votre site doit pouvoir s'adapter au maximum à la taille de la fenêtre de votre navigateur (Seuls les "iframe" avec les vidéos n'ont pas besoin d'être responsives)
- Le style / design final de votre site a peu d'importance tant qu'on s'y retrouve facilement quand on le visite
- Même si cela ne sera pas noté, les fautes d'orthographes sont à éviter au maximum dans la partie visible du site (pour les commentaires du code, c'est moins grave)
- Et évidemment, il faut respecter au maximum les consignes présentes dans ce document (ci-dessus et ci-dessous) mais vous pouvez prendre quelques libertés concernant le design et le contenu
- Aucune musique (ni vidéo) doit être lancée au chargement de la page sans autorisation de l'utilisateur
- Les différentes ressources du site devront être "rangées" dans des sous-dossiers cohérents (un sous-dossier "images" pour les images par exemple)
- Le site complet (avec les images) devra être envoyé sous la forme d'un ZIP (ou d'un RAR) qui ne devra pas dépasser 20Mo

En-tête et Bas de page
- Les différentes pages du site devront partager une en-tête et un bas de page semblable pour qu'il y ait une "cohérence" entre les pages (un simple copier-coller du code HTML dans les différentes pages suffit tant que le code reste bien organisé).

- L'en-tête des pages devra au moins contenir le nom du sujet (ou une image contenant le nom du sujet) et prendre toute la largeur de la page. Dans le code HTML, tout le contenu de l'en-tête devra être situé dans une balise "header". Si l'en-tête de la page principale contient un menu de navigation, ce menu de navigation ne devra évidemment pas apparaitre dans l'en-tête des pages annexes.

- Le bas de page devra au moins contenir votre nom et prénom et prendre toute la largeur de la page. Dans le code HTML, tout le contenu du bas de page devra être situé dans une balise "footer".

Page principale
- La page principale doit avoir un menu de navigation avec des liens internes qui emmènent aux différentes sections de la page. Ce menu de navigation doit correspondre à une liste (balises "ul" et "li") contenue dans la balise structurante "nav".

- Une section "Mini-Biographie" utilisant la balise "section" doit être présente et doit au moins contenir :
    -> la mini-bio de votre sujet dans une balise "article" (Vous pouvez récupérer des informations de Wikipédia à partir du moment où vous citez votre source)
    -> ainsi que quelques informations accompagnées d'une photo dans une balise "aside" 
    
- Une section doit être présente avec des images de même largeur en mode Flex avec "wrap". Chaque image doit mener à une page annexe de votre Fan Site et quand l'utilisateur passe sa souris sur l'image, il doit y avoir une modification visuelle sur l'image pour montrer que l'image est clicable (par exemple, afficher une bordure autour de l'image quand on la survole avec la souris). Si vous partez sur un Fan Site d'un groupe de musique, vous pouvez faire une section avec quelques pochettes d'albums qui mènent chacune vers une page annexe avec les détails de l'album (mais vous n'êtes pas obligé de faire exactement cela)

- Une autre section doit être présentes avec 2 ou 3 vidéos intégrées (YouTube, Vimeo, Dailymotion, ...) situées les unes au dessus des autres.

Pages annexes
- Comme indiqué précédemment, les page annexes doivent avoir la même en-tête et le même bas de page

- Le contenu des annexes est un peu plus libre : il faut au moins une image et du texte (si possible avec un paragraphe avec votre avis personnel si le sujet s'y prête). Si votre page annexe correspond aux détails d'un album, vous pouvez rafficher la pochette en plus grand, ajouter la liste des morceaux en dessous et ajouter un paragraphe avec votre avis sur l'album.
