# CSS Positioning Codepens

#### Description
Using what you learned in lecture and reading, re-create the following layouts in separate Codepens that you can share tomorrow in class.

#### Objectives
- Understand the CSS box model and how it applies to HTML elements
- Understand and implement the differences between different "display" types in CSS".
- Understand and implement the different types of CSS positioning.
- Identify the uses for and differences between CSS reset and Normalize

#### Performance Objectives
After completing this assignment, you should be able to effectively use

- Create and Fork a Codepen
- Effectively implement and understand the 4 types of CSS positioning using the CSS Box Model

#### Details

Deliverables

- Students should save Codepen links and email them to abby@theironyard.com.

#### Exercises
1. Create a new Codepen
- Make a div with a class of "container" that will contain all of your future divs.
- Give the container div a:
    + Width of 90% at any screen size, but is 960px at maximum size
    + Padding of 20px, but the container should not have a maximum width more than 960px including padding
    + Background color of #cccccc
- Center the container div
- Add 2 new divs inside of the container div; one with a class of "left-col" and one with a class of "right-col"
- Both divs should have a width of 50% and a height of 200px
- "left-col" should be floated left and have a background of #2B7F7B
- "right-col" should be floated right and have a background of #07CCC1
- "container" should wrap entirely around both "right-col" and "left-col"
- Save the pen and copy the link somewhere.

2.  Start a new pen by forking the one you just created
- After forking, add a new div with a class of "main" that has the same height as "left-col" and "right-col"
- Give "main" a background of #993654
- "main" should appear below "left-col" and "right-col" and span the width of "container"
- below "main" add 3 divs with the class of "thirds" with a height of 200px
- "thirds" should have a background of #332546, floated left, with a 2% margin on the center div

-  For the following exercises, use these hexcodes:

- Grey: #cccccc
- Blue: #258aa5
- Purple: #e50e56
- Pink: #554466

3.  Create the following layout using relative positioning:
     ![Codepen Image 1](/Curriculum/images/relative.png)

4.  Create the following layout using absolute positioning:
     ![Codepen Image 2](/Curriculum/images/absolute.png)

5.  Create the following layout using fixed positioning (the pink box should remain in view while scrolling):

     ![Codepen Image 3](/Curriculum/images/fixed.png)

#### Hard Mode
- Create your codepen in steps 1 & 2 with 41 or less lines of well-formed CSS and no additional classes except for the ones defined in the instructions
- Create the first and second layout images with margin instead of positioning