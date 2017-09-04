---
title: Installation Instructions
date: 2017-08-25 06:40:12
---

# ArialShop - Vue2.0 + Node + Mongo

### Single page progressive e-commerce app using VueJS.

## Softwares
> Make sure you have [**Node**](https://nodejs.org/en/) version >= 8.0, **NPM** >= 5 and [**MongoDB**](https://www.mongodb.com/)

Download and unzip the file from **codecanyon**

### navigate inside the directory
```bash
cd arialshop
```

## Start dev server
### Start mongodb in a separate shell

Try-1: `npm run database`

Try-2: In Windows operating system we can start it by opening the following file

```bash
C:/Program Files/MongoDB/Server/3.2/bin/mongod.exe
```

1. Open another terminal (command prompt)

2. install the dependencies with npm
`npm i`

3. serve with hot reload at localhost:8080
`npm run dev`

4. build for production with minification
`npm run prod`

5. build client for production and view the bundle analyzer report
`npm run build --report`

## Deploy to Heroku

1. Run command `npm run prod` 

2. Install mLab heroku addon
```
heroku addons:create mongolab
```

3. Upload everything inside dist directory to Heroku

4. Run command `npm i --production`

5. Check heroku logs `heroku logs --tail` for any error
