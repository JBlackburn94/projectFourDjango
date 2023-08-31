# Jason Blackburn - Milestone Project 4 JB Vapes

This site is to be used by the user to browse and purchase vape products.

Deployed Site: https://project-four-django-8dfc14207eac.herokuapp.com/

# Table of Contents

1. [Business](#business)
2. [Colour Scheme](#color-scheme)
3. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
5. [Testing](#testing)
6. [Deployment](#deployment)
7. [Credits](#credits)
8. [Media](#media)

# Business <a name="business"></a>

The business goals of this page are to provide the user with an ecommerce store in order to browse and purchase vape products.

## Site Owners Goals

The site owners goals of this page are to provide clear weather data using the Open Weather API.

# Colour Scheme <a name="color-scheme"></a>

This site uses a minimalist colour scheme of mainly black and white, with various bold coloured buttons to make it easier for important options to stand out to the user. The main hero image is bold in colour and the remainder of the site upholds a professional style. 

# Wireframes <a name="wireframes"></a>

I have made wire frames for desktop and mobile. These can be seen below. This app has basically the same layout on mobile and desktop due to the simplicity of the UI.

![image](<readMeImgs/projectFourWireframe.png>)

# Technologies Used <a name="technologies-used"></a>

During the build for this page I used:

HTML

The project uses HTML to create the content.

CSS

The project uses CSS to style some of the elements, and also makes some of the elements responsive.

JavaScript

The project uses JavaScipt to handle the interactivity and functionality of the front end. 

Python

This project uses Python to handle the backend of the site.

Django

This project uses the python framework Django including some of its built in apps etc.

GitPod

I used GitPod to build this project.

GitHub

I have used GitHub to push and deploy this project.

# Testing <a name="testing"></a>

“PLEASE NOTE - There is an error showing. The error claims that some external font/icon files have not been loaded. But having investigated this with my mentor, we can clearly see all items have loaded and this error is incorrect. There is also an error should an incorrect location or spelling mistake entered. However, I have accounted for this by using a catch statement, upon entering a mistake the user will be prompted with an alert to make them aware there were no results found. -”

This project was tested using:

[W3 HTML Validator](https://validator.w3.org/)

The W3 Schools HTML Validator - returning 0 errors.

[W3 CSS Validator](https://jigsaw.w3.org/css-validator/)

The W3 Schools CSS Validator - returning 0 errors.

[Google Chrome Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/)

Google Chrome Lighthouse was used to score the performance and accesibility of this site.

The code was also ran through JSLint, a number of errors were present but they were mainly due to empty white space etc. After fixing the layout issues I was only left with errors that weren't major issues.

I also ran manual tests on this project and worked towards fixing any errors I found. The main problem I found was upon entering an incorrect location name or a spelling mistake, an error 404 would be present in the console. I fixed this by implementing error handling, using a catch statement to alert the user when they're search returned no data, the alert will then ask them to reset, check again and finally check their spelling.

| User Story                                                                                              | User Case                                                                                                                                                      | Pass/Fail |     |     |
| ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | --- | --- |
| User Story 001 - (Consumer) As a consumer I want to be able to add, update and remove an item from my basket.    | User case 001-001 All products can be added, updated and removed from the basket with ease, all buttons to update and delete are easily located and work as they should.                        | Pass      |     |     |
|
| User Story 002 - (Consumer) As a consumer I want to be able to register for an account, log into my account and save my details for next time. | User case 002 - 001 The consumer can register for an account, then use the account details to login. Once logged in, the user can then either register their address details in the account section or can save their address details after initial purchase. | Pass      |     |     |

# Deployment <a name="deployment"></a>

GitPod -> GitHub -> Heroku (Static files loaded through AWS and ElephantSQL used to manage the databases.)

## GitHub

Create GitHub Repository using VS Code. Commited and pushed all content from VS Code to Github.

## Heroku

Completed site deployed to Heroku.

## AWS

I used Amazon AWS to store static files and media.

## Elephant SQL

I used Elephant SQL to manage my databases. I have two database models, one for categories and one for products. Products is a child of categories.

## Database Layout

![image](<readMeImgs/projectFourDatabaseModel.png>)

# Credits <a name="credits"></a>

[Stack Overflow](https://stackoverflow.com/)

I used Stack Overflow to research different bugs on the build.

Code Institute

I used Code Institute materials to help with some of the build and deployment.


