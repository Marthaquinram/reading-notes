# HTML Notes Lab 4

## WireFrame
Wireframes is a clear visual representation of a web page or layout.  Wireframes can be drawn with pencil and paper, or with a whiteboard. Using pencil and paper or a whiteboard allows for easy corrections and modifications. This allows for testing at every stage of the design and ideation. Project managers and web designers use wireframes to capture what a client is requesting their website/mobile app to look like. once the designing is completed and the end user is satisfy, this gets distributed to the software developers to start working on the coding side of things to make the website come to life. during this stage is where we find out what works and what doesnt.

## HTML

Next up is HTML. What is HTML?
HTML stands for Hypertext Markup Language and it defines the structor of your content. HMTL consist of elements and tags.
 
 **Element**: https://developer.mozilla.org/en-US/docs/Glossary/Element/anatomy-of-an-html-element.png

**Tag**
An HTLM tag is another word or letter surrounded by brackets like < and >. You use tags to create elemeents like links,paragraphs or list. Many elements have an opening tag and a closing tag.

Examples:
1. HTML is the root element. This is the root of the tree of elements that make up the web page.
<html> Hi (all other page elements go here)
</html>

2. The document Head

<head> Hello </head> This contains info about the web page that was created. Elements that can go inside the head are things like Titles, links, images.

Title, this will be The web page title<title> Llamas and Alpacas of the world </title>.

3. The page's content. This is where all your images and text will go, this is the body of the page.
<body> content of pages displayed here </body>

4. A Link.
Links allow you to enter URLs that can lead you to other pages and content. 
<a>www.ilovealpacas.com</a>

5. An image
Img elements allow you to add photos to your web page. in order to insert and image you must obtain the image address first and you can add an alt attribute after to show the title of image if it cant be displayed.
<img src="alpacaphotos . jpg" alt="alpacas">

Now put it all together

<html>
  <head>
    <title>lamas and Alpacas of the world</title>
    <link > helloalapacas link here
    </link >
  </head>
<body> content of pages displayed her 
<img scr= "<img src= "photo here" >
</body>
</html>