---
layout: essay
type: essay
title: "Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2024-12-04
published: true
labels:
  - computer science
  - design patterns
  - websites
---


The usage of Design patterns are not that well known. Whether its a kid playing a game on their Ipad, to a student logging into their social media apps, a design pattern was created behind the scenes in order to get a usable solution. 

These are important as a software engineer because it "improves the quality of code, speed up development, and make collaboration easier"



<img width="913" alt="Screenshot 2024-12-04 at 2 43 28 PM" src="https://github.com/user-attachments/assets/fa83f7ae-befc-43da-b970-286cbadaa692">



Design patterns are a general and reuasable solution to a commonly occuring problem in software design. These are represented by a template that can be used for many different situations. Design patterns are often described by a Name, Problem Description, Solution Description, and The Consequences of the proposed design pattern. The consequence is usually about the downsides and risks of that style. An Object Oriented Design pattern consists of a few differnt types: Creational Patterns, Structural Patterns, and Behavior Patterns.

Design patterns can stretch from User Interface, Database Systems, Real Time systems, Testing, Architecture, Software Processes, Language Specific (C++, Java, JS, etc). The most common examples would be Factory, Singleton, Observer, MVC. 

Our website used Front Controller Design pattern which is a centralized request handelling mechanism. takes the user to login or sign up on the front end. On our system we implemented it so that once the user logs in it goes to a specifc home page. 

Singleton pattern is also used with the variable "Jewels" is the singleton instance of the OurProducts class. The users details are connected to the database. 
The usage of Factory design patterns is also shown where it returns the id for each individual product. 

For my personal project I wanted to create a website where I can have users shop and purchase my handmade jewelry. During the summer I came up with a few ideas and wanted to make some necklaces with a lot of materials that I foraged. The personal plan didn't follow through but when I found out that in my ICS314 class we needed to create a website as our final project, I proposed the idea to my teammates and I to create a real working ecommerce website. 

This whole project from the images to the products was created by my team and I so I thought it was really fun being able to use my own images and see it on the website. 

For this website we have the home screen prompting the user to log in or to make an account. This is an example of the Front Controller Design pattern, redirecting the user to the login page and handeling that request. After the user logs in, it directs them to the products page, consisting of the three jewelry pieces that the user can shop. This is an example of the Singleton Design Pattern because the 'Add To Cart'button is connected to the database. So when the user adds the item to cart, the data base will write down the items under the logged name. 

Once ready to check out the user can click the shopping cart button, where the database has read from the database and written it onto the shopping cart page. Another button called 'Continue to payment' redirects the user to fill out their choice of payment, followed by a button called 'Proceed to Shipping".

On this shipping form the Singletone Design Pattern is being used again as the user inputs their shipping information and the data is being written into the database. 

