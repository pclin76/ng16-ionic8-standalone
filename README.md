# Angular 16 (Standalone) w/ Ionic Framework 8

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.14.

```shell
ngvm n ng16-ionic8-standalone \
--routing=false \
-g \
-S \
--standalone \
--style=scss \
-ng 16
```

> **Options**
> - `--routing` Generate a routing module for the initial project. [**`boolean`**]
> - `-g`, `--skip-git` Do not initialize a git repository.
> - `-S`, `--skip-tests` Do not generate `spec.ts` test files for the new project.
> - `--standalone` Creates an application based upon the standalone API, without `NgModules`.
> - `--style` The file extension or preprocessor to use for style files. [**`string`**: `css`, `scss`, `sass`, `less`]

When using **Ionic Framework** in an Angular project, install the latest **`@ionic/angular`** package from npm. This comes with all of the Ionic Framework components and Angular specific services and features.

```shell
npm i @ionic/angular@latest --save
```

For adding Ionic to an already existing Angular project, use the Angular CLI's `ng add` feature.

```shell
ng add @ionic/angular
```

This will add the necessary imports to the **`@ionic/angular`** package as well as add the styles needed.

```shell
git init && \
git add . && git commit -m '初次提交' && \
git branch -M main && \
git remote add origin git@github.com:username/repository.git && \
git push -u origin main
```

## Development server

Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng g c component-name` to generate a new component. You can also use `ng g directive|pipe|service|class|guard|interface|enum|module`.

> **Command**
> - `g c` Creates a new, generic component definition in the given project.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
