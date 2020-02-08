# EL1TE
**Milestone project 1: User-Centric Frontend Development - Code Institute**

For a silkscreen-press company a need for new concepts in sports clothing has been requested to get more customers in sport.
The site needs to be small, informative, quick and to use a well thought-out logic.
The main goal is to make the company known on the web and to trigger the new customers' attention.
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
to instill confidence in the potential B2B customer looking for the products they need.

## User stories
Trough phone-research of existing customers, we tried to find out what they need and what they think the companies strongest points are.
We wanted to know what the costumers finds most important.
The following points came up:

 - As a user, I want to see if this company is trustworthy. (**service page**)
 - As a user, I want to know if this company is fast and flexible. (**service page**)
 - As a user, I want to know how much it will cost. ( **price page**)
 - As a user, I want to know my product options. (**product page**)
 - As a user, I want to know how I can contact this company. ( **blue contact box, contact page and footer**)
 - As a user, I'm mostly busy and I want to find quick and preferable on my phone. ( **responsive**)

### Strategy
The goal in the design was to make it as easy as possible to access, short and an informative B2B based site,
while striving for a minimalist and user-friendly design as possible.

### Scope
For B2B visitors, we wanted to provide them with a short overview of the products and the companies strongest points.
This way, they would be able to get a glimpse of what the company sells and if it is a trustworthy partner to do business with.

### Structure
The site is structured to get the right information as quickly as possible.
Contact information on the top and further down buttons to get to the contact form.
A navigation bar that's always available to quickly scroll between pages.
The proper order of the pages is created to trigger the reader to contact us.

### Skeleton
By using figma the following wireframes were created:

[EL1TE wireframe](https://github.com/D1ang/EL1TE/blob/master/mockups/wireframe.pdf)

[Responsive phone wireframe](https://github.com/D1ang/EL1TE/blob/master/mockups/responsive.pdf)

### Surface
The colours blue and orange were used to create a high energy "sport" like feel.
After a short Google search for the most used Google Fonts on sport sites, Oswald was chosen on its popularity and demand.
The buttons are styled as blocks to be in comformt with the header block and to keep the style in check with the blue call to action block.

## Technologies
1. HTML - *To create a basic site*
2. CSS - *To create a nice style and to stand-out*
3. Bootstrap - *To improve responsiveness*
4. Figma - *To create a wireframe*


## Features
This site uses a parallax scrolling effect in CSS to create a subtle element of depth that results in a distinctive and memorable website. 
The navbar collapsed on smaller screen sizes to be useful for phones and will be available on every page.
On larger screens a "call to action" blue box wil appear so user can contact more quickly without scrolling through the page.
by using Smooth Scrolling a scroll effect has been added as the site felt a bit sluggish.
The buttons are created to move the user to the contact page as this would be the final step that we would like to achieve.


### Features Left to Implement
In the future, we would like to add an order system with a login so existing customers can order more products easily.
Also, we would like to add some animations to the cards in the products and prices section to move on the page when the section is scrolled to. 


## Testing
All links will function, but the social media links will open the main page of that particular platform.
The "Send us your details" button will return to the home section.
Custom CCS code is written for every button comfort design.

This site was tested across multiple screen sizes on Chrome, Safari and Internet Explore
To ensure compatibility and responsiveness it was also tested on an android based mobile device (OnePlus5).
When the webpage is visited on larger screens a blue box is shown on the upper right side of the screen.
This will disappear on smaller screens the box is used for direct to call actions and social media.
A navigation bar is shown all the time and will transform to an option bar on smaller phone screens.

The text and card-decks will properly align on every screen size. The card-decks have some extra CSS code to improve alignment of the content within the cards.
The footer will place the text beneath each other to make it better readable for smaller screens.

## Bugs:

### Card-decks responsive:
The standard Bootstrap functions gave problems with the content inside cards. On card-decks the content got squashed so a solution needed to be found.
[stack overflow](https://stackoverflow.com/questions/48406628/bootstrap-align-button-to-the-bottom-of-card)
This solution steps away from the regular bootstrap grid and uses a workaround in CSS to fix the responsive problems.

### Scrolling:
The site felt a bit sluggish when scrolling with the buttons to different pages.
[w3schools.com](https://www.w3schools.com/howto/howto_css_smooth_scroll.asp)
By using Smooth Scroll the navigation buttons to the pages will react more fluid.

### Navbar hamburger icon:
The navigation bar hamburger icon that shows on smaller screens had an outline when pressed, and jumped a few pixels up.
This has been fixed by adding a top-padding of 3 pixels in the style and by adding the following code:

>.navbar-toggler:focus,
>.navbar-toggler:active {
>	outline: none;
>	box-shadow: none;
>}


The following tests have been used to ensure proper site functionality:

- [GTmetrix](https://gtmetrix.com/): To test on website loading times
- [W3C HTML Validator](https://validator.w3.org/): This validator checks the markup validity of Web documents in HTML.
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/): This validator checks the markup validity of Web documents in CSS.
- [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB): Inspecting on overflow errors
- [Autoprefixer CSS online](https://autoprefixer.github.io/): Autoprefixer is a PostCSS plugin which parses your CSS and adds vendor prefixes


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

- The Parallax Scrolling effect was found on w3schools.com [link](https://www.w3schools.com/howto/howto_css_parallax.asp) (by mentor advice)
- Fixing the card-decks responsiveness [link](https://stackoverflow.com/questions/48406628/bootstrap-align-button-to-the-bottom-of-card)
- The following site [link](https://www.mbsportswear.nl/) was used as an insparation for the navigation bar and blue "call to action" box.