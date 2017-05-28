# Documentation-of-deployment-to-Heroku
### Documentation of how to deploy CoAXs to Heroku

### 1 Clone the CoAXs repo from github 

### 2 Install dependencies 
```sh
npm install
```

### 3 Build and compile production code
The package build and compile tool Webpack will help you compress and output production code in public folder. 
```sh
$ npm run build-prod
```

### 4 Add, commit and push to your own github repo
```sh
$ git add .
$ git commit
$ git push
```

### 5 Link heroku with github repo and then delopy
finally, open the heroku dashboard and click deploy tab

Choose github in "Deployment method" and then find your repo and branch

click "Deploy Branch" button.

![Heroku screenshot](https://github.com/mitTransportAnalyst/Documentation-of-deployment-to-Heroku/blob/master/heroku%20screenshot.png "Heroku screenshot")

