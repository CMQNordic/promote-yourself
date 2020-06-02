# Final version project: __Promote Yourself__

### The course at Udemy teaching vue, nuxt and mongo

### Course: [The Complete Nuxt.js & Vue.js Course](https://www.udemy.com/course/the-complete-nuxtjs-vuejs-course-self-promo-app/)


## Before running:
Set up connection to your MongoDB:  
For more info how to do it please watch lectures:  
122 - DB Setup  
123 - Server Setup  
124 - Populate Data to DB
``` bash
# navigate to folder server->keys

Here connection to db must be set in order for the app to work

in dev.js set username and password:
martin@__xxx__
Minc__xxx__
```

In case of new db:
``` bash
# navigate to folder server->dbNocs

Populate the server by running:
>node seedDb.js

Then data in data.js will written to db
```
To det products:
```
http://localhost:3000/api/v1/products
```

## Build Setup

``` bash
# install dependencies (if node_modules folder is missing)
$ npm run install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).
