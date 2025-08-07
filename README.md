

-> pakage.json 
-> "homepage": "https://hollolo123.github.io/scss_overwatch/"

npm i gh-pages --save-dev
=> pakage.json  "gh-pages": "^6.3.0" 확인

"scripts": {
    "dev": "parcel index.html",
    "build": "parcel build index.html -d build",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }

  npm run deploy
