# Angular Projects Repo

## Reference
* [Angular Essentials | Angular.dev](https://angular.dev/essentials)
* [Difference between Angular and AngularJS](https://www.scaler.com/topics/angular/difference-between-angularjs-and-angular/)
* [Using Angular in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/angular-tutorial)
* [Download Node.js](https://nodejs.org/en)
* [Angular CLI | github](https://github.com/angular/angular-cli)
* [Angular - The Complete Guide (2024 Edition) | Udemy](https://www.udemy.com/course-dashboard-redirect/?course_id=756150)

## Setup Angular Environment

### Install Node.jS
Node.js is a javascript runtime that allows you to run javascript outside of the browser. Angular is not a Node.js framework, it's a browser side framework in the end. However, to install and use the [Angular CLI](https://angular.dev/cli) as well as run the Angular application server, you'll need the [Node.js](https://nodejs.org/) JavaScript runtime and npm (the Node.js package manager) installed. npm is included with Node.js which you can install from [Node.js downloads](https://nodejs.org/en/download/).

### Install Angular CLI
To install the Angular CLI, in a terminal or command prompt type:
```console
$ npm install --global @angular/cli
```

### Commands to Validate Setup
```console
$ node --version
$ npm --version
$ ng --version
```

## Create a New Angular App
* You can now create a new Angular application by typing:
```console
$ ng new my-first-ng-app
```
> [!NOTE]
> After issuing the "$ ng new ..." command, pick the default options for stylesheet format ("CSS") and SSR/SSG ("no") by hitting Enter.
> Wait few minutes for the project to be created. 
* Link to a newly created Angular app: [my-first-ng-app](https://github.com/navrwork/angular/tree/main/my-first-ng-app)

## Run the Angular App
* You can run the Angular app directly from the IDE (say, Visual Studio Code) or from command prompt.
* Enter the below command to start/run the Angular application :
```console
$ ng serve
```
* Once the app starts, visit http://localhost:4200/ from a browser. You should see a page similar to the one below.
  <img src="https://github.com/user-attachments/assets/11c383df-a031-4051-acbc-da5e7a994162" height="400" width="800"></img>
