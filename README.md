# EL1TE
Milestone project 1: User-Centric Frontend Development - Code Institute

## Introduction
As a current employee of a screen-press company a need for new concepts 
in sports clothing has been requested to get more customers in sport.
The site needs to be small, informative, quick and to use a well thought-out logic
Main goal is to make us know on the web and to trigger new customers attention.
The customer base will be B2B companies in sports.

In short:
- increase brand awareness
- attrac more clients

## Demo
A live demo version can be found [here](https://d1ang.github.io/EL1TE/).

![Design](https://github.com/D1ang/EL1TE/blob/master/mockups/responsive.png)

## UX
To make the website as clear as possible to the user as to the option we provide.
Be simple layout with the main focus on the companies service and product options
to in-still confidence in the potential B2B customer looking for the products they need.

## User stories
Trough phone-recearch of excisting customers we tried to find out what they need and what they think what our strongest and weakest point are.
We wanted to know what our costumer find important.
The following points came up:

 - As a user, I want to see if this company is trustworthy.             (service pag)
 - As a user, I want to know if this company is fast and flexible.      (service page)
 - As a user, I want to know how much it will cost.                     (price page)
 - As a user, I want to know my product options.                        (product page)
 - As a user, I want to cknow how I can contact this company.           (blue contactbox, contact page and footer)

### Strategy
The goal in the design was to make it as easy as possible to access short informative B2B based site,
while striving for a minimalist and user-friendly design as possible.

### Scope
For B2B visitors, we wanted to provide them with a short overview of the products and the companies strongest points.
This way, they would be able to get a glimpse of what the company sells and would be a trustworthy partner to do business with.

### Structure
The site is structured to get the right information as quickly as possible.
Contact information on the top and further down buttons to get to the contact form.

### Skeleton
[EL1TE wireframe](https://www.figma.com/file/3VCrAaJBiDzaORiA8KSroK/EL1TE?node-id=0%3A1)
[Responsive phone wireframe](https://www.figma.com/file/EdKAJaVOlBZMMYuAMIOIms/EL1TE-Copy)

### Surface
The colours blue and orange were used to create as high energy "sport" like feel.
After a short Google search for the most used Google Fonto n sport site's.
Oswald was shocen on it's popularity in demand on sport sites.

## Technologies
1. HTML5            To create a basic site
2. CSS              To create a nice style and stand out
3. Bootstrap        To improve responsiveness


## Features
This site uses a parallax scrolling effect in CSS to create a subtle element of depth that results in a distinctive and memorable website. 
The navbar collapsed on smaller screen sizes to be usefull one phones.
On larger screens a "call to action" bluebox wil appear so user can contact more quickly without scrolling trough the page.

Navbar: 
Home:
Products:
Service:
Price:
Contact:

### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

### Features Left to Implement
In the future, I would like to add an ordersystem behind a login so excisting customers can order products more easily.
I would like to also add animations to the cards in the products and prices section to move on the page when the section is scrolled to. 


## Testing
All links will function but the socialmedia links will open the main page of the particular platform.
The "Send us your details" button will return to the home section.
Custom CCS code is writting for every button comfort design.

This site was tested across multiple screen sizes on Chrome, Safari and Internet Explore
To ensure compatibility and responsiveness it was also tested on an android based mobile device (OnePlus5).
When the webpage is visited on larger screens a blue box is shown on the upper right side of the screen.
This will dissapear on smaller screens the box is used for direct to call actions and social media.
A navbar is show all the time and will transform to a optionbar on smaller phone screens.

Text.
The text and card-decks will properly align on every screen size. The card-decks have some extra CSS code to improve alignment of the content within the cards.
The footer will place the text beneeath echother to make it mmore nice for phonelinke smaller screens.

## Bugs:

### Card-decks responsive:
Fixing the card-decks responsiveness
The standard Bootstrap functions gave problems with the content inside cards on card-decks it got squashed so a solution needed to be found.
[stack overflow](https://stackoverflow.com/questions/48406628/bootstrap-align-button-to-the-bottom-of-card)
This solutions steps away of the rugalar bootstrap grid and uses a workaround in CSS to fix the responsive problems.

### Scrolling:
Scrolling to the site felt a  bit slugish by using Smooth Scrolling
[w3schools.com](https://www.w3schools.com/howto/howto_css_smooth_scroll.asp)
By using Smooth Scroll the navbuttons to the pages are react more fluid.


The following test have been used to ensure proper site functionality:
[GTmetrix](https://gtmetrix.com/) To test on website loading times
[W3C HTML Validator](https://validator.w3.org/) This validator checks the markup validity of Web documents in HTML.
[W3C CSS Validator](https://jigsaw.w3.org/css-validator/) This validator checks the markup validity of Web documents in CSS.
[Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) Inspecting on overflow errors
[Autoprefixer CSS online](https://autoprefixer.github.io/) Autoprefixer is a PostCSS plugin which parses your CSS and adds vendor prefixes


## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, you can clone this repository directly into the editor of your choice by pasting the link into your terminal.
To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.


## Credits

### Content
All content on this site were written by me. 

### Media
All photos were taken from [Adobe Stock](https://stock.adobe.com/), a stock image library.
All material from Adobe Stock are licensed with a paid account.


### Acknowledgements

The Parallax Scrolling effect was found on w3schools.com [link](https://www.w3schools.com/howto/howto_css_parallax.asp) by advice.

Fixing the card-decks responsiveness [link](https://stackoverflow.com/questions/48406628/bootstrap-align-button-to-the-bottom-of-card)
The standard Bootstrap functions gave problems with the content inside cards on card-decks it got squashed so a solution need to be made.
This solutions steps away of the rugalr bootstrap grid and uses CSS to fix the responsive problems.

The following site [link](https://www.mbsportswear.nl/) was used as an insparation for the navbar and blue "call to action" box.
