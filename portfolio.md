# git

git remote add origin
git push -u origin master

# VS code

code . / code ..

# NPM

- Nowy projekt -> tworzy plik package.json

npm init -y 
sudo npm i sass -D

### package.json 

- uzupelnic authora
- license -> Beerware (stwiasz piwo jak spotkasz autora,mozesz uzywac)

# Project structure

- dist
- src (css, fonts, images, scripts, scss)

- index.html


├── README.MD
├── dist
├── index.html
├── package.json
└── src
    ├── css
    ├── fonts
    ├── images
    ├── scripts
    └── scss

# Emmet

https://docs.emmet.io/cheat-sheet/

# JS

<script src="./src/scripts/app.js" async defer></script> w HEAD

# SASS

- Transpilacja - transformation & compilation (SCSS -> CSS)
sass ./src/scss/main.scss ./src/css/styles.css -> Global SASS
node ./node_modules/.bin/sass ./src/scss/main.scss ./src/css/styles.css -> local SASS

package.json -> scripts -> "dev": "node ./node_modules/.bin/sass ./src/scss/main.scss ./src/css/styles.css --watch" -> obserwowaie zmian i kompilacja css

npm run dev -> uruchomienie deamona


#{$} - interpolacja

# CSS

HEAD before JS

<link rel="stylesheet" href="./src/css/styles.css">


# HTTP

200 - wszystko ok
304 - bez zmian
404 - blad

Sources - do modyfikacji kodu live

# Stalguide -> storybook


