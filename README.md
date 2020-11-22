# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from a `JSON` object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Preprocessing, and JavaScript Basics.

> You have **three hours** to complete this challenge. Plan your time accordingly.

## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You are free to work with the full data set as a stretch goal.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. How would you describe acessibility on the web to someone new to programming?

    Acessibility on the web is important as it allows those with disabilities or different viewing devices to engage in the website. There are ways to write html code and css which help to make websites more accessible. One person may only be viewing a website on a desktop screen while another may primarily use their cellphone or tablet to view websites. A person with a disibility may only be able to engage in a particular website through a screen reader. So, when developing a website, one must take into account their audience and what would make the website more accessible to them.

2. Talk about 3 different things you can do to ensure your website is accessible. 

    2.a -- Media Queries -- Building a website so it is accessable on all screen sizes allows more users to navigate the website. If one builds a website strictly for one screen size, they will be excluding a very large audience. Every website should look good on a cell phone, tablet, and desktop computer.

    2.b -- Semantic Html -- Writing html code should be written and labled in a way that anyone can understand it. It is very important for screen readers to have the html structured and labled correctly so it can follow and read it as expected.

    2.c -- Color Contrast -- Some people see colors differently than others. Some people are even color blind. So, it is important that colors have a good amount of contrast with eachother so the viewing experience is more readable.

    2.d -- Clean Dry Code -- Writing code in any programming language should be done in a way that another programmer can understand it should they ever need to edit it. Variable, named functions, classes, objects, should all have names which makes sense to the user viewing the code.

3. How would you explain the concept of a variable to someone new to programming?
    A variable is a placeholder for a type of data. It can be used to hold strings of text, numbers, and other data types. They can be used later on in the code by refering to the variable name.
    
4. What is the purpose of using functions in code?
    The purpose of a function is to hold a block of code which performs tasks that are written inside of the function. If the task is a repetitive one, the function can simply be invoked by its function name instead of having to rewrite all the tasks inside the function again. The purpose of this is to not repeat code.  

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