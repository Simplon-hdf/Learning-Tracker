# Proposition technique :

![](/doc/Assets/proposition.jpg)

### Introduction

Afin de déterminer le choix des technologies notre équipe a effectué une analyse comparative détaillée de différentes options technologiques en se basant sur les besoins du client, la performance, la réactivité et la sécurité. Nous avons mis en place une méthode structurée pour comparer objectivement ces options en utilisant des critères précis. Notre objectif était de sélectionner les technologies les plus adaptées pour atteindre les objectifs du projet de manière efficace et de satisfaire les besoins du client sans négliger les aspects de performance, de réactivité et de sécurité.

<details>

<summary><b>Tableau comparaison back-end</b></summary>

| Back                    | Koa | Fastify | Nest | Adonis |
| ----------------------- | --- | ------- | ---- | ------ |
| Big ou small            | 3   | 3       | 4    | 4      |
| \_ Custo                | 4   | 3       | 5    | 2      |
| \_ Rapidité             | 3   | 4       | 4    | 3      |
| Popularité              | 3   | 2       | 4    | 2      |
| Maturité                | 4   | 3       | 2    | 3      |
| Releases                | 3   | 4       | 3    | 3      |
| Best Practices          | 4   | 3       | 4    | 3      |
| Equipe Core             | 2   | 3       | 5    | 2      |
| GitHub Stars            | 3   | 2       | 5    | 1      |
| Licence Open Source     | 4   | 3       | 4    | 4      |
| \_ Distribution         | 4   | 3       | 4    | 3      |
| \_ Commercial           | 4   | 2       | 3    | 4      |
| \_ Modification         | 4   | 2       | 4    | 3      |
| \_ Restriction          | 3   | 2       | 3    | 3      |
| Commu GitHub            | 5   | 3       | 4    | 1      |
| \_ Contributeurs        | 2   | 5       | 4    | 1      |
| \_ Used                 | 4   | 3       | 4    | 1      |
| \_ Issu                 | 3   | 4       | 5    | 2      |
| \_ Pull Request         | 4   | 3       | 5    | 1      |
| \_ Process contribution | 2   | 4       | 4    | 1      |
| Dernier commit          | 3   | 4       | 4    | 2      |
| Sponso                  | 3   | 1       | 5    | 2      |
| Stackoverflow           | 4   | 2       | 3    | 1      |
| \_ Tag                  | 3   | 3       | 3    | 3      |
| \_ Nombre de question   | 3   | 1       | 5    | 2      |
| \_ Dernière question    | 4   | 3       | 5    | 3      |
| \_ Réponse valider      | 4   | 3       | 5    | 2      |
| Documentation           | 4   | 3       | 5    | 2      |
| Bibliothèque            | 4   | 3       | 4    | 3      |
| Magique                 | 2   | 1       | 2    | 1      |
| Mariage librairies      | 3   | 3       | 4    | 2      |
| Prise politique         | 4   | 3       | 3    | 5      |
| Payant                  | 4   | 4       | 2    | 4      |
| TOTAL                   | 113 | 95      | 130  | 79     |

</details>

</br>

<details>

<summary><b>Tableau comparaison front-end</b></summary>

| Front                 | Angular | ReactJS | VueJS |
| --------------------- | ------- | ------- | ----- |
| Big ou small          | 4       | 3       | 3     |
| \_ Custo              | 3       | 4       | 4     |
| \_ Rapidité           | 3       | 4       | 4     |
| Popularité            | 3       | 5       | 4     |
| Maturité              | 4       | 3       | 1     |
| Releases              | 3       | 4       | 4     |
| Best Practices        | 4       | 3       | 3     |
| Equipe Core           | 4       | 4       | 2     |
| GitHub Stars          | 3       | 4       | 5     |
| Licence Open Source   | 4       | 4       | 4     |
| Commu GitHub          | 3       | 5       | 3     |
| \_ Contributeurs      | 4       | 4       | 2     |
| \_ Used               | 3       | 5       | 3     |
| \_ Issu               | 4       | 3       | 2     |
| \_ Pull Request       | 3       | 4       | 4     |
| Dernier commit        | 4       | 4       | 2     |
| Sponso                | 3       | 3       | 4     |
| Stackoverflow         |
| \_ Tag                | 4       | 4       | 4     |
| \_ Nombre de question | 4       | 5       | 3     |
| \_ Dernière question  | 4       | 5       | 3     |
| \_ Réponse valider    | 3       | 4       | 3     |
| Documentation         | 5       | 4       | 3     |
| Bibliothèque          | 3       | 4       | 4     |
| Mariage librairies    | 3       | 4       | 4     |
| Prise politique       | 4       | 4       | 4     |
| Payant                | 4       | 4       | 4     |
| TOTAL                 | 93      | 101     | 88    |

</details>

## Choix de la stack

| Technologies | Description                                                                                                                                                                                                         |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Node.js      | Node.js est un environnement d'exécution JavaScript côté serveur qui permet de développer des applications web.                                                                                                     |
| Nest.js      | Nest.js est un framework back-end basé sur Node.js et TypeScript. Il a été créé pour fournir une structure modulaire et claire pour le développement d'applications backend.                                        |
| React.js     | React.js est un front-end basé sur JavaScript qui a été développé par Facebook. Il permet aux développeurs de créer des applications web côté client de manière efficace en utilisant des composants réutilisables. |
| PostgreSQL   | PostgreSQL est un système de gestion de bases de données relationnelles (RDBMS) open source de haute performance.                                                                                                   |
| Prisma       | Prisma est un framework open source qui vous permet de gérer votre base de données de manière simple et intuitive en utilisant une syntaxe proche de SQL et une couche de mapping de données (ORM).                 |

</br>

### Environnement d'exécution

![](/doc/Assets/nodejs-logo.png)

Node.js est un environnement d'exécution JavaScript côté serveur qui connaît un grand succès depuis plusieurs années. Il est basé sur le moteur JavaScript V8 de Google, ce qui lui confère une excellente performance et une exécution rapide des codes JavaScript.

L'un des principaux atouts de Node.js est son modèle d'exécution asynchrone basé sur des événements, qui le rend particulièrement adapté aux applications Web qui doivent gérer de nombreuses requêtes simultanées de manière efficace. En utilisant ce modèle, Node.js peut traiter de nombreuses requêtes en parallèle sans avoir à attendre que chacune d'entre elles soit terminée, ce qui peut significativement améliorer les temps de réponse de l'application.

Node.js est également très populaire et bien soutenu par une grande communauté de développeurs, ce qui signifie qu'il y a de nombreuses ressources et outils disponibles pour nous aider dans le développement de notre projet. En outre, Node.js est compatible avec de nombreux systèmes de gestion de bases de données et technologies de développement web, ce qui nous permet de choisir les outils qui conviennent le mieux à notre projet et à notre équipe de développement.

En somme, Node.js est un environnement d'exécution JavaScript côté serveur performant et flexible qui peut être un choix judicieux pour de nombreux projets Web. Je suis convaincu que l'utilisation de Node.js pour notre projet nous permettra de développer une application de qualité, performante et maintenable.

### Framework Back-End

![](/doc/Assets/nest-js-logo.png)

Pour le développement de notre projet de site web, nous avons choisi d'utiliser Nest.js comme framework back-end.

Nest.js est un cadre de développement open source pour les applications Web côté serveur, basé sur Node.js. Il offre une structure modulaire et scalable pour la construction de notre application, ainsi qu'une architecture claire et logique pour organiser notre code. De plus, Nest.js est nativement intégré à TypeScript, ce qui peut être bénéfique pour la qualité et la maintenabilité de notre code.

En utilisant Nest.js, nous pouvons profiter de la puissance et de la flexibilité de Node.js tout en bénéficiant d'un cadre de développement structuré et adapté aux meilleures pratiques de développement back-end.

En résumé, Nest.js est un cadre de développement back-end complet et performant qui peut être un choix judicieux pour de nombreux projets Web basés sur Node.js.

### Base de Donnée

![](/doc/Assets/postgres-logo.png)

Dans le cadre de notre projet nous avons le choix de l'utilisation de PostgreSQL comme système de gestion de bases de données.

PostgreSQL est un système de gestion de bases de données open source puissant et flexible. Il prend en charge un large éventail de fonctionnalités avancées, notamment des index full-text, des requêtes JSON, des types de données géospatiales et de nombreuses autres fonctionnalités utiles pour les développeurs d'applications Web.

En utilisant PostgreSQL, nous pouvons être sûrs de disposer d'une base de données fiable et performante pour stocker et gérer les données de notre application. PostgreSQL est également très populaire et bien documenté, ce qui facilite la recherche de solutions en cas de problèmes ou de questions.

En somme, PostgreSQL est un système de gestion de bases de données open source puissant et flexible, adapté aux besoins de nombreux projets Web. Sa large gamme de fonctionnalités avancées et sa fiabilité en font un choix judicieux pour notre projet de site web. Je suis convaincu que l'utilisation de PostgreSQL nous permettra de gérer efficacement les données de notre application et de bénéficier d'une base de données performante et fiable.

### Proposition d'ORM

![](/doc/Assets/prisma.jpg)

Pour le choix de l'ORM nous vous proposons prisma comme ORM (Object-Relational Mapping).

Prisma est une bibliothèque open source qui facilite la gestion des données dans les applications basées sur une base de données. Elle offre une interface de programmation (API) pour la manipulation de données qui est simple à utiliser et qui permet de générer automatiquement du code SQL. Cela signifie que vous pouvez écrire du code qui est plus facile à lire et à maintenir, sans avoir à écrire des requêtes SQL complexes et difficiles à comprendre.

En utilisant Prisma, vous pouvez également éviter les erreurs courantes liées à l'écriture de requêtes SQL manuellement. Par exemple, si vous oubliez une virgule ou si vous utilisez le mauvais type de données, cela peut entraîner des erreurs difficiles à déboguer. Prisma vous permet d'éviter ces erreurs en générant automatiquement du code SQL qui est correct et optimisé.

De plus, Prisma offre une grande flexibilité et peut être utilisé avec de nombreuses bases de données différentes, y compris MySQL, PostgreSQL et MongoDB. Cela signifie que vous pouvez facilement changer de base de données si vous en avez besoin, sans avoir à réécrire votre code de gestion de données.

En résumé, Prisma est une bibliothèque pratique et efficace pour la gestion des données dans les applications Web. Son utilisation dans notre projet nous permettra de développer une application de qualité, facile à maintenir et performante.

### Framework Front-End

![](/doc/Assets/reactjs.png)

Concernant le choix du framework front-end notre choix ces tournée vers react.js.

React.js est un framework JavaScript open source qui est de plus en plus populaire pour le développement d'applications Web. Il a été développé par Facebook et il est utilisé par de nombreuses entreprises de renom, telles que Airbnb, Dropbox et Netflix.

L'un des principaux avantages de React.js est sa flexibilité. Il peut être utilisé pour développer des applications Web de toutes tailles, des petits sites de présentation aux grandes applications Web complexes. De plus, il peut être utilisé avec de nombreux autres frameworks et bibliothèques JavaScript, ce qui vous permet de créer des applications Web riches en fonctionnalités.

React.js est également très performant. Il utilise une approche appelée "virtual DOM", qui permet de mettre à jour uniquement les parties de l'application qui ont changé, plutôt que de mettre à jour l'ensemble de l'application à chaque modification. Cela signifie que les applications React.js sont généralement plus rapides que les applications développées avec d'autres frameworks.

En utilisant React.js, nous pouvons développer une application Web qui est facile à maintenir et à développer, grâce à sa syntaxe simple et à sa communauté active de développeurs.
L'utilisation de React.js nous permettra de créer une application front-end performante et facile à utiliser pour les utilisateurs de notre site web.
