### Reading Notes: Problem Domain, Objects, and the DOM.

What is the hardest thing about writing code?

- Learning a new technology
- Naming things
- Testing your code
- Debugging
- Fixing bugs
- Making software maintainable

Sonmez, J (2013) [Simple Programmer]. https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming

### What's the difference between Primitive Values and Objects reference in JS

 JavaScript can be put into one of two catergories : **Primitive values** and **Object references.**

 - Primitive Values - is data that is not an object and has no methods. they store the actual value;
  - 7 primitive data types : string, number. bigint, boolean, undefined, symbol, and null.
- Objects References - they store the addresses of the objects they refer to. Its a variable that points to an object of a given class, letting you access the value of an object.

- A variable thats part of an object is called a **property**. This tells us about the object, like name  of a building or the number of the rooms.
- In objects functions become known as **"methods"**
- Methods rep. tasks that are associated with the object. EX: check how many rooms are available by subtracting the number of booked rooms fromt he total number of rooms.
- Properties and methods have a name and a value, In an object that is called **key**.
- object cannot have 2 keys with the same name.
- value of a property can be a string, boolean, array, or another object. the value of a method is always a function.
- Properties are variables.
- Method is a function
- object is the  curly braces and their content. the objects stored in a variable is called a hotel. 
- separate each key from value using colon. separate each property and method with a comma.

### Accessing an Object and Dot Notation.
-  access the property or methods of an object using dot notation.
- also access properties using square brackets [ ].
- Ex: var hotelName = hotel . name;
hotel is the object and name; is tje property/method name
the period is called member operator.

### DOM Tree
- is a model of a web page.
- Dom tree is stored in the browsers memory.
- it consist of four main types of nodes.
- document node - every element and attribute  and text in the HTML is represented by its own DOM node. at the top of the tree a document node is added.
- Element node - Html elements describe the structure of an HTML Page

Will update notes with more info once i learn more in class
