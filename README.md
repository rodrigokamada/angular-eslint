# Angular ESLint



[![Website](https://shields.braskam.com/v1/shields?name=website&format=rectangle&size=small&radius=5)](https://rodrigo.kamada.com.br)
[![LinkedIn](https://shields.braskam.com/v1/shields?name=linkedin&format=rectangle&size=small&radius=5)](https://www.linkedin.com/in/rodrigokamada)
[![Twitter](https://shields.braskam.com/v1/shields?name=twitter&format=rectangle&size=small&radius=5&socialAccount=rodrigokamada)](https://twitter.com/rodrigokamada)
[![Instagram](https://shields.braskam.com/v1/shields?name=instagram&format=rectangle&size=small&radius=5)](https://www.instagram.com/rodrigokamada)



## Prerequisites


Before you start, you need to install and configure the tools:

* [git](https://git-scm.com/)
* [Node.js and npm](https://nodejs.org/)
* [Angular CLI](https://angular.io/cli)
* IDE (e.g. [Visual Studio Code](https://code.visualstudio.com/))



## Getting started


### Create the Angular application


**1.** Let's create the application with the Angular base structure using the `@angular/cli` with the route file and the SCSS style format.

```shell
ng new angular-eslint --routing true --style scss
CREATE angular-eslint/README.md (1067 bytes)
CREATE angular-eslint/.editorconfig (274 bytes)
CREATE angular-eslint/.gitignore (548 bytes)
CREATE angular-eslint/angular.json (3136 bytes)
CREATE angular-eslint/package.json (1045 bytes)
CREATE angular-eslint/tsconfig.json (863 bytes)
CREATE angular-eslint/.browserslistrc (600 bytes)
CREATE angular-eslint/karma.conf.js (1431 bytes)
CREATE angular-eslint/tsconfig.app.json (287 bytes)
CREATE angular-eslint/tsconfig.spec.json (333 bytes)
CREATE angular-eslint/.vscode/extensions.json (130 bytes)
CREATE angular-eslint/.vscode/launch.json (474 bytes)
CREATE angular-eslint/.vscode/tasks.json (938 bytes)
CREATE angular-eslint/src/favicon.ico (948 bytes)
CREATE angular-eslint/src/index.html (299 bytes)
CREATE angular-eslint/src/main.ts (372 bytes)
CREATE angular-eslint/src/polyfills.ts (2338 bytes)
CREATE angular-eslint/src/styles.scss (80 bytes)
CREATE angular-eslint/src/test.ts (749 bytes)
CREATE angular-eslint/src/assets/.gitkeep (0 bytes)
CREATE angular-eslint/src/environments/environment.prod.ts (51 bytes)
CREATE angular-eslint/src/environments/environment.ts (658 bytes)
CREATE angular-eslint/src/app/app-routing.module.ts (245 bytes)
CREATE angular-eslint/src/app/app.module.ts (393 bytes)
CREATE angular-eslint/src/app/app.component.scss (0 bytes)
CREATE angular-eslint/src/app/app.component.html (23364 bytes)
CREATE angular-eslint/src/app/app.component.spec.ts (1097 bytes)
CREATE angular-eslint/src/app/app.component.ts (219 bytes)
✔ Packages installed successfully.
    Successfully initialized git.
```

**2.** Now we will install the libraries and add the ESLint settings.

```shell
ng add @angular-eslint/schematics
ℹ Using package manager: npm
✔ Found compatible package version: @angular-eslint/schematics@14.0.2.
✔ Package information loaded.

The package @angular-eslint/schematics@14.0.2 will be installed and executed.
Would you like to proceed? Yes
✔ Packages successfully installed.
    
    All @angular-eslint dependencies have been successfully installed 🎉
    
    Please see https://github.com/angular-eslint/angular-eslint for how to add ESLint configuration to your project.
    
    We detected that you have a single project in your workspace and no existing linter wired up, so we are configuring ESLint for you automatically.
    
    Please see https://github.com/angular-eslint/angular-eslint for more information.
    
CREATE .eslintrc.json (984 bytes)
UPDATE package.json (1511 bytes)
UPDATE angular.json (3447 bytes)
✔ Packages installed successfully.
```

**3.** Next, we will run the command below to validate the ESLint installation and configuration.

```shell
npm run lint

> angular-eslint@1.0.0 lint /home/rodrigokamada/angular-eslint
> ng lint


Linting "angular-eslint"...

All files pass linting.
```

**4.** Ready! The message *All files pass linting.* shows that no problem was found.
