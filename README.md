# booki-starter-pack


L’entreprise souhaite développer un site Internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix.



Vous êtes chargé d'intégrer l'interface du site avec du code HTML et CSS. Pour cela, vous travaillez en étroite collaboration avec Sarah, la CTO, et Loïc, l’UI designer.



Sarah vous envoie un e-mail pour vous présenter l’avancée du projet.

Objet : Maquette site Booki
De : Sarah
À : Vous

Bonjour,



Ça y est, Loïc a finalisé la maquette du site ! Tu vas pouvoir l'intégrer. Elle est disponible en pièce jointe.



Pour que le projet soit très clair, Loïc et moi t’avons préparé une note de synthèse qui regroupe les spécifications et contraintes techniques à respecter (voir pièce jointe).



Pour t’aider à démarrer, je t’ai préparé la structure de fichiers du site ainsi qu’une base de code :

un fichier “index.html” contenant une première base du code HTML que tu devras compléter ;

un dossier “css” contenant un fichier “style.css” avec une première ébauche du code CSS et que tu devras compléter également ;

un dossier “images” contenant l’ensemble des images utilisées sur le site.



Ce code est déjà un peu fourni et il te donnera les premiers éléments HTML et CSS. Tu peux t’en inspirer pour développer le reste du code, et il faut que tu conserves la même structure de dossiers. Tu devras ensuite m’envoyer ce dossier complet.

Bon courage pour ce projet, et bonne journée !

Sarah, CTO @Booki
Pièces jointes :
Maquette du site Booki
Note de synthèse pour intégration du site Booki


Ravi par ce projet, vous commencez par vous plonger dans l’étude de la maquette !

Attention, sur Figma vous trouverez du code d'exemple proposé pour faciliter le développement des éléments de l'interface. Ce code vous causera souvent des problèmes (mauvais positionnement relatif ou absolu, mesures en pixels et non en mesure relative, etc.). Il est recommandé de ne pas utiliser ce code, à moins d'être sûr de bien comprendre ce qu'il fait.

Pour vous aider à mener à bien cette mission, vous pouvez suivre les étapes décrites ci-dessous.



1. Étapes  
Une fois cette étape terminée, vous devriez avoir :

votre éditeur de code (au choix) installé.
Recommandations :

Récupérez la base de code fournie dans l’énoncé du projet. Ouvrez-la avec Visual Studio Code et vérifiez que le site s’affiche correctement.

Points de vigilance :

Le code fourni devrait vous permettre de faire fonctionner le site dès le début, même s’il est incomplet. Cependant, si vous modifiez le code et rencontrez des difficultés, posez-vous les questions suivantes :
Avez-vous bien lié le fichier CSS dans le code HTML ?
Avez-vous importé les polices Google Fonts avant de les utiliser ?
Utilisez-vous les bonnes classes des icônes Font Awesome ?
Le style CSS ne fonctionne pas correctement.
La police ne s’affiche pas correctement.
Les icônes Font Awesome ne s’affichent pas correctement.
Il y a des erreurs, des problèmes d’affichage ou bien quelque chose d'autre ne fonctionne pas dans votre code ?  C'est une chose qui arrive souvent en développement. C'est pourquoi il est important de savoir comment débugger son code en utilisant des outils adaptés tels que l’inspecteur de code. Pour cela, soyez attentif au chapitre « Testez votre code avec les devtools Chrome et Firefox » du cours Mettez en place votre environnement front-end donné dans les ressources.
Ressources :

> Le cours Mettez en place votre environnement front-end en sautant les parties sur Git.
La documentation officielle pour utiliser Font Awesome.

---
- la demande était d'intégrer l'interface du site BOOKI avec du code **HTML et CSS**.
> - à partir d'une maquette [FIGMA]() contenant les différents composants nécessaire à l'intégration dans les écrans et résolutions uniquement de **1025px et plus** avec un container central de **maximum 1440px de large** 


- Comment as-tu analysé la maquette et comment est-ce que cela a influencé ton travail ?
> - Je suis allée comparer les composants à créer et ceux déjà présant dans le css fournit et la strutures du HTML
> - pris le paramètre général qui était que la taille maximal de container principal ne devait pas dépasser 1440px.
> - j'ai ajouter des style pour faire en sorte que certaines propriétées soit générique 


- Pourquoi passer au validateur ? Quels en sont les publics et les bénéfices ?
> un validateur comme le W3C permet de définir les standards techniques liés au web. Surtout, ils déterminent les mêmes règles pour tous les développeurs du monde.

- Pourquoi adhérer aux standards ?
> cela permet de homogénéiser son code et d'être compris de tous: ainsi d'avoir un code maintenanble par tous

- spécificité en CSS
> importance donnée à une déclaration CSS 
> - selon l'ordre dans laquelle elle est écrite dans le css 
> - le type de selecteur 
>   - tag
>   - .class
>   - #id
>   - exception **!important**
