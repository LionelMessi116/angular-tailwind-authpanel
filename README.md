# :zap: Angular Tailwind Auth Panel

* Angular 11 app using [Webpack v5](https://webpack.js.org/) & [Tailwindcss](https://developers.google.com/chart/) components to display a login dashboard
* Tutorial code from [CodingAndCaffeine, Youtube channel](https://www.youtube.com/channel/UCQk_kRUoxJQY5vqbJQFgJDA) - see [:clap: Inspiration](#clap-inspiration) below
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/angular-tailwind-authpanel?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/angular-tailwind-authpanel?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/angular-tailwind-authpanel?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/angular-tailwind-authpanel?style=plastic)

## :page_facing_up: Table of contents

* [:zap: Angular Tailwind Auth Panel](#zap-angular-tailwind-auth-panel)
  * [:page_facing_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal_strength: Technologies](#signal_strength-technologies)
  * [:floppy_disk: Setup](#floppy_disk-setup)
  * [:wrench: Testing](#wrench-testing)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status & To-Do List](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:file_folder: License](#file_folder-license)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* Webpack explained in [Webpack documentation Concepts](https://webpack.js.org/concepts/)
* To build for production Tailwind’s purge option is used to tree-shake unused styles and optimize final build size.
* `angular.json` file modified to use custom builder and `webpack.config.js` file

## :camera: Screenshots

![Example screenshot](./img/login.png)

## :signal_strength: Technologies

* [Angular framework v11](https://angular.io/)
* [Webpack v5](https://webpack.js.org/) static module bundler for modern JavaScript applications.
* [Tailwindcss v2](https://tailwindcss.com/) CSS framework
* [postcss-loader v4](https://www.npmjs.com/package/postcss-loader) Loader to process CSS with PostCSS. Transformations that are applied to the source code of a module, to pre-process files as you import or “load” them.
* [postcss-scss v3](https://www.npmjs.com/package/postcss-scss) SCSS parser for PostCSS.
* [ngx-build-plus](https://www.npmjs.com/package/ngx-build-plus) to extend the Angular CLI's default build behavior. Allows a partial custom webpack config to be merged with the CLI's one.

## :floppy_disk: Setup

* Run `npm i` to install dependencies.
* Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
* Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## :wrench: Testing

* Run `ng test` to run Jasmine unit tests via [Karma](https://karma-runner.github.io)
* Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## :computer: Code Examples

* extract from `app.component.html` showing tailwindcss used to style input checkbox & label

```typescript
<div class="flex items-center">
  <input
    id="remember_me"
    name="remember_me"
    type="checkbox"
    class="w-4 h-4 text-indigo-600 border-gray-300 rounded focus:ring-indigo-500"
  />
  <label for="remember_me" class="block ml-2 text-sm text-gray-900">
    Remember me
  </label>
</div>
```

## :cool: Features

* Tailwindcss [sign-in form](https://tailwindui.com/components/application-ui/forms/sign-in-forms)] component simply copy-pasted into app.

## :clipboard: Status & To-Do List

* Status: Working. All filees pass linting. App passes unit tests. e2e testing not set up so doesn't pass. Build file is a compact 241.70kb thanks to Tailwind’s purge option (manually enabled in `tailwind.config.js`) that tree-shakes unused styles and optimizes the final build size.
* To-Do: Nothing

## :clap: Inspiration

* [Angular 11 and Tailwind; Let's go!](https://www.youtube.com/watch?v=ul8UvsBWM3Y)
* [Tailwindcss docs: Optimizing for Production](https://tailwindcss.com/docs/optimizing-for-production#setting-up-purgecss)
* [Trungk18.com: How to configure TailwindCSS with Angular and why you should use it](https://trungk18.com/experience/configure-tailwind-css-with-angular/)
* [Angular Architects: article: Extending the Angular CLI’s build process without ejecting](https://www.angulararchitects.io/aktuelles/extending-the-angular-clis-build-process/)

## :file_folder: License

* This project is licensed under the terms of the MIT license.

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: gomezbateman@yahoo.com
