# LAB - 06 

## Simple API

### Author: Alvian Joseph

### Links and Resources
* [submission PR](https://github.com/alvian-401-advanced-javascript/simple-api)
* [Front-end](https://codesandbox.io/s/w638oyk7o8)
* [Swagger Hub](https://app.swaggerhub.com/apis/AlvianJoseph/default-title/0.1)


### Command to add data to server  
```echo '{"id": number, "description":"string","display_name": "string", "string":"text"}' | http post :3000/categories```

#### REST methods
* `/categories GET, POST`  

  GET Responds with all categories
* `/products GET, POST`  

  GET Responds with all products
* `/categories/:id/ PUT, DELETE`  

  Requires id in path, PUT updates a given category
  Requires id in path, DELETE deltes a given category
* `/products/:id/ PUT, DELETE`  

  Requires id in path, PUT updates a given product
  Requires id in path, DELETE deltes a given product


### Documentation
* [swagger.json](https://github.com/alvian-401-advanced-javascript/simple-api/blob/json-server/docs/swagger.json)
* Generated using `swagger`.


#### Running the app
* `json-server --watch data/db.json` in terminal
* Go to `https://codesandbox.io/s/w638oyk7o8`
* Categories and their corresponding products should display when a category is clicked:

#### Tests
N/A
