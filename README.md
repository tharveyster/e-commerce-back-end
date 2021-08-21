# E-Commerce Back End

## Description

## Walkthrough Video

## Installation
To install necessary dependencies run the following command in the root of your project:
```bash
npm i
```

To create the database schema run the following command from a mysql prompt:
~~~~sql
source db/schema.sql
~~~~

To seed the database, exit from the mysql prompt and run this command:
```bash
npm run seed
```

## Usage
To launch the app run the following commands in the root of your project:
```bash
npm start
```

To run the test routines, you'll need Insomnia Core. The following information explains how to test the application using Insomnia Core.

To test the **get all categories** route, use the GET method and the following URL:
```bash
localhost:3001/api/categories/
```

To test the **get category by id** route, use the GET method and the following URL:
```bash
localhost:3001/api/categories/2
```

To test the **create category** route, use the POST method and the following URL:
```bash
localhost:3001/api/categories/
```
Then use the following JSON data as the body:
```bash
{
  "category_name": "Sporting Goods"
}
```

To test the **update category by id** route, use the PUT method and the following URL:
```bash
localhost:3001/api/categories/5
```
Then use the following JSON data as the body:
```bash
{
	"category_name": "Footwear"
}
```

To test the **delete category by id** route, use the DELETE method and the following URL:
```bash
localhost:3001/api/categories/3
```

To test the **get all tags** route, use the GET method and the following URL:
```bash
localhost:3001/api/tags/
```

To test the **get tag by id** route, use the GET method and the following URL:
```bash
localhost:3001/api/tags/5
```

To test the **create tag** route, use the POST method and the following URL:
```bash
localhost:3001/api/tags/
```
Then use the following JSON data as the body:
```bash
{
	"tag_name": "orange"
}
```

To test the **update tag by id** route, use the PUT method and the following URL:
```bash
localhost:3001/api/tags/7
```
Then use the following JSON data as the body:
```bash
{
	"tag_name": "purple"
}
```

To test the **delete tag by id** route, use the DELETE method and the following URL:
```bash
localhost:3001/api/tags/2
```

To test the **get all products** route, use the GET method and the following URL:
```bash
localhost:3001/api/products/
```

To test the **get product by id** route, use the GET method and the following URL:
```bash
localhost:3001/api/products/1
```

To test the **create product** route, use the POST method and the following URL:
```bash
localhost:3001/api/products/
```
Then use the following JSON data as the body:
```bash
{
  "product_name": "Basketball",
  "price": 200.00,
  "stock": 3,
  "category_id": 6,
  "tagIds": [6, 7, 9]
}
```

To test the **update product by id** route, use the PUT method and the following URL:
```bash
localhost:3001/api/products/5
```
Then use the following JSON data as the body:
```bash
{
  "product_name": "Bermuda Shorts",
  "price": 24.99,
  "stock": 15,
  "category_id": 2,
  "tagIds": [4, 5, 6]
}
```

To test the **delete tag by id** route, use the DELETE method and the following URL:
```bash
localhost:3001/api/products/2
```

## Questions
If you have questions about this repo, open an issue or contact me directly at todd@theharveysplace.com. You can find more of my work at [tharveyster](https://github.com/tharveyster).

## License
ISC