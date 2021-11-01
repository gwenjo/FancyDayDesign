python3 -m http.server

python3 manage.py runserver

python3 manage.py startapp 

pip3 freeze > requirements.txt

# **Milestone Project 4**
**THIS PROJECT IS FOR EDUCATIONAL USE ONLY**

**FANCY DAY DESIGN**

For my final project I chose to create a website for my sister-in-law. About 2 years ago she started making balloon decorations. From tiny balloon arches to elaborate themes for birthdays, weddings and other celebrations.<br />

The website focuses on the work of Fancy Day Design but also the simple products that are sold there. The website also features a blog where ideas and comments can be submitted.

Mockup!!
<img src="readme-documents/mockup.jpg">

live site [Fancy Day Design](https://.herokuapp.com/)

## **Contents** ##
* UX
    * [Project Summary](#project-summary)
    * [User Stories](#user-stories)
    * [Design Choices](#design-choices)
* [Wireframes](#wireframes)
* [Features](#features)
* [Technologies](#technologies)
* [Testing](#testing)
* [Fixed Issues](#fixed-issues)
* [Deployment](#deployment)
* [Credit](#credits)
* [Content and Media](#content-media)


## **UX (User Experience)** ##
### **Project Summary** ###
---


### **User Stories** ###
---
** First time user **
- As a user I want to be able to view a list of all products, so i can select the products I want to buy.
- As a user I want to be able to view a category of all products, so i can find products i'm interested in without having to search through all the products.
- As a user I want to be able to view the product individually, so i can identify product image, price, description and product rating.
- As a user I want to be able to view my shopping bag anytime to see my total, so i can see what my total costs are at any time
- As a user I want to be able to see a list of available products, so i can see the best priced and sorted products.
- As a user I want to be able to search for a product by keyword, name or descriptions, so i can find a specific product I want to buy.
- As a user I want to be able to see what I've been looking for and if the product I want is available, so i can decide whether the product I want is available
- As a user I want to be able to select the quantity of a product when purchasing, so i can can make sure I don't accidentally buy the wrong product or quantity
- As a user I want to be able to view items in my shopping bag, so i can see the total cost of my purchase and all the items I will receive
- As a user I want to be able to adjust the amount of individual items in my bag, so i can change my purchase before I check out
- As a user I want to be able to simply enter my payment details, so i can can pay quickly and easily
- As a user I want to be able to view an order confirmation after checkout, so i can check that I haven't made any mistakes
- As a user I want to be able to receive an email confirmation after checking out, so i can keep the order confirmation of what I bought for my own administration

** Returning Users **
- As a returning user I want to be able to easily register for an account, so i can view my profile and have a personal account
- As a returning user I want to be able to login or logout, so i can access my personal account.
- As a returning user I want to be able to recover my password in case I forget it, so i can restore access to my account
- As a returning user I want to be able to receive an email confirmation after registering, so i can verify that my account registration was successful
- As a returning user I want to be able to have a user profile, so i can view my personal order history and order confirmations.
- As a returning user I want to be able to leave a comment on the website, so i can comment and read from other site users

** Site owner’s Goal (admin): **

- As a site owner i want to be able to add a product, so i can add new items to my shop
- As a site owner i want to be able to edit/update a product, so i can
- As a site owner i want to be able to delete a product, so i can remove items that are no longer available.

### **Design choices**
---

For the main foundation of this website I used the videos of Boutique ado. Then this is adapted to the chosen design so that this website is clear and user-friendly.

You can always return to the homepage in the navigation bar.

**Framework**


**Typography**

-   [Google Fonts](https://fonts.google.com/specimen/Roboto) was used for the font style of this project. The font used for this website is Roboto with a backup font of Sans-serif. It is a simple and easy to read font. The font is also easy to read on smaller devices.

**Icons**

-   [FontAwesome](https://fontawesome.com/) was used for my forms and buttons, 
    to make it more appealing.

-   The Fancy Day design logo is used for the favicon. There has been made use of [Favicon](https://favicon.io/) to create this favicon.

**Colour Scheme**

The colors used for this website have been selected by Shakira Lacroes (owner).

(zwart) 		#231f20
(gebroken wit)	#fff9f9
(Zand)			#e3d8d2
(zand donker)		#c19c77

Logo font - #8d6e63

Edit button

button

Card-Panel

Page-header 

Home-image h1

All Icons

Cancel button

## **Wireframes**


## **Features**
---
Navigation bar is visible on all pages. On a smaller page, it turns into a bar. The navbar contains a logo and links for each section and subsection of the website.

The footer contains three sections, the first section links to different sections of the website, the middle section contains the location of the stores and the third section refers to the social media links.

There is a search bar on every page, where you can easily search for products by name and/or keyword

***Home/ Index Page***
On the home page there is a button that takes you directly to the products page. Under the title be inspired you can see 3 images. Also on this page is the testimonial

***Product Page***
Here you will find all products that are for sale in this webshop.

***About Page***
On this page you can find information about who Fancy Day design

***Profile Page***

***Contact Page***

***Blog Page***


**Features Left to Implement**

## **Technologies**
---

The following technologies were used for this website:

## Programming
* [HTML5](https://en.wikipedia.org/wiki/HTML) HTML was used to create the layout and gave the page structure and presenting static data. In the folder 'templates' you will find all HTML files.
* [CSS](https://en.wikipedia.org/wiki/CSS) the project used CSS stylesheets to specify style of the web document elements;
* JavaScript - the project used JavaScript to implement Stripe, EmailJS and custom Javascript.
* Python - the project back-end functions are written using Python.

## Libraries
* [Font Awesome](https://fontawesome.com/v4.7.0/)
* [jQuery](https://jquery.com/)

## Database
* [Heroku Postgres](https://www.heroku.com/postgres/)

## Frameworks
* [Bootstrap](https://getbootstrap.com/)
* [Django](https://www.djangoproject.com/)

* [EmailJS](https://www.emailjs.com/)
* [Stripe](https://stripe.com/ie) 
 
## Others
* [GitHub](https://github.com/)
* [Gitpod](https://gitpod.io/workspaces/)
* [Heroku](https://dashboard.heroku.com/)
* [AWS-S3](https://aws.amazon.com/s3/) 

**Tools used**

**[Balsamiq](https://balsamiq.com/)**
-   Before I started on the website, I used Balsamiq software to set up my  
    wireframe. <br>

**[Google Fonts](https://fonts.google.com/)**
-   Google Fonts was used to select the font for my website.

**[Pexels](https://pexels.com/)** & **[Adobe Stock](https://stock.adobe.com/nl/free.com/)**
-   The images for this website mostly come from Fancy Design herself. To fill the product page, some other images were used from pexels.com and adobe.stock.com. The names of the photographers are listed in the media section below this page.

**[Resize It](https://apps.apple.com/us/app/resize-it-image-resize/id844716779)**
-   Resize It was used to easily crop the photos to the correct size. I used my Iphone for this.

**[Materialize](https://materializecss.com/color.html)**
-  For the color selection Materialize was used. But then the owner came with here own colors. So i used her colours.

**[W3School](https://www.w3schools.com/)**

**[Css Beautifier](https://www.freeformatter.com/css-beautifier.html)**
-   Css Beautifier was used for formatting my CSS code.

**[Am I Responsive Design](http://ami.responsivedesign.is)**
-   For the mockup in the beginning of my readme file Am I Responsive Design was used 

**[W3C HTML Validator](https://validator.w3.org/)**
-   To validate my HTML code this tool was used.

**[W3C CSS Validator](http://jigsaw.w3.org/css-validator/)**
-    To validate my CSS code this tool was used.

**[Wave Webaim](https://wave.webaim.org/)**
-   webaim was used to check the contrast of my website.

**[Dillinger](https://dillinger.io/)**
-   To make my README file more organized Dillenger was used.

Bootstrap Toasts

**[]()**
-   

## **Testing** ##
---



**Lighthouse**

Desktop

<img src=" " width="50%" height="50%">
  
<img src=" " width="50%" height="50%">

## **Fixed Issues**

## **Deployment**
---


## Heroku Deployment 


## **Credits**
---
Videos from Code Institute



## **Content and Media**
---
Carousel - testimonials
-https://www.w3schools.com/howto/howto_js_slideshow.asp

THIS PROJECT IS FOR EDUCATION USE ONLY

For the main foundation of this website I used videos from Code Institute - Project - Boutique Ado. Then I modified it to this website.

Most of the photos used for the website were made by Shakira Lacroes (owner). To fill up the product page I used some other pictures from pexels.com and adobe stock.
Obtained from Pexels.com: 

-	Ring Balloon & Happy Birthday Balloon - Polina Tankilevitch

-	Love Balloon - Cottonbro

Obtained from stock.adobe.com/nl/free: 

-	All-numbers balloon. From this image I took all the individual photos of the numbers and used them for the products.

-	All-Alphabet letters balloon. From this image I took all the individual photos of the letters and used them for the products.

-	Gender reveal balloon.


The content of the about.html page is written by Shakira Lacroes the owner (and my sister in law) of Fancy Day Design.

Used websites and images:

Review Forms and Add to Database using forms | Build Movie Review Website Using Django 2020.
[video](https://www.youtube.com/watch?v=lSX8nzu9ozg

[Building A Blog Application With Django](https://djangocentral.com/building-a-blog-application-with-django/)

Wat is een blog? [Dutch Page](https://www.blogkracht.nl/wat-is-een-blog/) 

Create A Simple Django Blog from [Codemy.com](https://www.youtube.com/results?search_query=make+a+blog+with+django)

**Resources**
**Code I have used**

I want to reiterate that THIS PROJECT IS FOR EDUCATION USE ONLY.<br />





### **Acknowledgements**
---

Student Care

I want to thank my friends and family who have viewed my website multiple times, have given me good criticism on my website and for putting up with my moodiness these past few weeks.

I would also want to thank my mentor who believed in me that I can do this project in 3 weeks and my fellow student Daphne for always staying positive!

The Slack community!

**THIS PROJECT IS FOR EDUCATIONAL USE ONLY**
