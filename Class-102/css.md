# CSS Notes 

## What is CSS

CSS stands for Cascading Style Sheets, this allows you to create and design your webpages. CSS allows you to modify and customize your webpage to your liking. For example, font, color, size and spacing of your content split into multiple columns and/or add animations. CSS is a languagenfor laying out and structuring webpages, HTML. CSS language has coding elements and is composed of these cascading stle sheets which are equally called CSS files (. css)

## Cascading Order

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default
 So an inline style has the highest priority and will override external and internal styles and browser defaults.

### External CSS

 You can change the look of the entire website by changing one file.
An external style sheet can be written in any text editor and must be saved with a .css extension.

### Internal CSS
An internal stle sheet may be used if one single HTML page has a unique style.
The internal stle is defined inside the < style> element, inside the head section.

### Inline CSS
An inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.


- CSS link goes in the < Head > and below the < title >.

Once you plug in the CSS link, you go to css and breakdown every section.
Body in Css file it correlated to HTML body Tag. First property is going to target the HTML tag. tied to the boyd tag, Body tag you give it rules. 

- Rules: Read from top to bottom, anything from the bottom is overwritten by the the rules on the top. Cascading style sheets.
- a : separates the property from the value, ; teller the rule its done excuting like a period at the end of a sentence. 
- Margin is like the margins on a paper, area before the page starts.
undoing a rule enter in /* */  that disclude from the rule, it ommits it

- padding is gonna be the gap between components next to each other.
- px are pixels when adjusting margin and padding.
- font-family: ; is choosing the font style on the page. 

- targeting ul items at the top of the page.
- ul {}
- getting rid of bullet points 
- li{} list-style: none; to remove the list bullet points.

- Header <--- this ensures just the header color is being modified
- background-color: ; <-- changes background color for header
- height: px; <---- this changes the background color to be the height of color of the box to be 100px
- h1 tag is the logo 
- float: px; forcing it the left, right top bottom. that shifts the h1 in the HTML tag.
- margin-left: px; of that logo. sets the logo X amount of px from the margin.
- margin-right: px; this is giving the gap to the right of the h1
- color: ; changes the color of the h1 font.
- text-shadow: px; gives a shadow to the font of the h1

- nav <----- where the links are,
- < li > < a href>Link 1</ a>< /li>
In HTML these mean:
- < li> - this means links
- < a> this is means anchor which mean we are gonna start here and navigate somehwere else.
- href="" - is the URL
- nav li{ Displa: inline-block } - this means all of the list itmes in the nav section of the HTML follow these specific rules. In this example itll have the listed items going horizontal instead of vertical. 
- margin-top: px; this moved the list  X amount of px from the top of the webpage.
- margin-right: px; this adjust the spacing between list items in the nav list

- nav li a {} this getting more specific, this is saying I want to change all of the anchor tags, the url's are being modified with this specific tag.
- color: this changes the color of the link itself
- text-decoration: none; this is telling the webpage to remove the underline from the link.
- font-size: px; this changes the font size of the link
- font-family: this cjanges the font style of the link
- font-weight: px: sets the weight or boldness of the font.
- cursor: ; changeing the coursor when your mouse hovers over the links 


- nav li a: hover - this means itll over the default state of nav li a links
- color: ; this is the color of the link when hovering over it.
- text-decortation: underline; this underlines the link when hovering over it.
- font-size: px; changed the font size when hovering over it


Hero Image in the Main section
for the hero image to places where we need it to be we need to make modification to main directly.



