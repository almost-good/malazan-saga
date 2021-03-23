# Malazan Saga
User Centric Front End Milestone Project.

Malazan Saga website is Milestone project that is a part of Code Institute training programme. It consists of 5 pages and it's heavy on text and links.
This website will provide it's users with lots of information regarding books from Malazan Universe, written by two authors.
## Table of Contents
* [UX](#ux)
    * [Business Goals](#business-goals)
    * [User Stories](#user-stories)
    * [Design](#design)
        * [Wireframes](#wireframes)
        * [Typography](#typography)
* [Features](#features)
    * [Existing Features](#existing-features)
    * [Features Left to Implement](#features-left-to-implement)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
    * [Automated Testing](#automated-testing)
    * [Manual Testing](#manual-testing)
    * [Bugs](#bugs)
* [Deployment](#deployment)
    * [GitHub Pages](#github-pages)
    * [Local](#local)
* [Credits](#credits)

---
## UX

### Business Goals
My goal as a website owner is to gain **high traction** and reach as many users in high-fantasy book community, thus showing my support to both authors of these wonderful books. 

### User Stories
#### New Visitor
* I want to see what information is available at a glance
* I want to find information about specific book, what it's about
* I want to find information about the author of the book
* I want to be reminded of the events in the book
#### Returning visitor
* I want to explore
* I want to see what books authors have written 
* I want to find information about relationships between books
* I want to see what is the best way to read the books
* I want to find interesting quotes from the books

### Design
The website consists of 5 pages total, all 5 rich with content and links. It's responsive and users will be able to access it through number of devices, starting from small-frame mobile devices, on to tablets, laptops and even small sized TV.

#### Wireframes
Wireframes are separated by the Web Pages, offering device by device view of each page.
* [Index Page Wireframe](./docs/wireframes/index-wireframe.pdf)
* [Author Page Wireframe](./docs/wireframes/author-wireframe.pdf)
* [Collection Page Wireframe](./docs/wireframes/collections-wireframe.pdf)
* [Reading-Order Page Wireframe](./docs/wireframes/reading-order-wireframe.pdf)
* [Sign Up Page Wireframe](./docs/wireframes/signup-wireframe.pdf)

Note: during the development of the website small changes were implemented so the website may differ from original wireframes.
#### Typography
Font's that were used are Lato and IM Fell DW Pica SC, with Lato used for main content, and IM Fell DW Pica SC for headings and highlighting parts of a text.
## Features
### Existing Features
Malazan website have many different features, that are mainly used for educational purposes. 
At the top of every page there is fixed navbar present which holds 5 links, at the bottom there are two sets of social links, each set per author. 
Index page is highlighted with carousel. What is interesting is that carousel shows max of 3 items at once; lg screens 3 items, md screens 2 items, small screens 1 item. 
* ## Navbar 
    * Fixed to top
    * Responsive, it shrinks to hamburger icon
    * Consists of Logo (linked to home page), home, authors, collections, reading order and subscribe page
* ## Footer
    * Visible across all pages
    * Consists of author names and their social links
* ## Home page
    * CAT, which calls out for subscribing to a Newsletter 
    * Authors minni bio with pictures, and links to their respective full biographies
    * Carousel with images of book collections that act like links
    * Small Testimonial section
* ## Authors page
    * Author biography page, with picture, youtube interview and book lists
* ## Collections page
    * Book collections placed in scrollspy
* ## Reading order page
    * Two recommended reading orders
* ## Subscribe page
    * Form that let user type in their Name, Email address and also choose one from 3 subscription options

### Features Left to Implement
Main thing that I would like to do is optimise CSS code, that will allow me to handle website with more ease. My deadline wouldn't allow me that kind of optimization so I will leave it as a future implementation.

## Technologies Used
* [HTML](https://en.wikipedia.org/wiki/HTML) ~ Website structure
* [CSS](https://en.wikipedia.org/wiki/CSS) ~ Website style
* [Visual Studio Code](https://code.visualstudio.com/) ~ Development environment
* [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/introduction/) ~ v4.6 Grid system, navbar, carousel, scrollspy
* [Git](https://git-scm.com/) ~ Version control system
* [GitHub](https://github.com/) ~ Project repository host
* [Balsamiq](https://balsamiq.com/) ~ Wireframe design
* [Javascript](https://www.javascript.com/) ~ Carousel, Scrollspy, Form Validation
* [Google Fonts](https://fonts.google.com/) ~ Font resource
* [Fontawsome](https://fontawesome.com/) ~ Icon resource
* [Photoshop Adobe](https://photoshop.adobe.com/) ~ Minifying images

## Testing
### Automated Testing
* [W3 HTML Validator](https://validator.w3.org/) for HTML validation
* [W3 CSS Validator](https://jigsaw.w3.org/css-validator/) for CSS validation

### Manual Testing
Manual testing was done using [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
### Bugs
* Hamburger collapse show: Items would not align to the right side of a browser.
    * Tried placing mr-auto, justify-content-end, many kind of item and text alignments to get them to move at least a bit ~ no success 
    * FIX: Added display property to div that consists of nav-items which collapse from hamburger menu. Value was "block" and it has been changed to "flex". After that I added ml-auto class to HTML "ul" tag and it aligned to right side of browser window nicely.

## Deployment
### GitHub Pages
* Go to repository
* Click on "Settings"
* Scroll until section "GitHub Pages"
* Select on the "source" dropdown menu the "master branch" option
* A success message (in green) appears and it shows you the link for your live preview page in Github Pages.
### Local
* Go to repository
* Click on the button "code"
* Select the "HTTPS" option
* Copy the URL
* Open your Terminal
* Create a directory for storing this repository
* Type "git clone" and paste the URL in that you previously copied
* Press enter to create local clone repository

## Credits
### Media
* Images
    * Hero Image ~ Image sourced from Corporal--Nobbs on Devianart [Malazan World Map](https://www.deviantart.com/corporal--nobbs/art/Malazan-World-Map-739391015/)
    *  Photographs of people
        * Steven Erikson Photograph ~ Image sourced from Wikimedia [Steven Erikson](https://commons.wikimedia.org/wiki/File:Steven_Erikson_-_Lucca_Comics_%26_Games_2016.jpg)
        * Ian Cameron Esslemont Photograph ~ Image sourced from Fandom website [Ian C. Esslemont](https://malazan.fandom.com/wiki/Ian_C._Esslemont) and is used in line with Fair Use law
        * Stephen R. Donaldson Photograph ~ Image sourced from Wikimedia [Stephen R. Donaldson](https://upload.wikimedia.org/wikipedia/commons/7/78/Stephen_R_Donaldson_%28cropped%29.jpg)
        * Glen Cook ~ Image sourced from Wikimedia [Glen Cook](https://commons.wikimedia.org/wiki/File:Utos107-Glen_Cook.jpg)
        * Michael A. Stackpole ~ Image sourced from Wikimedia [Michael A. Stackpole](https://commons.wikimedia.org/wiki/File:Michael_Stackpole_by_Gage_Skidmore.jpg)
    * Book Images
        * All of the book images sourced from [GoodReads](https://www.goodreads.com)
* Icons
    * Helmet Icon ~ Icon sourced from Flaticon [Helmet Icon](https://www.flaticon.com/free-icon/helmet_812225?term=helmet&related_id=812225)
* Text ~ All the book description text sourced from [GoodReads](https://www.goodreads.com)
### Code
* Javascript Code snippet adapted from: https://www.jqueryscript.net/slider/responsive-bootstrap-carousel-multiple-items.html for Carousel
* Bootstrap 




