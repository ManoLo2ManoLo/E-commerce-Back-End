# E-commerce Back End Starter Code

## Link(s)
Link to Video: https://watch.screencastify.com/v/97IBq8vpmfRbBWmo82xe

## Table of Contents (Optional)
* [Description](#description)
* [Clone Repository](#clone-repository)
* [Install Dependencies](#install-dependencies)
* [Start Application](#start=application)
* [Screenshots](#screenshots)
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

## Clone Repository
* git clone https://github.com/ManoLo2ManoLo/E-commerce-Back-End.git

## Install Dependencies
* All NPM packages required for this application (bcrypt, connect-session-sequelize, dotenv, express, express-handlebars, express-session, mysql2, sequelize) are already listed as dependencies in the package.json file. Run the
command 'npm i' command in your terminal at the root directory level to install the packages.
* Ensure you have Node.js installed on your machine. The budget tracker application will be invoked by entering node server.js in the command line.

## Start Application
* You will see the App running on port 3001! in the console. You can then view the app on http://localhost:3001/.

## Screenshots
List of Categories: <br />
![Screenshot (445)](https://user-images.githubusercontent.com/88364269/143662297-c6a9c8bc-b2c5-4504-838d-9c578c3ec257.png)

Category by Id: <br />
![Screenshot (446)](https://user-images.githubusercontent.com/88364269/143662298-2260148b-206a-4796-b9a9-4a5d8df93474.png)

List of Products: <br />
![Screenshot (447)](https://user-images.githubusercontent.com/88364269/143662299-7ed22318-c982-458c-b773-19983dec0d03.png)

Product by Id: <br />
![Screenshot (448)](https://user-images.githubusercontent.com/88364269/143662300-c227697e-acf1-4db8-954c-b599d2ad81b8.png)

List of Tags: <br />
![Screenshot (449)](https://user-images.githubusercontent.com/88364269/143662301-b742d52a-0b8d-4670-9c0f-27be8c7d4620.png)

Tag by Id: <br />
![Screenshot (450)](https://user-images.githubusercontent.com/88364269/143662302-0628e6bf-1f49-4ae4-b4ed-0faddb5f79ae.png)

## Credit
The starter code for Note Taker was created by Rutgers' Coding Bootcamp, and was edited and revised Manuel Canas-Menendez (ManoLo2ManoLo). <br />

* [Github](https://github.com/ManoLo2ManoLo)
* [Portfolio](https://manolo2manolo.github.io/React-Portfolio/)
* [LinkedIn](https://www.linkedin.com/in/manuel-canas-menendez-33354b21b/)

## License
<p align="center">
    <img align="center" src="https://img.shields.io/github/license/ManoLo2ManoLo/Coding-Quiz?style=for-the-badge" alt="license" />
</p>