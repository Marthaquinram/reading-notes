# Table
- A table represents information in a gride format. Like tables include financial reports, TV scheds. sports results.
- each block in a grid is a a **table cell.**

## Basic Table Structure
- < table> is used to create a table. The contents of the table are written row by row.
- < tr> you indicate the start of each row using the opening < tr> stands for **Table Row** followed by one or more < td> and then close tag < /tr>.
- < td> each cell of a table is represented using a < td>. td stands for **Table Data**.


## Table Headings
- < th> is used just like < td> but the purpose is to represent the heading for either a column or a row. Th stands for **Thable Heading**.


## Spanning Columns and Rows
- < td colspan="2"> Geography< /td> colspan is used to indicate how many columns that cell should run accross.
- < td rowspan="2"> Movie< /td> rowspan indicates how many rows a cell should span down the table.

## Long Tables
- < thead> the heading of the table should sit inside the < thead> element.
- < tbody> body should sit inside the < tbody> element.
- < tfoot> the footer belongs inside the < tfoot> element.


## Object Constructor
- The Object constructor creates an object wrapper for the given value.
- Updating an object, to update value of a property use dot notation or square brackets. 
ex: hotel.name = [ ' park']; 
hotel - is the object, . is the member operator name - is the property name = is the assignment operator and park is the property value.
- += operator is used to add content to an existing varialbe.

### Create the object then add properties and methods
- Literal Notation - the object is created on the first line of the code ex. the properties and methods are added to it afterwards.
- let hotel = {}
  - hotel.name = 'Quay'
  - hotel.room = 40;
  - hotel.book = 25;
  - hotel.checkAvailability = funtion(){
    - return this.rooms - this.booked;
  };

  - Object Construtor Notation - once you created object the syntax for adding or removing any properties and methods from that object is the same.
  - let hotel = new Object ();
    - hotel.name = 'Quay';
    - hotel.rooms = 40;
    - hotel.booked = 25;
    - hotel.checkAvailability = function(){
      return this.rooms - this.booked;
    };

### Creating an object with properties and methods
- Literal Notation - a colon separates the key/value pairs. comma between each key/value pair.
- let hotel = {
  - name: 'Quay'
  - room: 40;
  - book: 25;
  - checkAvailability: funtion(){
    - return this.rooms - this.booked;
  }
  };

- Object Constructor Notation - the function can be used to create multiple objects. The *this* keyword is used insted of the object name.
  - function Hotel (name, rooms, booked){
  - this.name = name;
  - this.rooms = rooms;
  - this.booked = booked;
  - this.checkAvailability = function(){
    - return this.romms - this.booked;
  };
}
- let quayHotel = new Hotel('Quay', 40, 25);
- let parkHotel = new Hotel('Park', 120,77);
