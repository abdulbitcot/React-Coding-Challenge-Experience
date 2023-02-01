# React Coding Challenge

> Welcome to the React Coding Challenge!

## Overview
To complete this challenge, you will need to write a simple React based web app, and provide us the source files to be built.
The purpose of this challenge is to assess your skills and approach to composing a simple web app given a set of screens and an API feed. We will also assess the generated HTML, CSS, and JS output.
The Challenge
It's pretty simple. Using the provided screens as a reference, you'll need to build a set of React components to render the app. You'll also need to request a JSON feed, filter that data, and use the relevant fields.
Although this is a basic exercise, we'll be looking for simple, well-designed, performant, and tested code in the submission.

## Details

Convert the HTML into REACT JS then Implement the redux in this project and then create Public and Private (Routes / Layout ).

Link of HTML : [HTML] (https://facebook.github.io/react/)

You will need to build the following 4 pages with React:
- A "Login" page
- A "Product List" page
- A "Add Product" page
- A "Edit Product" page

The deployable solution should be built in a folder named dist with an entry point file of index.html.
Please create components for each part of the page (eg. header, content, footer, etc). Assets are provided in the assets folder.
The pages should also be usable on mobile and tablet devices.
You can assume that you do not have to support legacy browsers without features such as fetch or flexbox.
Login page : 
In the Login page you have to show login screen and in that LogIn screen there are two inputs, one for email and one for password and one button for sign In and also add validation for both fields. User fill this with any Email and password then the token is generated statically and saved in local storage. 
Once user login it will be redirect to Product list and if token is in local storage then it will not be able to come to login page 
And with the help of token you can manage public and private routes.


## Product List page

For this page you will need to fetch this JSON feed , then:   
Save the Product list in the reducers Initialstate
Display product list.
Add Searching functionality  by product name or category Locally
There is a Delete Button in the list and onClick of the delete button product should be deleted.
There is an Edit Button in the list and onClick of the Edit button .Product should be redirected to the Edit page and form will be filled by selected  product data.
There is a Button of Add Product and on click the page is redirected to Add product page.


## Add Product

Add Tab of general and variation.
Add validation of all the required fields.
In the variant tab We can add multiple variants.
After submitting the product then the product should be added in the product list locally in the reducers.


## Edit Product

When Product should be redirected to the Edit page from the product list then  form will be filled by selected  product data. 
User can Edit Product and Submitted by button and then it will be reflected in the product list.
Also maintain the validation in edit form. 