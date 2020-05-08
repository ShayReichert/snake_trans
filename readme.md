# Creer un package.json et lancer un script sass

Créer un package.json : npm init
    (installer sass : npm install sass -g puis sass --version)

Définir un script Sass :
"scripts": {
  "sass": "sass --watch ./css/style.scss:./css/style.css"
},

Enregistrer, puis lancer Sass 
npm run sass


