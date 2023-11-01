# Bootstrap w/ Vite - update: 01/11/2023

Include [Bootstrap](https://getbootstrap.com)'s source Sass and individual JavaScript plugins with [Vite](https://vitejs.dev/).

## How to use

```sh
git clone https://github.com/twbs/examples.git
cd examples/vite/
npm install
npm start

or npm run build (To create production files in the /dist directory.)
```

## Main features

> In the src/scss/main.scss file, imports of what will be used in the project were made. The intention is to optimize the project's auto reload by loading only the components or plugins that will be used. Leaving it lighter. The same was done with main.js. Make necessary changes to these files for this optimization purpose.

> Use of scss and bootstrap variables to change the theme, spacing and some components as an example.