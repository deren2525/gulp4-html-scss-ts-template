# gulp4-html-scss-ts-template
<div align="center">
<img src="https://user-images.githubusercontent.com/32975158/72197803-f0d5ad80-3468-11ea-9a9e-b706eda9f90d.jpg" alt="gulp-html-scss-typescript" title="gulp-html-scss-typescript">
</div>

> HTML × SCSS × TypeScript Template🐶 By gulp v4
> （gulp v4 による HTML × SCSS × TypeScript テンプレート）

## 📦 Features
- SCSS to CSS converter
- TypeScript to JavaScript converter
- Autoprefixer CSS
- HTML Formatter
- [Normalize.css](https://necolas.github.io/normalize.css/)

### Directory structure

```
...
├─ gulpfile.ts
├─ index.html
├─ src/
│  ├─ scss/
│  │  └─ style.scss
│  ├─ typescript/
│  │ └─ main.ts
│  └─ image/
│
└─ dist/ // What is automatically converted is stored here📦.
    ├─ css/
    │  └─ style.css
    ├─ js/
    │  └─  main.js
    └─ image/
```

## Recommend VSCode Extensions
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

## 💬 Usage
### 0. How to set up gulp
If you've previously installed gulp globally, run `npm rm --global gulp` before following these instructions.
For more information, read this [Sip](https://medium.com/gulpjs/gulp-sips-command-line-interface-e53411d4467).

1. Check for `node`, `npm`, and `npx`.
If they are not installed, follow the instructions [here](https://nodejs.org/en/).

```
# Check for node
$ node -v
v12.14.0
```

```
# Check for npm
$ npm -v
6.13.4
```

```
# Check for npx
$ npx -v
6.13.4
```

2. Install the [gulp](https://gulpjs.com/) command line utility
```
$ npm install --global gulp-cli
```

### 1. Install

```
$ git clone git@github.com:deren2525/gulp4-html-scss-ts-template.git
$ cd gulp4-html-scss-ts-template
$ npm install
```

Verify your gulp versions
```
# Check for gulp
$ gulp -v
CLI version: 2.2.0
Local version: 4.0.2
```
### 2. Start
```
# start
$ gulp
```
Go to [http://localhost:3000](http://localhost:3000/) !
