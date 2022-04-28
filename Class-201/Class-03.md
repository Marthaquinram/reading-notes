# HTML Lists, Control Flow with JS, and the CSS Box Model

## Lists - ordered list, unordered list, definition list, and nested list.

- < ol> this creates an ordered list.
- < li> is used within the < ol> element to create the ordered list.
- < ul> creats an unordered list. and < il> is within that element
- < dl> definition list is a series of terms and definitions.
- < dt> is used to contain the term being defined
- < dd> is used to contain the definition.
- nested list is where you place a second list inside an < li> element to create a sublist or nested list.

## Box Dimension

- width and height allows you to set your own dimensions to the box.
- Limiting width - min-width, specifies the smallest size a box can be displayed when the browser window is narrow.
- Max-width property indicates the maximum width a box can stretch to when the browser window is wide.
- limiting height - min- height and max-height, this allows you to adjust the min and max height of your box.

## Overflowing

- overflow tellers the browser what to do if the content contained within the box is larger than the box itself. it can have one of two values.
  - hidden - hides any extra content that does not fit box.
  - scroll - adds scrollbar to the box so user can scroll missing content.

  ## Border Margin and Padding.
  
  - border- every box as a border whether its visible or not, it separates one box from another.
  - margin - sits outside the edge of the border
  -padding - the space between the border of a box and any content contained in it.
  

  ## White spaces and vertical margin

  - white spaces add spaces between items on the page and the border.

  ## Borders
  - border width - used to control the width of a border, property can be given either px or values like thin medium and thick. cannot use % with this property.
  - you can control individual sizes of borders with four separate props.
    - border-top-width
    - border-right-width
    - border-bottom-width
    - border-left-width
  - border-style you can control the style of the border.
    - solid line
    - dotted line
    - dashed line
    - doubled line
    - groove line
    - ridge line
    - inset line
    - outset line
    - hidden/ none
    - border-top-style
    - border-right-style
    - border-bottom-style
    - border-left-style



## Arrays
- consider using an aaray whenever working with a list or a set of values that are related to one another.
- array literal
  - colors = [ ' white' 
                'black',
                  'custom'];

## values in arrays

- number items in arrays
  - automatically given a number called index
    - index - 0, 1, 2
    - value - white (0), black (1), custom (2)
- accessing items in arrays
  - to retrieve the third item on the list, the array name is specified along with the index number in the square brackets.

 ## Loops

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

  
