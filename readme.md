
# Snake Queer - Vanilla JS
## Famous snake game with trans flag colors :)
[Démo du Snake ici](https://shayreichert.github.io/snake_trans/)
[![Snake Trans Queer](screen_snake.png) ](https://shayreichert.github.io/snake_trans/)

## Built With

* [Vanilla JS](http://vanilla-js.com/) - The best JS framework


















////////
MEMO pour lancer Sass depuis son éditeur de code :

- Créer un package.json :
```
npm init
```
- Installer Sass si nécessaire : 
``` 
npm install sass -g 
``` 
puis pour vérifier que l'installation est ok (doit retourner un numéro de version) :
``` 
sass --version 
``` 

- Ajouter le script Sass au fichier .json :
``` 
"scripts": {
  "sass": "sass --watch ./css/style.scss:./css/style.css"
}, 
```

- Enregistrer le fichier .json, puis lancer Sass avec :
``` 
npm run sass
```
