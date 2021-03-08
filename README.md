# Webpack Starter

Webpack starter for the vanila JS

## Getting Started

### Installation

Prerequisites: Make sure you have [**Node**](https://nodejs.org/en/) and **NPM** installed on your computer.

**Install NPM packages.**

```bash
$ npm install
```

### Running tasks

**Run Webpack devServer with development mode.** This task will automatically open your browser via devServer and reload pages whenever your files get updated.

```bash
$ npm run start
```

**Build development files.** This task will generate development files and emit them into **dist** folder.

```bash
$ npm run dev
```

**Build production files.** This task will generate production files and emit them into **dist** folder.

```bash
$ npm run prod
```

**Run Lint** You can run [ESLint](https://eslint.org/) in CLI.
Run Javascript and Sass lint.
```bash
$ npm run lint
```
Run Javascript Lint.
```bash
$ npm run lint:js
```
Run Sass Lint.
```bash
$ npm run lint:sass
```

**Run Prettier.** You can run [Stylelint](https://prettier.io/) in CLI.

```bash
$ npm run prettier:check
```
```bash
$ npm run prettier:write
```

### Folder Structure

```bash
├── .editorconfig # https://editorconfig.org/
├── .eslintignore
├── .eslintrc.json # https://eslint.org/
├── .gitignore
├── .prettierignore
├── .prettierrc.json # https://prettier.io/
├── .stylelintrc.json # https://stylelint.io/
├── LICENSE
├── README.md
├── dist # compiled files go here
├── package-lock.json
├── package.json
├── postcss.config.js
├── src # app's source files
│   ├── fonts
│   ├── html
│   │   ├── about.html
│   │   ├── hbs
│   │   │   └── header.hbs
│   │   └── index.html
│   ├── images
│   │   ├── sample-a.jpg
│   │   └── sample-b.jpg
│   ├── scripts
│   │   ├── app.js
│   │   └── components
│   │       └── button.js
│   └── styles
│       ├── app.scss
│       ├── base
│       │   └── reset.scss
│       └── components
│           └── button.scss
└── webpack.config.js # webpack entry
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
