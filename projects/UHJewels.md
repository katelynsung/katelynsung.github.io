---
layout: project
type: project
image: img/dropbracelet.JPG
title: "UH Jewels"
date: 2024-12-15
published: true
labels:
  - ICS314
  - Bootstrap
  - HTML
  - CSS
  - Business
summary: "UH Jewels"
---

# UH Jewels  [![ci-nextjs-application-template](https://github.com/UH-Jewels/uh-jewels-application-template/actions/workflows/ci.yml/badge.svg)](https://github.com/UH-Jewels/uh-jewels-application-template/actions/workflows/ci.yml)
<a href="https://github.com/UH-Jewels">View our organization on GitHub</a>

## Table of Contents

* [Overview](#overview)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development](#development)
* [Team Contract](#team-contract)
* [Team](#team)

## Overview
I wanted to create a small business for fun creating my own handmade jewelry. In my ICS 314 class I decided to implement my website project to be showcasing my pieces and format it as a working 'jewelry ecommerce site'. My teammates [Jarren Seson](https://github.com/jarrenseson), [Waltz Tuzon](https://github.com/waltz-axl-c-tuzon) and I worked on developing the working application together. Using VSCode and Github as our main platforms, our team learned how to connect inputted data from our website to our local database using pgAdmin. We ran this application through Vercel.  

Consumers are able to login, make an account and shop for their new pieces. Our local database allows us as the owner to see what orders each user has placed, and from there on can ship and finish up the ordering process on the business side. 

## User Guide

### Home Screen

Welcome to the UH Jewels Homescreen! 

<img width="1706" alt="Screenshot 2024-12-15 at 1 11 25 PM" src="https://github.com/user-attachments/assets/ecc75a43-21b9-422b-8e06-980e5fd55107" />


When you click the button 'Shop Jewels' it will be prompting the user to login in or make an account. That way all of their information and the products they add will be under the same name in the database. 

### Instagram
When logged in, users can click the button on the top left which takes you to our instagram page.

<img width="1431" alt="Screenshot 2024-11-21 at 4 59 31 PM" src="https://github.com/user-attachments/assets/c0b86896-d328-4bcf-b29a-cdbe40f23927">

### Customer Login page

<img width="1708" alt="Screenshot 2024-12-15 at 1 12 25 PM" src="https://github.com/user-attachments/assets/53cdccdd-1f47-49b4-b341-de9b84a5b6a0" />


Just sign in create an account with your email and a password.

After logging in, it will take you to back to the home page with a Shop Jewels tab. As a user you can either view the products by clicking the 'Shop Jewels' button or click the tab in the Nav bar. 
<img width="1710" alt="Screenshot 2024-12-15 at 1 13 55 PM" src="https://github.com/user-attachments/assets/e1c89bcf-9002-4eb2-9766-7d592b89c8cd" />


### Products Page

Here you can view the pieces that are listed, viewing the prices and styles available. 
<img width="1704" alt="Screenshot 2024-12-15 at 1 15 03 PM" src="https://github.com/user-attachments/assets/1925c40b-2033-4b79-a603-0ff4a49af2e0" />


### Add To Cart
To select the products that you want to purchase, simply click 'add to cart' on the products that you want and it'll update your shopping cart.

### Shopping Cart Page

<img width="1705" alt="Screenshot 2024-12-15 at 1 15 52 PM" src="https://github.com/user-attachments/assets/2d984211-01c0-4363-9bbf-2109bcf41f79" />
The shopping cart page which can be accessed through the Navbar cart logo or the 'proceed to cart' button will show you to your updated cart and its total.
Users are also able to edit their cart by removing or adding the quanitity. 
Click the 'Proceed To Payment' Button which will take you to the payment page.

### Edit Cart Items Page

![Screenshot 2024-12-15 161149](https://github.com/user-attachments/assets/ad60f0c8-2811-4caf-a799-53ae6f37e96d)
This page allows you to edit the quantity of a product.

### Payment Page
<img width="1705" alt="Screenshot 2024-12-15 at 1 18 56 PM" src="https://github.com/user-attachments/assets/5e08bcb2-4218-4094-b2bb-34aeafc06040" />


Complete all the information with your choice of payment. And when finished, click the 'Continue to Shipping Form'

### Shipping Page

Enter your shipping information so we can ship your jewels to your door!

<img width="1706" alt="Screenshot 2024-12-15 at 1 21 40 PM" src="https://github.com/user-attachments/assets/79a47a03-d92c-42aa-a6ab-a262b1b2aa2f" />

The data inputted will be written into our database and your order will be submitted!

### Admin Access

As an administrator, there is an admin exclusive access.
Simply login with the admin email account. 

<img width="1704" alt="Screenshot 2024-12-10 at 11 58 49 AM" src="https://github.com/user-attachments/assets/818170fd-aace-4db9-8304-6d32922e2041">
<img width="1707" alt="Screenshot 2024-12-15 at 1 24 15 PM" src="https://github.com/user-attachments/assets/a380dfcc-e414-47a2-9374-f46eb7f23b57" />

This access redirects you to the home page with a exclusive 'List New Products Tab"


Simply list a new products to release onto the site!
<img width="1703" alt="Screenshot 2024-12-15 at 1 26 50 PM" src="https://github.com/user-attachments/assets/30b1a158-bf5a-4853-80dd-2c55cc457d58" />

The newly listed product will immediately be listed and update on the 'Shop Jewels' page for the public.
<img width="1710" alt="Screenshot 2024-12-15 at 1 27 09 PM" src="https://github.com/user-attachments/assets/c1d3e09a-1008-4969-b43e-ff2523d81965" />
<img width="1710" alt="Screenshot 2024-12-15 at 1 27 21 PM" src="https://github.com/user-attachments/assets/7292c2bb-bbac-4d45-b2ee-8d81c63b2e0f" />


### The new product is updated to the public as a customer is logged into their account

<img width="1710" alt="Screenshot 2024-12-15 at 1 29 31 PM" src="https://github.com/user-attachments/assets/1700ba1d-ca58-45bb-90cb-c53831744cf0" />

## Community Feedback

After getting responses from the UH community, many were excited and showed high interest in the products. The visualization and the design of the website was complimented to be trendy to the young adult audience. One suggestion that a few mentioned were not being used to having a button keep taking them to the next page in order. While this was made to make the shopping experience easier, a few people said they like the old style of just having different logos that would take them to other pages. We did implement the usage of both. Another suggested the usage of videos and more images of the products to be incorporated. Such as the usage of 'models' and how the pieces were styled. The logo was also said to be too small it gave some confusion on the brand name. Majority of the suggestions were more about the products and commercializing rather than the actual design of the webiste. Overall, majority enjoyed and thought the webiste was self explanatory. 
## Developer Guide

This section provides information of interest to developers wishing to use this code base as a basis for their own development tasks. 

### Installation

Visit the [UH Jewels application github page](https://github.com/UH-Jewels/uh-jewels-application-template), and click the "Use this template" button to create your own repository initialized with a copy of this application. 

Then, cd into the uh-jewels-application-template/app directory and install libraries with:

```
$ npm install
```
Third, run the system with:
```
$ npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).


## Deployment 

Click [here](https://uh-jewels-application-template-fork.vercel.app) to see our Vercel deployment.

## Development

### Milestone 1: Mockup Development

The goal of milestone 1 was to create a set of HTML pages providing a mockup of the pages in the system.
Milestone 1 was managed using [UH Jewels GitHub Project Board M1](https://github.com/orgs/UH-Jewels/projects/2/views/1?filterQuery=). 

### Milestone 2
The goal of milestone 2 was to significantly improve the functionality and quality of our application. Milestone 2 was managed using [UH Jewels GitHub Project Board M2](https://github.com/orgs/UH-Jewels/projects/3/views/1)

### Milestone 3
The goal of milesstone 3 was to signicantly improve the functionality of our system from milestone 2, incorperate a significant amount of "real" data into our system, and implement acceptance testing. Milestone 3 was managed using [UH Jewels GitHub Project Board M3](https://github.com/orgs/UH-Jewels/projects/4)

## Team Contract
View our team contract [here](https://docs.google.com/document/d/1dADF0u-a7cH049eyQP-dMeUer1EFkaykC__uFOfFstg/edit?tab=t.0).

## Team

UH Jewels is designed, implemented, and maintained by [Katelyn Sung](https://github.com/katelynsung), [Jarren Seson](https://github.com/jarrenseson), and [Waltz Tuzon](https://github.com/waltz-axl-c-tuzon).
