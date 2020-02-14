# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages:

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

        Basically Semantic HTML is the use of HTML elements to easily be able to tell the difference between elements. It is used to separate different parts of the markup from each other, so it is easier to edit or add to, and it enables a programmer to stylize the program with CSS.

2. Name two big differences between ```display: block;``` and ```display: inline;```.

        The main difference is the line break. A Block element will always have a line break after the element (it goes to a new line and starts the next element there). An inline element will not line break, and the next element will continue on the same line as it, allowing elements to sit next to each other.

        Another difference is that block elements can have margins all around, however inline elements will only apply the left and right margins, ignoring the top and bottom.

3. What are the 4 areas of the box model?

        Content: The content of the box (most of, if not any of the elements)
        Padding: The area around the content. Allows a programmer to set space between the content and border
        Border: A border that surrounds the padding. Requires 3 values (width of border, border style, and color)
        Margin: The invisible space between the inner areas and other content


4. While using flexbox, what axis does the following property work on: ```align-items: center```?

        It aligns the items on the Y-axis. 
        It will align items from:

            item        item                    item                    item
            item                    item                                item
            item                                            item        item
        
        to
            item                                                        item
            item        item        item        item        item        item
            item                                                        item
    

5. Explain why git is valuable to a team of developers.

    Git allows a team to access all of the same files, upload to the same project, work on and modify the same content, and roll back to a previous point in the program (if necessary)

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

- [yes] Create a forked copy of this project.
- [yes] Add your project manager as collaborator on Github.
- [yes] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [yes] Create a new branch: git checkout -b `<firstName-lastName>`.
- [yes] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [yes] Push commits: git push origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your project manager as a reviewer on the pull-request
- [ ] Your project manager will count the project as complete by merging the branch back into master.
 


## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [yes] Build the HTML and CSS to create the missing navigation and header.
* [yes] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [yes] box1: `teal`
* [yes] box2: `gold`
* [yes] box3: `cadetblue`
* [yes] box4: `coral`
* [yes] box5: `crimson`
* [yes] box6: `forestgreen`
* [yes] box7: `darkorchid`
* [yes] box8: `hotpink`
* [yes] box9: `indigo`
* [yes] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [yes] Copy and paste your home page navigation and header into the about page
* [yes] Update the header image with the about page image
* [yes] Link the `Home` navigation item back to the `index.html` page.
* [yes] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Build a page of your choosing from the navigation items.  Come up with content and images that fit the theme.  
* [ ] Introduce CSS animations to your site.
* [ ] Build a contact page and create a form with several inputs of your choosing
* [ ] Add responsive breakpoints to your code by using media queries
