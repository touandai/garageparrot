# garageparrot
Résumé Projet  

L'objectif de ce travail consiste à concevoir l’application web du Garage Vincent Parrot situé à Toulouse. 

Un garage qui propose différents services à savoir :  Service de réparation mécanique, de réparation de carrosserie et de la vente des voitures d’occasion.  

le but  recherché est de rendre disponible effectivement ces services, ou alors la société toute entière sur internet . L'intérêt est de faire connaitre cette entreprise , accroitre sa clientèle et augmenter son chiffre d’affaire. 

J'ai pu réalisé le travail grâce à des langages de programmation, outils et quelques ressources énumérées plus tard dans ce résumé. 

J’ai ainsi divisé le travail  naturellement en 2 parties : 

Une première partie consacrée au front-end (partie statique) 

Puis une seconde partie back-end pour lequel , j’ai rencontré quelques difficultés d’ordre technique lié surement à un statut d’inexpérimenté.  

Activité - Type 1 : Développer la partie Front-end d’une application Web ou Web mobile en intégrant les recommandations de sécurité 

LANGAGES : Javascript , HTML ET CSS 

Outils : FIGMA (pour la réalisation des Mockups), PAINT , GHITUB, VSCODE  

Dans cette partie du site ou l’usage essentiel demeure du html , css et javascript . 

J'ai pu concevoir la partie visible du site. Une page d’accueil , composée d’un header , un main et un footer. 

- dans le header sur l’entête du site , nous pouvons remarqué comme recommandé la présence du logo du garage à droite et d’un menu navbar comportant les 5 rubriques essentielles de l’application intégrant un formulaire flexbox. 

-Main, la partie où se situe le contenu principal est destinée à l’exposition des services proposés par l’entreprise ou on peut remarquer la présence des sections qui mènent à ses 4 services qui sont : réparations : Mécanique, carrosserie, ainsi que la vente des voitures d’occasion avec une dernière section destinée à recueillir les avis des clients . ( dans le cadre de la politique commerciale de monsieur Vincent Parrot . 

Footer : Tout en bas , le pied de page donne quelques informations importantes sur les mentions légales, et les horaires de l’entreprise mis à jour par l'administrateur.  

Vous pouvez cependant constater la présence d’une seconde barre de navigation comportant un lien donnant sur une page à propos qui retrace l’histoire du garage.  

La partie statique du site intègre la technologie  mobilefirst ,vous pouvez  le  constater lors de votre navigation (usage des médias). 


Activité - Type 2 : Développer la partie Back-end d’une application Web ou Web mobile en intégrant les recommandations de sécurité


Langages et outils utilisés :  

Langages : PHP / SQL (BASE DE DONNEES POSTGRES) 

Outils / RESSOURCES COMPLEMENTAIRES : XAMP, PGADMIN4 ,  

VISUAL Paradigme (Réalisation des différent Diagram ) 

J'avais à l’idée de créer un espace d’administration disposant d’un tableau de bord, comportant un petit menu avec les liens entre espace de connexion, déconnexion, listes des annonces et le recueil des avis.  

Les difficultés de connexion, d’installation des outils et API ne m’ont pas permis de tout réaliser comme prévu . 

Ainsi vous pouvez remarquer la création de la base de données à travers un fichier .sql joint au dossier . j’ai pu créer les différents utilisateurs , ADMIN, Employé et leur attribué les différents rôles,  voir fichier annexe ci-dessous 

Relation entre class User et class Contact (base de données) n’ a pas pu s’établir car, on part du principe que le contact se fait par adresse email du garage, le formulaire envoyé par l'utilisateur et ses données peuvent être mise à jour manuellement dans la base de données ce qui explique l'absence de relation entre ces 2 classes. 

 

J'ai pu joindre au dossier un fichier script_garage.sql permettant de consulter quelques commandes essentielles, m’ayant permises de créer et administrer ma base de données. 

En navigant ainsi sur le site vous avez la possibilité d’inscrire un nouvel user “employé” et le connecté au serveur.  

Vous pouvez simuler un rendez-vous coté client à partir de la rubrique dédiée, tout comme cogarage, laisser des avis.  

Les employés ont cependant la possibilité de mettre à jour les annonces et modérer les témoignages des utilisateurs.  

Ils peuvent se connecter à la base de données par exemple le super utilisateur (Administrateur) Mr Vincent PARROT avec son login : visible sur le fichier annexé ci-dessous, peut évidemment le faire depuis le compte perso. 

J'ai pu établir ma connexion avec la base de données comme vous pouvez le remarquer dans le code. Les formulaires sont sécurisés à l’aide du javascript et quelques attributs basiques en HTML m’a également permis de mieux contrôler les données entrées par des utilisateurs devons correspondre à la nature des éléments.  

Toutes les requêtes en effet, ont été préparées pour lutter contre de possibles injections SQL.  

Difficultés rencontrées : 

PATH : difficile cohabitation des fichiers au niveau de variable d’environnement / problème technique lié au port, faisant planter le poste de travail . 

Difficulté de mieux organiser un Dashboard backend suite à PGAADMIN  qui fonctionnait une fois sur 2. 

GIT m’a permis l’enregistrement des différentes versions mais n’arrive cependant pas à faciliter le déploiement du site en ligne malgré plusieurs tentatives sans succès.  Est-ce lié au poids de l’application plus conséquent que le minimum autorisé ? ci jointe une dernière sauvegarde de version.  

 

 

CONCLUSION 

 

L’application est adaptée à la technologie mobile-first et peut faire l’objet d’une mise en vente après un travail complémentaire et bien évidemment professionnelle surtout du côté Backend.  



