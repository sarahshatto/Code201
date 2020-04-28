Code 201 pre work notes

### HTML BOOK ch. 1

HTML: tags, elements, hypertext markup language
CSS: presentation, layout

Browsers: software to access websites. Safari, chrome, Firefox, etc...
* In order to visit website, users need web address
* Constantly updating web browser versions but not every customer will be running the newest version. 

Web servers: 
* When you ask for a certain website, request is sent across the internet to a special computer known as a web server that hosts the website. 
* Web servers constantly connected to the internet.
* Often a web hosting company is the main source. 

Screen reader:
* Software program that reads the page to a user, often used by those w/ visual impairments. 
* Many laws have been passed to mandate accessibility for websites. 

CMS: content management system

Programming languages: PHP, .ASP.net, Java, Ruby

How the web works: 

To visit a website -
* To find the location of the web server, your browser will first connect to a domain name system server. 
* The dns server searches for the corresponding IP address associated w the domain name. That address will take you to the web server.

HTML elements: whatever is inside the angled brackets. 
Ex: < html > , < body >, < h1 >, etc...

Tags: elements are usually made up of two tags. Opening and closing

Attributes: provide additional info about the contents of an element. 
* Appear in the opening tag and comprised of a name and a value. 
    * Attribute name indicates what kind of extra info and it should be in lowercase. 
    * Attribute value is the info or setting of an attribute. Should be placed in double quotes. 

Elements: 
< body >
< head > contains certain info about the page. Usually find the < title > element in here. 
< title > either shown in the top of the browser or on the tab of the page. 



### HTML BOOK ch. 8

Doctypes: because there are so many versions of html, each web page should begin with a DOCTYPE declaration to tell a browser which version of html the page is using. Can help the browser to render a page correctly. 

Comments in html: <!- -  - -> : If you want to add a comment to your code that will not be visible in the users browser. 

ID attribute: every html element can carry the ID attribute. Used to uniquely identify that element from other elements on the page. It’s value should start with a letter or an underscore.  Ex: <p Id= “pullquote”>

Class attribute: every html element can also carry a class attribute. A way to identify several elements at a time. Ex: <p class=“important admittance”>

Block level elements: some elements will always appear to start on a new line in the browser window. Examples, < h1 >, < p >,< ul >, < li >

-vs-

Inline elements: some elements will always appear to continue on the same line as their neighboring elements. Ex. < a >,< b >,< em >,< img >

Grouping text and elements in a block:
< div > allows you to group a set of elements together in one block level box.
Ex: Creating a < div > element to contain all of the elements for the header of your site, like the logo and the navigation

< span > commonly used with specific css to differentiate from other text, an inline equivalent of the < div >

Iframe: small window where you can see another page. Commonly used for google maps being embedded into a page. 

< meta > meta element lives inside the head element, and contains information about that webpage. It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it and whether or not it is time sensitive.￼￼


### HTML BOOK ch. 17

###html5 layouts
Headers and footers can be used for: the main header or footer that appears at the top of the page on the site.

 Navigation < nav > element used to contain the major navigational blocks on the site such as the primary site navigation. 

Articles < article > acts as a container for any selection of a page that could stand alone and potentially be syndicated. Ex. Individual article, blog entry, comment or forum post.

< aside > two purposes, depending on whether it is inside an < article > element or not. 
When used inside an article tag, 

< section > dissection element groups related content together and typically each section would have its own heading. Example: on a homepage there may be several section elements to contain different sections of the page such as latest news top products and newsletter sign-up. 
* Because the section element groups related items together it may contain several distinct article elements that have a common theme or purpose.￼


### HTML BOOK ch. 18
Target audience: 

Target Audience
* WHY
    * Key motivations for visiting your page
    * is there a specific goal or just for general entertainment?
    * do they see spending time on this activity as essential or a luxury?
    * do they want general info?
    * are they already familiar with the service or product?
    * Are they looking for time sensitive info?
    * Do they want general info?
    * How familiar are they with the product or service?
    * Are they looking for time sensitive information?
* WHO
    * Target audience // individuals
        * Age range
        * gender
        * location
        * marital status
        * device used to access page
        * urban or rural
        * average income
        * level of education
        * occupation
    * Target Audience // Companies
        * What is the size of the company?
        * position of the person viewing your content
        * will visitors be using the site for themselves or for a client ?
        * How large is overall budget?
* WHAT
    * What are users trying to acheive?
    * what info do they need?
    * level of existing knowledge?
* HOW
    * How often will people visit your website?
    * How often will your services change?
Site Maps
* used to organize the information into sections or pages.
* Card sorting type system in order to visually organize the different pages in a website and how they relate to one another.
Wireframes
Simple sketch of key info that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require. 

Using design to help express your message 
Visually differentiating between logos, navigation bar, articles, login options
Important to prioritize by creating a visual hierarchy. 
Organizing via grouping similar or related content into blocks or chunks.
When organizing, consider tools like size, color, and style. Visual hierarchy and visual contrast.
Gestalt laws of proximity, closure, continuance, negative space... color and borders. 


### JAVASCRIPT CH. 1

Script: series of instructions that a computer will follow to achieve a goal. 
First step in writing a script is to state your goal.
Then list the steps necessary to get there. 

Every step for every task needs to be written in a language the computer can understand and follow. 

Vocabulary: the words that computers understand
Syntax: how you put those words together to create instructions for computers to follow. 

Sketching out the tasks necessary in a flowchart. 

Computers create models of the world using data. 
The models use objects to represent physical things. 
Objects can have: 
properties that tell us about the object; 
methods that perform tasks using the properties of that object; 
events which are triggered when a user interacts with the computer. 

Objects and properties 
Objects (things) : physical things represented in code as one instance of something. Every object can have its own properties, methods and events.

Properties (characteristics) 
Can be used to define an object. Ex: car - properties may include make, color, engine size, current speed. 

Properties always have a name and a value. 

Events
Programs are designed to do different things when users interact with the computer in different ways. Ex: when clicking on a link, the browser brings up a contact form.

Method: questions and instructions that 
-tell you something about that object using info stored in properties
- change the value of one or more of that objects properties 

Programmers can write code to express that when a specific event occurs it triggers a certain line of code to run.

Web browsers use HTML markup to create a model of the web page. Each element creates its own node (kind of object)

To make pages interactive, you write code that uses the browsers model of the web page. 

JavaScript runs where it is found in the html and runs top to bottom

It’s best To keep JavaScript code and it’s on JavaScript file. JavaScript files or text files just like HTML pages and CSS style sheets, but they have the .js extension.￼

The HTML script element is used in HTML pages to tell the browser to load the JavaScript file.

If you view the source code of the page in the browser, the JavaScript will not have change the HTML, because the script works with the model of the webpage that the browser has created.￼￼