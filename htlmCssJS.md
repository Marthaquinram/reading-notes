# Basics of HTML, CSS & JS

**Structural Markup**: " The elements that you can us to describe both headings and paragraphs."
(HTML&CSS design and build websites, Chapter 2 page 41)[Jon Ducket]

**Semantics Markup**: " Which provides extra information; such as where emphasis si placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on". 
(HTML&CSS design and build websites, Chapter 2 page 41)[Jon Ducket]

## Headings

- HTML has 6 levels of headings
  - < h1> : Largest heading - used for main headings
  - < h2> : Second largest heading - used for subheadings
  - < h3> : Third largest heading  - follows after any subheadings
  - < h4> : Start getting small heading  
  - < h5> : Smaller heading 
  - < h6> : The smallest heading.



## Paragraphs

  - < p> - this is used to create a paragraph and follows with a closing < /p> when paragraph is completed. 
  - using < p> tags makes text easier to understand when its split into sections.

## Bold & Italic

  - < b> - an open and closed b tag will make whatever is within it  **BOLD**.
  - < i> - an open and closed i tag will make whatever is within in it *ITALIC*.

  ## Superscript & Subscript

  - < sup> - is the small letter or number ABOVE the letter or number EX: 2<sup>2</sup> or 2<sup>nd</sup>
  - < sub> - is text which a small letter or number is written after a particular number or letter that hangs BELOW the number or letter. EX: H<sub>2</sub>O.


## White Space

"When the browser comes accross two  or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as *white space collapsing.*" (HTML&CSS design and build websites, Chapter 2 page 47)[Jon Ducket])

## Line Breaks & Horizontal Rules

- < br /> - you will use this tag when you want to add a break in the middle of a paragraph.
- < hr /> - Adds a horizontal line  between sections.

# Semantic Markup

### Strong & Emphasis

- < strong> element is indicating the importance of something, it has a strong emphasis with whatever is within the element.
- < em> is subtly emphasises something, that could change the meaning of a sentance. It italicize the content within the element.

### Quotations

- < blockquote> - elements indicates that the enclosed text is an extended quotation. Visually by indentation.
- < q> is used for shorter quotes thats within a paragraph. The book goes on to say that browsers are supposed to put "" around the < q> element, but IE does not, and many people avoid using the < q> element.

### Abbreviations & Acronyms

- < abbr> element reps an abbreviation or acronym, the optional title attribute can provide an expansion or description for the abbreviation.

### Citations & Definitions

- < cite> used to describe a reference to a cited work, like movies, book, or research page. 
- Browsers will render the content of a < cite> element in italics.


### Changes to Content

- < ins> can be used to show content has been inserted into document. This elements is usally underlined.
- < del> can show text that been deleted from it. This elemenet usually has a line through it.

# CSS 

- CSS stands for Cascading Style Sheets, this allows you to create and design your webpages. CSS allows you to modify and customize your webpage to your liking. For example, font, color, size and spacing of your content split into multiple columns and/or add animations. CSS is a language for laying out and structuring webpages, HTML. CSS language has coding elements and is composed of these cascading stle sheets which are equally called CSS files (. css)
- CSS rule contains two parts; a selector and a declaration.
  - Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the elements names with commas.
  - Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts ( a property and a value), and are separated by a colon.
- CSS Declarations are inside curly brackets {} and they are made of two properties: a *property* and a *value* separated by a colon.
  - Example from book : h1. h2, h3 {
    font - family: Arial;
    color: yellow;
  }
color - is the propert and yellow - is the value.

### External CSS

 You can change the look of the entire website by changing one file.
An external style sheet can be written in any text editor and must be saved with a .css extension.
- href="" - is the URL It's the source of the file used by the tag. You can use both not only when connecting an external css file, also for using < a> tags,for a regular hyperlink.
- type - this attributes specifies the type of document being linked. the value should be text/css.
- rel - this specifies the relationship between the HTML page and the file it is linked to.The value should be stylesheet when linking to a CSS file.

### Internal CSS
- An internal stle sheet may be used if one single HTML page has a unique style. The internal stle is defined inside the < style> element, inside the head section.


### Selectors

- CSS selectors are the first part of the CSS rule. Its a pattern of elements and terms that tell the browser which HTML elements should be selected to have the CSS property Values inside the rule apply to them.


# Basic JavaScript Instructions

### Statements

- 
-
-



### Comments

-
-
-

### Variables

-
-
-

### How to declare Variables

-
-
-

### How to assign Variables value

-
-
-

# Data Types

- Objects / arrays
- strings
- boolean
- numbers

## What are data types

- a type of data
- a way of formatting data that the computer can anticipate
  - ex: do you have a dog? Yes/No (Boolean)
  - ex: How old is your dog? (number)

  # Loops

- Are the ability to repeat an action a set/some number of times.
- Guess a number between 1-100; or you can do trivia, ex. you have 3 attmepts to answer this question:

- How many cats do I have? <----- infinate amount of outcomes.

- simple structure/algorthim to solve the ability to repeat behanvior/loop

### 3 loops 

- while 
- do.. while
- for **

- start every while lop with "while"
- while(condition)
- whiles dont need a numeric condition.

cons: you control when it exits.
