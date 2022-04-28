# E-commerce Back End Starter Code

## Link Section
Link to Github Repository: https://github.com/ManoLo2ManoLo/E-commerce-Back-End.git
Link to Video: https://watch.screencastify.com/v/97IBq8vpmfRbBWmo82xe

## Table of Contents (Optional)
* [Description](#description)
* [Credits](#credits)
* [License](#license)

## Description
This application is for a store to keep track of their interventory. They are able to view, add, or delete products, categories, with an application called Insomia. If you view categories, you will see a list of all the categories with the products that belongs to that product. If you view products, you can see the products with their price, stock, catefory they belong to, and list of tags that belongs to it. If you view tags, you will see the tags, with a list of products that belongs to the tag. You are also able to add a category name in a json in the text, with just the category name looking like:
```
{
    "category_name": "Shirts"
}
```
You are able to add a product name the same way with the product name, price, stock, tag id (optional), and category id (optional) looking like:
```
{
    "product_name": "Plain T-shirt",
    "price": 14.99,
    "stock": 14,
    "category_id": 1,
    "tagIds": [6, 7, 8]
}
```
You are able to add a tag by just adding the tag name looking like: 
```
{
    tag_name: "rock music"
}
```
The user will also be able to update a product, category, or tag with their table, id and a json text similar to the what is above with the updated information. Similarly with the link to the table and id, you are able to delete things idividually.

## Screenshots
List of Categories:
![Screenshot (445)](https://user-images.githubusercontent.com/88364269/143662297-c6a9c8bc-b2c5-4504-838d-9c578c3ec257.png)

Category by Id:
![Screenshot (446)](https://user-images.githubusercontent.com/88364269/143662298-2260148b-206a-4796-b9a9-4a5d8df93474.png)

List of Products:
![Screenshot (447)](https://user-images.githubusercontent.com/88364269/143662299-7ed22318-c982-458c-b773-19983dec0d03.png)

Product by Id:
![Screenshot (448)](https://user-images.githubusercontent.com/88364269/143662300-c227697e-acf1-4db8-954c-b599d2ad81b8.png)

List of Tags:
![Screenshot (449)](https://user-images.githubusercontent.com/88364269/143662301-b742d52a-0b8d-4670-9c0f-27be8c7d4620.png)

Tag by Id:
![Screenshot (450)](https://user-images.githubusercontent.com/88364269/143662302-0628e6bf-1f49-4ae4-b4ed-0faddb5f79ae.png)

## Credit
The starter code for Note Taker was created by Rutgers' Coding Bootcamp, and was edited and revised by Manuel Canas-Menedez to meet an assignment requirements.

## License
MIT License

Copyright (c) 2021 Manuel Canas-Menendez

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
