# INM320 Assignment 3: CSS Precompiler (Sass)

## Setup
    npm install
    npm run dev          # watches SCSS (recompiles on save) and serves /public at http://localhost:8080
    npm run sass:build   # one-off compile

Source: `src/scss/style.scss` -> Output: `public/assets/css/style.css`
(`public/index.html` links `/assets/css/style.css`, so the dev server root is `public/`.)
