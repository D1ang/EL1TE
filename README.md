# EL1TE
Milestone project 1: User-Centric Frontend Development - Code Institute

For a silk screen-press company a need for new concepts in sports clothing has been requested to get more customers in sport.
The site needs to be small, informative, quick and to use a well thought-out logic.
Main goal is to make the company know on the web and to trigger new customers attention.
The customer base will be mostly business to business in sports.

In short:
- increase brand awareness
- attract more B2B customers

## Demo
A live demo version can be found **[here](https://d1ang.github.io/EL1TE/)**

![Design](https://github.com/D1ang/EL1TE/blob/master/mockups/responsive.png)

## UX
To make the website as clear as possible to the user as to the options we provide.
Be simple layout with the main focus on the companies services and products.
to in-still confidence in the potential B2B customer looking for the products they need.

## User stories
Trough phone-research of excisting customers we tried to find out what they need and what they think what our strongest points are.
We wanted to know what our costumer find important.
The following points came up:

**service page**
 - As a user, I want to see if this company is trustworthy.
 - As a user, I want to know if this company is fast and flexible.

 **price page**
 - As a user, I want to know how much it will cost.

 **product page**
 - As a user, I want to know my product options.

 **blue contactbox, contact page and footer**
 - As a user, I want to cknow how I can contact this company.

 **responsive**
 - As a user, I'm mostly busy and I want to find quick and preverable on my phone

### Strategy
The goal in the design was to make it as easy as possible to access, short and a informative B2B based site,
while striving for a minimalistic and user-friendly design as possible.

### Scope
For B2B visitors, we wanted to provide them with a short overview of the products and the companies strongest points.
This way, they would be able to get a glimpse of what the company sells and if it is a trustworthy partner to do business with.

### Structure
The site is structured to get the right information as quickly as possible.
Contact information on the top and further down buttons to get to the contact form.
A navigationbar thats always available to quickly scroll between pages.
The proper order of the pages is created to try to trigger the reader to contact us.

### Skeleton
By using figma the following wireframes were created:

[EL1TE wireframe](https://github.com/D1ang/EL1TE/blob/master/mockups/wireframe.pdf)

[Responsive phone wireframe](https://github.com/D1ang/EL1TE/blob/master/mockups/responsive.pdf)

### Surface
The colours blue and orange were used to create as high energy "sport" like feel.
After a short Google search for the most used Google Fonts on sport sites, Oswald was chosen on it's popularity and demand on excisting sport sites.
The buttons are styled as blocks to be in comform with the header block and to keep the style in check with the blue call to action block.

## Technologies
1. HTML *To create a basic site*
2. CSS *To create a nice style and to stand-out*
3. Bootstrap *To improve responsiveness*
4. Figma *To create a wireframe*


## Features
This site uses a parallax scrolling effect in CSS to create a subtle element of depth that results in a distinctive and memorable website. 
The navbar collapsed on smaller screen sizes to be usefull on phones and will be available on every page.
On larger screens a "call to action" bluebox wil appear so user can contact more quickly without scrolling trough the page.
by using Smooth Scrolling a scroll effect has been added as the site felt a bit slugish.

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
In the future, I would like to add an ordersystem with a login so excisting customers can order products more easily.
Also I would like to add some animations to the cards in the products and prices section to move on the page when the section is scrolled to. 


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

### Navbar hamburger icon:
The navbar hamburger icon that show on smaller screens had a outline when pressed and jumped a few pixel up.
This has been fixed bij adding a top-padding of 3 pixel in the style and by adding .navbar-toggler:focus,
.navbar-toggler:active {
	outline: none;
	box-shadow: none;
}
for the banenr

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
