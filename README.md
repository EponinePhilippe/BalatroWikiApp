# BalatroWikiApp

Balatro Wiki App est un projet que j’ai réalisé avec un autre stagiaire dans le cadre de mon stage de première année de BTS SIO (Services Informatiques aux Organisations). Celui-ci a pour but de répertorier les différentes cartes ainsi que tous les éléments du jeu Balatro qui influencent l’expérience de jeu.

L’application permet la modification de toutes les données contenues dans les listes uniquement si l’utilisateur est connecté avec un compte possédant les droits d’administrateur. Dans le cas contraire, les données sont accessibles en consultation uniquement.

Cette application m’a permis de mettre en pratique les tutoriels réalisés en début de stage et de consolider mes connaissances du framework Blazor. Nous avons également conçu et intégré la base de données du projet, en mettant en place les différentes classes et en assurant la liaison entre les données et l’application.

Prérequis pour utiliser le wiki de Balatro :

- PostgreSQL doit être installé sur l'appareil.

- PgAdmin 4 doit être installé.

- Consultez le fichier appsettings.json.

- Créez un utilisateur dans pgAdmin nommé « user » avec le mot de passe « balatro », et assurez-vous que les options « Superuser? » et « Can login? » sont activées.

- Créez une base de données nommée « BalatroDB » (en suivant les instructions du fichier appsettings.json).