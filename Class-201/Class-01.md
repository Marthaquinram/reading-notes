# Code 201 Reading Notes

## *Jon Duckett HTLM & CSS Book*

### **Structure**:
HTML describes the Structure of the pages
- HTML stands for Hypertext Markup Language and it defines the structor of your content. 
- The standard HTML Elements consist of an opening tag and a closing tag eg. <> </> (The forward slash indicates that the tag is closed) attributes of the tag and the content within the tags.

**Tag**
- A tag is another word or letter surrounded by brackets like < and >. You use tags to create elemeents like links,paragraphs or list. The characters within the brackets indicate the purpose of the tag.

**Attributes**
- An attribute is made up of two parts a **_name_** and **_value_**separated by an equal sign. Example: name="value"
- Attribute name should be written in lowercase and its indicating what information you are providing about the elements content.

- < html >

  < head >

    < title >
 Title of page
    < / title >

    </ head >

< body> 

< h1 > here is the body of page </ h1>

< p > displayed here will be main browser </ p>

</ body>

</ html>

## Extra Markup

### Doctypes
- Doc Type declaration is placed at the top of the page, this tells the page which version of HTML you are using. < ! DOCTYPE html>

### ID Attribute
- ID attibutes is used to specify a unique id  for an HTML element. It identifies it from other elements on the page.
- ID adttribute is also known as global attribute since it can be used on any element.

### Class Attribute
- A class attribut is used to identify multiple elements being different from the other elements on the page.

### Block Elements
- Block elemet starts on a new line, browers add some space before and after the element. 
- Examples of block elements are: < p>, < div>, < h1>, < ul>, < il>

### Inline Elements
- Inline element does not start on a new line. Everything will appear to continue on the same line as the element next to it. 
- Examples of inline elements are: < a>,< b>, < em>, and < img>

### Grouping Text & Elements in a Block
- < div> elemet defines a division or a section in the HTML document. This element is used as a containt for HTML elements and that gets styled with CSS.
- Using an id or class attributes on the < div> elements makes it so CSS can be used.
- use a closing < /div> tag.

### Grouping Text & Elemenets Inline
- The < span> tag is an inline container used to mark up a part of a tex or a part of a document.
- < span> is commonly used for controling the appearance of the content using CSS.
- Usually seen with class or id attributes, explain the purpose of this < span> elements, so that CSS styles can be applied to elemenets that have specifi values for these attributes.

### iframes
- < iframe> tags specifies an inline frame, and its used to embed another document within the current HTML doc.
- src - specifies the URL of the page shown in frame.
- height - attribute specifies the height of the iframe in pixels.
- width- attribute specifies the width in pixels

#### Meta
- < meta> tags defines metadata about the HTML document. (Information) about.
- The meta tag always go inside the < head> element, and used to specify character set, page description, keywords , author of the doc and view port setting.

### Escape Characters
- < less-than sign,
- > greater-than sign
- & ampersand sign
- "" Quotation mark
- ' left side signle quote
- ' right side single quote
- " left double quote
- " right double quote
- x multiplication sign

### HTML5
"HTML5 introduces a new set of elements that allow you to divide up the parts of the page.The names of these elements indicate the kind of content you will find in them. They are still subjext to change, but that has not stopped many web page authors from using them already." (HTML&CSS design and build websites, page 432)[Jon Ducket]
 




# JavaScript & Jquery

 -