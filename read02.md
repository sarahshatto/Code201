Notes on read02

### CHAPTER 2 (40-61)

HTML elements are used to describe the structure of the page (ex. Headings, subheadings, paragraphs)

they also provide semantic information (ex. Where emphasis should be placed, the definition of any acronyms used, when given text is a quotation)


### CHAPTER 10 (226-245) 

CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.

Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like.￼￼)

Different types of selectors allow you to target your rules at different elements.

Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies arial is the preferred typeface.￼￼

CSS rules usually appear in a separate document, although they may appear within an HTML page.

### JS BOOK: CHAPTER 2 (53-84) 

A script is made up of a series of statements. Each statement is like a step in a recipe.

￼ scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.

Variables are used to temporarily store pieces of information used in the script.

Arrays our special types of variables that store more than one piece of related information.￼￼￼

JavaScript distinguishes between numbers 0–9, strings (text) and Boolean values (true or false￼).

Expressions evaluate into a single value.

Expressions rely on operators to calculate your value.

### JS BOOK: CHAPTER 4 (145-162) 

Evaluations￼
Decisions :
- there are several places in a script where decisions are made that determine which lines of code should be run next. Flow charts can help you plan for these occasions.
- There are two components to a decision: an expression is a valuated which returns a value and a conditional statement says what to do in a given situation.
- ￼￼
loops￼


- Javascript makes websites more interactive and user friendly.
  - by accessing and modifying content/markup used in a web page while its being viewed in the browser.
  - can change new CSS rules. 
  - change the size of an <img> element. 
  - you can set up a set of instructions that will change the content. 
    - Ex: Pictures that get bigger when you click on them
  - React to certain user input
    - Button is pressed
    - link is clicked
    - cursor hover
    - info added to a form
    - webpage loading


#### Examples of Javascript in the Browser 
- Access the content of page
- modify the content of a page
- program rules/instructions browser can follow
- react to events triggered by the user or broswer.

### Slideshows (ch. 11)
-  can display multiple images in the same space and can play automatically or user clicking through. 
  - Example: 
    - React- script is triggered when page loads
    - Access- Get each slide from the slideshow
    - Modify- only show the first slide...

### Forms: 
- Validating whether forms have been filled out correctly. 
- Javascript lets you alert the user if there are mistakes. 
- sophisticated calculations 
  - Example
    - user presses submit button after name entry
    - access: get value from form field. 
- Reload only part of a page for speed 
- Filtering data from user input


## Script
-  Series of instructions that the computer will follow to achieve a goal.
  - First step in writing a script is to state your goal.
  - Then list the steps necessary to achieve that goal. 
  - Code your steps. 

Example page 18-19

## Defining a goal and designing a script 

- define your goal
- break into a series of tasks
  
  Flowcharts and examples on page 23


## Expressions: 

- page 74-79

- Expression evaluates into (or results in) a single value. 
  - Two types of expressions: 
    - Expressions that assign a value to a variable. 
      - Gives variable a value via the assignment operator. 
      - var color = 'beige'; 
    -Expressions that use two or more values to return a single value. 
      - var area = 3 * 2;   

## Types of operators:

- Operator: Allows programmers to create a single value from one or more values. 

Types of Operators: 
  - Assignment Operators: Assign a value to a variable.
    - color = 'beige'; 
    - pg. 61 
  - Arithmatic Operators: perform basic math
    - area = 3 * 2; 
    - pg 76
  - String operators: Combines two strings
    - greeting = 'Hi' + 'Molly'
    - pg 78
  - Comparison Operators: Compares 2 values and returns as True or False
    - buy = 3 > 5; 
    - pg 150
  - Logical Operators: Combines expressions and returns as true or false. 
    - Page 156

## Functions pg. 88-94: 

- Functions let you group a series of statements together to perform a specific task. If different parts of the same task, you can reuse the same function. 

- wraps an area/group of code so that it does something. Ex: function (TriviaTime)

- If you want your tasks to happen later, you need to name them. 
  - it should describe the task it's performing.
  - when you ask it to perform its task - it's calling the function. 

- Steps that a function needs to perform in order to perform the task are packaged up in a code block. 
  - refresher: code block consists of one or more statements within curly brackets. 

- Some functions need to be given info in order to complete a task. 
- pieces of information passed to a function is called "parameters". 

-When you write a function and you expect it to provide you an answer, the response is known as a return value. 

1. First, you must declare the function. Give it a name and then write the statements needed to acheive taks inside the curly brackets. 

1. Call the function: after declaring the function, you can then execute all of the statements between curly braces with just one line of code. 
