python3 -m http.server

python3 manage.py runserver

python3 manage.py startapp 

pip3 freeze > requirements.txt


cp -r ..//.pip-modules/lib/python3.8/site-packages/allauth/templates/* ./templates/allauth/ 

python3 manage.py loaddata categories
python3 manage.py loaddata products

python3 manage.py makemigrations --dry-run
python3 manage.py makemigrations

python3 manage.py migrate --plan
python3 manage.py migrate

export STRIPE_PUBLIC_KEY=pk_test_51JIHDOAae3eclnd3VlRgz2n3eYQqHen1CaCArxIWqOXRufHKNQ6Q9oMaaebUIMig2e7s3eHgaDjrsutCip5EPA0G00EsoG9jVy

export STRIPE_SECRET_KEY=sk_test_51JIHDOAae3eclnd3ojC0IlDBgb3equmNplZxmqup9Sds8rGjlmswL67TACMMnM9UcamHjTYcPyQVh6oFZWZ8fSpp00mB0Fmebi

export STRIPE_WH_SECRET=whsec_uDyWj5ad9RCafi8OOIDpigjY2LQYBOXt

# **Milestone Project 4**
**THIS PROJECT IS FOR EDUCATIONAL USE ONLY**

**FANCY DAY DESIGN**

For my final project I chose to create a website for my sister-in-law. About 2 years ago she started making balloon decorations. From small balloon arches to elaborate themes for birthdays, weddings and other parties.<br />

Mockup!!
<img src="readme-documents/mockup.jpg">

live site [Asian Flavours](https://asian-flavours.herokuapp.com/)

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

## **UX (User Experience)** ##
### **Project Summary** ###
---


### **User Stories** ###
---
** First time user **

- 

** Returning Users **

-

** Site owner’s Goal: **



### **Design choices**
---

The chosen design for this website is clear and user-friendly.


**Framework**

-   For the Front-end framework, [Materialize](https://materializecss.com/)
    was used for this website. It was used to create features such as navigation bar, forms and buttons.

-   [JQuery](https://jquery.com/) was used to initialize some Materialize 
    elements.

-   Micro framework [Flask](https://flask.palletsprojects.com/en/1.1.x/), 
    was used for this website, flask was chosen to build the backend.

**Typography**

-   [Google Fonts](https://fonts.google.com/specimen/Roboto) was used for the font style of this      
    project. The font used for this website is Roboto with a
    backup font of Sans-serif. It is a simple and easy to read font. The font is also easy to read on smaller devices.

**Icons**
-   An existing favicon has been chosen for this website [Favicon](https://favicon.io/). 


**Colour Scheme**
