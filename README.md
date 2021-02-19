# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from a `JSON` object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge.. Your work reflects your proficiency in Preprocessing, and JavaScript Basics.

> You have **three hours** to complete this challenge. Plan your time accordingly.

## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You are free to work with the full data set as a stretch goal.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. How would you describe acessibility on the web to someone new to programming?
    Accessibility is all about accomodating all walks of life and making your web pages adaptable to their needs. Things such as responsive units, color overlays, larger buttons on mobile, different settings for people with disabilities, etc. Websites onn mobile that are all squished have not been optimized with media queries for different max width sizes of a device. Accessibility even comes down to using proper HTML semantics 
2. Talk about 3 different things you can do to ensure your website is accessible. 
    1) Use proper HTML semantics so a screen reader can find headers, sections, etc when reading for someone with hearing problems. 
    2) When a website is accessed through  a mobile device or tablet, you can make buttons and certain divs that the user may interct with bigger, so that they can be clicked or see on a smaller screen. 
    3) One accessibility option I hold dear is a coorblind option. You can set different display colors on background and text so they do not blur into the colors of other things on the page. 
3. How would you explain the concept of a variable to someone new to programming?
    - A variable can be anything you want it to be, a string, intiger, boolean. We declare a variable using let, const, and "never" var (or at least consider using it last if the others won't work well enough for your goal). Variables can be declared using an "=" and they can be redeclared throughout your functions and work as long as their declaration allows it. You should always name your variable something that relates to it's function or use in the code, so that other developers know what it does when they work with your code. 
4. What is the purpose of using functions in code?
    - Functions perform operations for us. They are custom, or pre-built (methods) so that we can create processes and tasks for the computer. A funtion can access an array and push the items to a new array, it could perform mathmatics, compare variables, many many things - in theory,  it could do "any" task you design it to do, if coded properly. A series of functions together, that take in other functions as parameters, can eventually perform a chain of tasks the user commands and run all the functions in series. Every time you click in a video game to attack, it performs functions to check character's attack, distance, damage, accuracy, critical hit, make a number appear above the enemy's head for the damage dealt. Eventually there is a function that checks if they're dead, and they die. It's all functions being processed inside the game.  

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set Up

Follow these steps to set up your project:

1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test:watch` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Add a viewport meta tag to the head of your index.html page.
* [ ] Add responsive breakpoints to your code for 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Website is responsive at multiple breakpoints and looks good in-between breakpoints because student is using responsive units of measurement where appropriate. Student is using most semantic HTML for each element on page and has included ARIA roles where applicable (More research may be required to impliment ARIA roles)  
* [ ] Student demonstrates and can explain a deep understanding of basic programming concepts, when walking Team Lead through the explaination of their code.
* [ ] Use advanced array methods (.map, .reduce, .filer) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example) - do this seperate from your MVP tasks


## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Please see canvas for cohort specific submission instructions 
