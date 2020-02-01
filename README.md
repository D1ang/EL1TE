# EL1TE
Milestone project 1

This is my first project website to present to prospective employers. 
This site icludes a nice parales effect that makes sense by right placing meaningfull pictures.
It's build as a short sales pitch to get more customers.
It's small, informative, quick and uses a well thought-out logic.

## Demo
A live demo version can be found [here](https://d1ang.github.io/EL1TE/).

![Desktop Demo](https://raw.githubusercontent.com/hschafer2017/HSCHAFER-Portfolio/master/assets/images/portfolioview.gif "Desktop Demo")

## UX


















 
## UX
 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X






























## UX

### User stories

As an employer I expect to see a showcase of Haley's work.

![Work Showcase](https://raw.githubusercontent.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/master/assets/images/showcase.png "Work Showcase")

As a recruiter I expect to see a showcase of Haley's resume.

![Resume](https://raw.githubusercontent.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/master/assets/images/cv.png "Resume")

### Strategy
My goal in the design was to make it as easy as possible to access information on the site while striving for a minimalist and user-friendly design.

### Scope
For employers, I wanted to provide them with a brief overview of myself and my capabilities. This way, they would be able to get a glimpse of who I am, my background, work I've done, and my skills, with the option to contact me if they choose.

### Structure
In the 'Work/Travail' section, I wanted them to be able to quickly access work that I've done, providing a short summary of the project and main technologies with a link to each GitHub Repository and live demo. A link to my LinkedIn profile, my GitHub, and a downloadable PDF version of my CV were also provided for their ease of access.

### Skeleton
[About wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/about.png)

[Contact wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/contact.png)

[Landing Page wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/landing.jpeg)

[Skills wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/skills.jpeg)

[Work wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/work.png)

### Surface
The greyscale color scheme was chosen to create a sleek and modern feel.

## Technologies
1. HTML
2. CSS
3. Bootstrap (3.3.7)


## Features
This site uses the scrollSpy feature in Bootstrap with an extra JavaScript function added to create a 'smooth scrolling' effect. The navbar also stays collapsed regardless of the screen size to promote a minimalist design.


### Features Left to Implement
In the future, I would like to add further projects that I've worked on to create a more comprehensive 'work/travail' section. I would like to also add animations to the progress circles in the "skills/compétences" section to animate on a hover. 


## Testing
The employer and recruiter user story achieved the intended outcome of providing them with a showcase of myself and my work. In the about me section, they can read a bit about my background, and if they're viewing on a desktop, the background of this section is a photo of me. They are able to see my showcased projects via the project cards in the "Work" section. They can view both the live version and the GitHub repository by clicking on the Font Awesome icons. They are also able to view my social media profiles via clicking on the icons in the footer. They are also able to download my CV by either clicking on CV in the navbar dropdown, or by clicking on the document icon in the footer. 

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid, the page will reload. If an employer or recruiter is interested in contacting me, they will have to fill out all fields in order for the form to go through.

All links will open in a new tab using 'target="_blank"' and the CV will download to your default folder for downloads on click using the 'download' attribute. All links have been manually tested to ensure that they are pointing to the correct destination.

By clicking on the links in the navbar, the scrollSpy effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar. 

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. During the testing phase, I realized that ```background-attachment: fixed``` was not compatible with iOS browsers. On Chrome and Safari in iOS, the background photos appeared zoomed-in and blurry. To fix this, the ```background-attachment: scroll``` property value was added in a media query.


## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/hschafer2017/HSCHAFER-Portfolio.git` into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.


## Credits

### Content
All content in the "About Me/À Propos" and "Work/Travail" sections in this portfolio site were written by me. 

### Media
All photos were taken from [Pexels](https://www.pexels.com/), a stock image library, with the exception of the photo of myself in the background of the 'about me/À Propos' section in the desktop view. A greyscale filter was applied to each one prior to upload to preserve the greyscale theme. 

### Acknowledgements
The scrollSpy delay JavaScript function was found through this tutorial [here](https://www.abeautifulsite.net/smoothly-scroll-to-an-element-without-a-jquery-plugin-2).

The progress circles from the skills section are modeled after the following Stack Overflow [example](https://stackoverflow.com/questions/14222138/css-progress-circle). They were significantly modified to fit the styling, sizing, and progress for each skill.

The media query for the collapsed navbar regardless of viewport width was taken from this [site](https://www.codeply.com/go/iaM1zcNsQB/bootstrap-navbar-always-collapsed).

**This is for educational use.** 
