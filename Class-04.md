# Class-04 Reading Notes

## Chapter 4 "Links"

- To create a link you need to use the < a> element. Users can link on anything in between the opening < a> tag and the < /a> tag. then you can specify what page its linking to using the href attribute.

### Linking
- Linking to other sites, the value of the href attribute will be the full web address for th site, which known as an **absolute** URL
ex: < a  href = " www.ilovealpacas.com /abc">
- Linking to other pages on the same site, you dont have to specify the domain name in the url you can use shorthand known as a relative URL. ex: < a href="ilovealpacas.html">

### Directory Structure
- structure - top level known as *root folder*, this contains all the other files and folder for a website.
- Relationship - between files and folders on a web page described using the same terminology as a family tree.
The root folder is the parent folder for different folders/files within it. EX from (Jon Duckett book HTML &CSS, Page 82.) "The **examplearts** folder is a parent of the **movies, music** and **theater** folders. and the **movies, music** and **theater** folders are *children* of the **examplearts** folder."

### Relative URL
- Linking to other pages on the same site, you dont have to specify the domain name in the url you can use shorthand known as a relative URL. ex: < a href="ilovealpacas.html">
Ex: grandparent folder < a href="../../index.html">Home< /a>

### Email Links
- Mailto, < a href="mailto : martha@ example.org"> Email Martha< /a>

### Opening links in different window.
- if youre wanting a link to open in a new window youll need to use the taget attribute on the opening < a> tag. value of the attribute is _blank.
Ex:< a href="https://www.google.com" taget="_blank"> Google < /a> (opens in new window) be sure to let the user know that the link opens in a separate window.


# Layout Chapter 15
#### Key concepts in positioning elements
- Building Blocks - "CSS treats each HTML elemnet as if its in its own box. THis box will either be a **block-level** box or an **inline** box Block lever boxes start on a new line and act as the main building blocks of any layout. while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too) To separate boxes, you can use borders, margins, padding, and background colors." (HTML&CSS design and build websites, Chapter 15 page 361)[Jon Ducket]
- Containing Elements - "If one block-level element sits inside another block-level elment then the oter box is known as the containing or parent element." (HTML&CSS design and build websites, Chapter 15 page 362)[Jon Ducket]

- Positioning Schemes
 - Normal flow - the paragraphs appear one after the other, vertically down the page.
 - Relative positioning - second paragraoh has been pushed down the right from where it would otherwise have been in normal flow.
 - Absolute positioning - the heading is positioned to the top right and the paragraphs start at the top of th screen as if the heading were not there.
 - Fixed positioning - The heading has been placed in the center of the page and 25% from the top of the screen. The rest appears in normal flow.
 - Floating elements - the heading has been floated to the left allowing the paragraphs of text to flow around it.


 # JS Functions
- Functions are a way that we can categories or break down our code so only bits and pieces run.
- Usually JS runs from top to bottom
- group together code some kind of objective. we choose which ones to run. Functions are like receipes. bunch of actions that are group together.
- example:
  - function yourName(){
  - let name = prompt(' what is your name?');
  - console.log('Hello, ' + name)
}
- functions do not run until you call them
we can call our function - yourName();
git parameter ( these are the ())
- give it logic 
- give it a return

- let answer = prompt(' what is the name of martha\s dog?'); // Papaya

* === means its the exact strict answer
* == kinda equal truthy and a falsey
* if (answer ==== papaya ); {
* console. log (' great job! you are correct !' )
}

* !== means NOT EQUAL 
* ! is a (bang ), and that means NOT


* answer.toLowerCase ( ) normallizing the formating of the content.
* || means or : only one of the conditions in the statement has to be true

* && means AND : both or all conditions have to be true
