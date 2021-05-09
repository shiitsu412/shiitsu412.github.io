---
layout: essay
type: essay
title: Checkpoint Assignment #3
# All dates must be YYYY-MM-DD format!
date: 2021-05-06
labels:
  - Education
  - Learning
--- 

<strong>Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype</strong>

This is the link that indicates how each page will look like:
https://drive.google.com/file/d/1wNEE9IT4vrD2861MT-Y3UB60_Lml3acy/view?usp=sharing
Also, this is the link to my brief explanation video about my web page:https://youtu.be/ua6ZCnMh26s


<strong>Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.</strong>

The shopping cart will be on separate pages. 
I will display the product quantity that users selected in the shopping cart and ask them to checkout or keep shopping for each product.



<strong>Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.</strong>

I will use session ID to manage users' data. 
I will use this code to manage the shopping cart data.

var products_data;
        loadJSON('get_products_data', function (response) {
            // Parsing JSON string into object
            products_data = JSON.parse(response);
        });
        loadJSON('get_cart', function (response) {
            // Parsing JSON string into object
            shopping_cart = JSON.parse(response);
        });


<strong>How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</strong>

I will give users their own session-id to manage their product data. 
I will send cookie to check whether users are loging in or not. Also, I will set the time limit of how long users can keep login in.


<strong>Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)</strong>
I will send users a message with their usename, for example, Thank you for Shopping, Airi! Almost done! Please confirm your order for the last step! 

<strong>If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? 
</strong>

I am working on assignment 3 by myself.


<strong>7. Describe what worked well with this project? What did not work well?</strong>

I worked well with this project to create a CSS file for each login and register page, save user data on my server, and connect the login page to the invoice page. 
I worked not well with this project to connect the login page and register page, and send data of product quantity entered in the display page whenever move to other pages.


<strong>How are you approaching Assignment 3 differently than Assignment 2?</strong>

I am paying more attention and effort to solve problems as soon as possible when the problems are still simple.
Also, I am trying to start work on it earlier than assignment2 to be able to spend more time on assignment3. 
