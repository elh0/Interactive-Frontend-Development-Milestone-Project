# Interactive Frontend Development Milestone Project

This project was developed from the brief enlisted by Code Institute. I created a flip card memory game, using CI staff members as the playing cards.

The objective of the game is to sucessfully **match all 12 cards**.

Within this project I have used everything I learned thus far from Code Institue.
This project will utilise my experience of **HTML5**, **CSS3** & **JS**.

## UX

The user is guided fluidly to operate the game through the header & footer elements. This is common practice for users to find more information about the webpage so these are natural interactions therefore creating a familar feeling. I was intent on using enough negative space for the user to focus on the game in practice & leave no distracting/unecessary elements on the webpage.

The JavaScript code also has an application of UX using functions & variables such as ```setTimeout``` & ```lockBoard```. These were created with intention of helping the user stay within the parameters of the games intended functionality. ```setTimeout``` provides a slight delay when cards aren't correctly matched, whilst ```lockBoard``` prevents user from selecting multiple cards on the canvas.

## User stories

* As a new user landing on the page I want clear instructions of what to do upon landing & where to click

* As a new user I want to understand the game objective

* As a new user I would like to be rewarded for completing the objective

* As a new user I would like see relevant/well known images or logos to better understand the game

### First version

* Sizing of cards on mobile were illegible - Container was scaling down as opposed to containing

* ```setTimeout``` felt "slow & clunky to play" - ```setTimeout``` was set to ```1000``` causing a slow response feel

* Body was un-responsive at mobile-device width - Media queries were yet to be implemented

* Card colour was "difficult to differientiate" - This was due to the close colour codes of the body background & card background

### Final version
* Card sizing issue - ```object-fit : contain;``` was implemented to correct this

* Slow response time issue - ```setTimeout``` was reduced to ```500``` from ```1000```

* Responsiveness issue - Media queries were implemented at mobile & tablet view

* Card readability - Colour palette was corrected by using deeper shades to distinguish body elements

### [Wireframes](https://www.figma.com/file/019CbRh9rL3j3STQzXtMKjHj/Interactive-frontend-Memory-game-wireframes?node-id=0%3A1)

## Features 

* **Main playing board** - Optimised for desktop & devices

* **Header CTA** - Prompts user to click the main board/cards

* **Footer CTA** - Assists user with the game objective

### Features Left to Implement 

* Timer

* Levels/increase difficulty

* Sucess modals to assist with game completion (leave user satisfied)

* Advanced CSS3 animations

## Technologies Used

* **MS Visual Studio** - Coding and storing a local repository

* **Github** - Version control & remote resposity as well as deployment

* **Cloud9** - Mentor sessions to display queries & questions

* **Google Fonts** - Header & footer element styling

* **JavaScript** - Manipulated the DOM and make the game interactive

* **HTML** - To create the markup

* **CSS3** - To style the webpage

* **Adobe Illustrator** - SVG creation

* **Figma** - Wireframe creation

## Testing

* Tested on **Chrome**

* Tested on **iPhone**

* Tested on **Firefox**

## Validation

* HTML & CSS Validated with [W3C](https://validator.w3.org)
* JS Validated with [JsHint](https://jshint.com/)

## Deployment

To deploy my project I pushed my local respoitry to my GitHub repository named **Interactive-Frontend-Development-Milestone-Project** via the GitHub for desktop. Commits were deployed each time edits were made to my code and I needed to save them. To create my GitHub page I built it from the Master branch.

### [My GitHub](https://github.com/elh0)

### [View Site](https://elh0.github.io/Interactive-Frontend-Development-Milestone-Project/)

## Credits 

* Excerpts of JS code was implicated via [YouTube](https://www.youtube.com/watch?v=ZniVgo8U7ek&t=43s) - By freeCodeCamp.org

* Preloader SVG animation [Loading.io](https://loading.io/) - By loading.io

### Sites Used

* [W3 Schools](https://www.w3schools.com/html/default.asp) 

* [JsHint](https://jshint.com/)

* [CodeInstitute](https://courses.codeinstitute.net)

* [YouTube](https://www.youtube.com/)

* [Stack Overflow](https://stackoverflow.com/)

* [CodePen](https://codepen.io/)

### Fonts 

* [Poppins by Google Fonts](https://fonts.google.com/specimen/Poppins)

### Media Credits

* Code Institute [Image Source](https://codeinstitute.net/)

### Feeback

* *Feedback taken from CI Slack forum & mentor Antonija Simic*

## **Thanks for reading!**
