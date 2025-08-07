

-> pakage.json 
-> "homepage": "https://hollolo123.github.io/scss_overwatch/"

npm i gh-pages --save-dev <br>
=> pakage.json  "gh-pages": "^6.3.0" 확인<br>

"scripts": {<br>
    "dev": "parcel index.html",<br>
    "build": "parcel build index.html -d build",<br>
    "predeploy": "npm run build",<br>
    "deploy": "gh-pages -d build"<br>
  }

  npm run deploy<br>
