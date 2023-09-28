### Node-Express-Sass-Ejs-Starter Entwicklungsumgebung

### `node` `express` `sass` `ejs` `express-ejs-layouts` `concurrently` `nodemon` `livereload` `prettier`

> node v18.17.1

> Framework: express

> Template Engine: ejs

## Installation

> CMD: Projektordner erstellen und hinein wechseln

    mkdir Name; cd Name

> **Schnellstart**

> CMD: git clone & git remote remove orgin & npm install & npm run dev

    git clone https://github.com/tBrause/npm-express-sass-livereload-ejs.git .; git remote remove origin; npm install; npm run dev

> \_Erfolgreich getestet: 15.09.2023

## Struktur und Dateien

- bin
  - www
- public
  - stylesheets
    - style.css
    - style.css.map
  - favicon.svg
- routes
  - index.js
- src
  - scss
  - globals
    - \_index.scss
    - \_reset.scss
    - \_variables.scss
  - main.scss
- views
  - index.ejs
- .gitignore
- app.js
- package-lock.json
- package.json
- prettier.config.cjs
- README.md

## Konfiguration

### scripts

- dev: nodemon, sass
- start: node

### dependencies

- cookie-parser
- debug
- express
- http-errors
- morgan
- ejs
- express-ejs-layouts

### devDependencies

- concurrently
- nodemon
- sass
- livereload
- connect-livereload

## Erweiterungen für Visual Studio Code

- Prettier
- ESLint
- EJS Language Support
