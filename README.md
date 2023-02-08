# React Coding Challenge

> Welcome to the React Coding Challenge!

## Overview

To complete this challenge, you will need to write a simple [React](https://facebook.github.io/react/) based web app, and provide us the source files to be built.

The purpose of this challenge is to assess your **skills and approach to composing a simple web app** given a set of screens and an API feed. We will also assess the **generated HTML, CSS, and JS** output.

## The Challenge

Using the provided screens as a reference, you'll need to build a set of React components to render the app. You'll also need to request a JSON feed, filter that data, and use the relevant fields.

Although this is a basic exercise, we'll be looking for **simple, well-designed, performant, and tested code** in the submission.

## Details

Convert the  **HTML** into **REACT JS** then Implement the redux in this project and then create Public and Private (Routes / Layout ).

- Click on [**HTML**](https://github.com/abdulbitcot/React-Coding-Challenge-Experience/raw/main/HTML.zip) to download HTML
- Add dropdown functionality in sidebar
- Add toggle functionality in sidebar

You will need to build the following 5 pages with React:
- "Sign Up" page
- "Login" page
- "Product List" page
- "Add Product" page
- "Edit Product" page


Please create components for each part of the page (eg. header, content, footer, etc).
Assets are provided in the `assets` folder.

The pages should also be usable on mobile and tablet devices.

You can assume that you do not have to support legacy browsers without features such as `fetch` or `flexbox`.

### "Sign Up" Page

- Add validation in all fields
- When user fill all the fields and click on **Sign up** button then data should be save in your `localStorage` and `reducer` then redirect to login page

**Note:** User can create multiple users

### "Login" Page

- Add validation in email or password field. In the email field, you will have to add email validation
- When user submit **login** form,  you have to retrieve **email** and **password** from your reducer which you saved during **Sign up**.
- After submit login form the token will we generated statically and saved in `localStorage` and `reducer`.
- Once user have loged in than it will be redirect to the **Product list** and if token is in `localStorage` than it will not be able to come to login page 

**Note:** With the help of static token you can manage public and private routes.

### "Product List" Page

For this page you will need to fetch this JSON [sample.json](https://raw.githubusercontent.com/abdulbitcot/React-Coding-Challenge-Experience/main/sample.json) feed 

- Save the Product list data in the reducer's Initialstate
- Display product list.
- You can display product **image** in the `variation` array key from the `0` index
- You can display product **price** in the `variation` array key from the `0` index
- You can display product **stock** in the `variation` array key from the `0` index
- Add Searching functionality by **Product name** or **Category** Locally
- There is a Delete Button in the list and on `Click` of the delete button, The Product should be delete.
- There is an Edit Button in the list and on `Click` of the Edit button. The Product should be redirecte to the Edit page and form will be filled by selected  product data.
- There is a Button of **Add Product** and When **Click** the page will be redirecte to the **Add Product** page.


### "Add Product" Page

- Add **Tabs** functionality of `general` and `variation`.
- Add validation of all the required fields.
- In the **variation** tab, We can add multiple variants.
- Atleast one **variation** is required.
- After submitting the product than the product should be add in the product list locally in the reducers and display in product list.


### "Edit Product" Page

- When Product will be redirected to the **Edit Page** from the product list than **form** will be filled by selected product data. 
- User can Edit Product and After Submitted, it will be reflected in the product list.
- Also maintain the validation in edit form.