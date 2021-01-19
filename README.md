4 - vercel -v

5 - npm install -g @angular/cli
    ng new appWebDep

6 - vercel

7 - vercel list

8 - vercel log https://app-web-dep.vercel.app/

9 - vercel inspect https://app-web-dep.vercel.app/

10 - Les variables d'environnements permettent de stocker des informations utilisables par plusieurs processus simultanément à l'extérieur d'une application

11 - vercel env add plain ENV1 production

12 - vercel env ls

13 - Les secrets permettent d'utiliser du contenu crypté dans des variables d'environnement

15 - vercel secrets add env_secret2 null

16 - Les 3 environnements sont Production, Preview et Development. Avoir plusieurs environnements permet de faire des tests sur les environnements de développement et de preview sans toucher à la version de production fournie aux utilisateurs du site.

17 - https://github.com/Nazrallie/AppWebDeploy

18 - app-web-dep-git-master.nazrallie.vercel.app

19 - Une pull-request est une demande d'ajout de son code à un code plus large. Cela permet à plusieurs personnes de travailler en même temps sur un même projet et de pouvoir créer une branche évoluant en parallèle de la principale. Cela permet de discuter des changements effectués ou de les modifier avant de les merge à la branche master.

Changement

Vercel déploie la pull request automatiquement dans un environnement de preview

20 - Vercel déploie la pull request automatiquement dans un environnement de production

21 - L'environnement de production correspond à la branche master.
     L'intérêt de faire des pulls request permet de faire des version temporaire de l'application et de tester des configurations.
     A chaque nouvelle feature on créé une branche dans laquelle on développe la nouvelle feature, une fois qu'elle est prête on la merge sur la branche principale pour l'ajouter au projet.

22 - Le serverless est un modèle de développement qui permet aux développeurs de créer et d'exécuter des applications sans avoir à gérer des serveurs. Un fournisseur de cloud s'occupe de gérer l'infrastructure serveur et le développeur n'a plus qu'à envoyer le code dans des conteneurs pour déployer l'application. Les ressources serveurs disponibles sont aussi allouées dynamiquement. Ce genre d'app permet de au développeur de se concentrer sur le développement de nouvelles fonctionnalités en priorité.


# AppWebDep

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
