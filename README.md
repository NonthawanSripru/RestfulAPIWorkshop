# Restful API Workshop

### Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Vue project Create All Default selected
```
vue create vpower  
cd vpower
vue add vuetify
vue add router
```
Create .eslintignore files
```
/build/**
/coverage/**
/docs/**
/jsdoc/**
/templates/**
/tests/bench/**
/tests/fixtures/**
/tests/performance/**
/tmp/**
/tools/internal-rules/node_modules/**
/lib/rules/utils/unicode/is-combining-character.js
test.js
!.eslintrc.js
/src/**
```
add Axios
```
vue add axios
```

### Compiles and minifies for production
```
npm run build
```

### Create API
```
npm install --save json-server
npm run json:server
```

### Create db.json file
```
npm install --save json-server

Create a db.json file with some data

{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```
### Start JSON Server

```
json-server --watch db.json
```

