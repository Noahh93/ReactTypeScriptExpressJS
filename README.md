# ReactTypeScriptExpressJS
This is ExpressJS with TypeScript Fixxo Website. MongoDB


>>>> Här är API för Product CRUD, med denna text kan man utföra CRUD API på postman <<<<

1. Gå till ExpressJs folder by running command cd expressjs
2. Kör command "node index.js" i command terminalen



add product
POST  http://localhost:5000/products

{
"id": "1",
"name": "Laptop",
"description": "Laptop description",
"price": 400,
"imageName": "laptop.png",
"category": "Electronics",
"articleNumber" :"a1234"
}

{
"id": "2",
"name": "Iphone",
"description": "Iphone description",
"price": 250,
"imageName": "iphone.png",
"category": "Electronics",
"articleNumber" :"a12345"
}

{
"id": "3",
"name": "Jeans",
"description": "Jeans description",
"price": 750,
"imageName": "jeans.png",
"category": "Clothes",
"articleNumber" :"a123456"
}

{
"id": "4",
"name": "T-shirt",
"description": "T-shirt description",
"price": 123,
"imageName": "tshirt.png",
"category": "Clothes",
"articleNumber" :"a1234567"
}

retrieve record from API
GET   http://localhost:5000/products

update record from API by ID
PUT  http://localhost:5000/products/6420a9b783f155ccfcae974e

{
"id": "3",
"name": "Jeans updated",
"description": "Jeans description",
"price": 750,
"imageName": "jeans.png",
"category": "Clothes",
"articleNumber" :"a123456"
}

Delete product by ID
DELETE http://localhost:5000/products/6420aa2083f155ccfcae9753

Retrieve product by ID
GET http://localhost:5000/products/6420a9b783f155ccfcae974e


Frontend applicaton react with Typescript 
//React_Typescript\OlldReactWebsite

1. För att köra programmet först gå till "React_Typescript\OlldReactWebsite" folder
2. Run npm start
3. Gå till products menu, här kommer alla produkter från expressJS API

