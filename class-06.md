# Read-06
## Chapter 3: “Object Literals”
### What is the hardest thing about writing code?
### There are many common answers to this question:

1.Learning a new technology
2.Naming things.
3.Testing your code.
4.Debugging.
5.Fixing bugs.
6.Making software maintainable.

### WHAT IS AN OBJECT?
**An object is a series of variables and functions that represent something from the world around you.**  
-In an object, variables are known as properties of the
object; functions are known as methods of the object.
Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window. 

how to creat an object ?
1.literal notation : example here is the hotel object
var hotel={
name: 'Quay',
rooms:40,
booked:25,
checkAvailability: function(){
    return this.rooms - this.booked;
}
;}
* accessing an object and dot notation:
var hotelName=hotel.name;
var roomsFree=hotel.checkAvailability();

## Chapter 5: “Document Object Model”
1. The browser represents the page using a DOM tree.
2. DOM trees have four types of nodes: document nodes,element nodes, attribute nodes, and text nodes.
3. You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.
4. Whenever a DOM query can return more than one node, it will always return a Node list.
5. From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.
6. An element node can contain multiple text nodes and
child elements that are siblings of each other.
7. In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).
8. Browsers offer tools for viewing the DOM tree . 
