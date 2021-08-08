# Object

### WHAT IS AN OBJECT? 
Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names.

IN AN OBJECT: VARIABLES BECOME 
KNOWN AS **PROPERTIES**

IN AN OBJECT: FUNCTIONS BECOME 
KNOWN AS **METHODS**

### creating an object literal notation 

literal notation is the easiest way to create an object

the **object** is the name of the object

the **key** is the properties of the object

the **value** is the method and what the method returns.

![object](https://miro.medium.com/max/1400/1*GA7toY-Y3a3l0nlewOxIAw.png)

# Document Object Model

The Document Object Model (DOM) specifies 
how browsers should create a model of an HTML 
page and how JavaScript can access and update the 
contents of a web page while it is in the browser window. 

### WORKING WITH THE DOM TREE 

Accessing and updating the DOM tree involves two steps: 

1. Locate the node that represents the element you want to work with. 
2. Use its text content, child elements, and attributes.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT9GTdSC924I39i7NZHc-Tu0LN8zR-A7TCuGpPO393-1a1GxFRMNLGhe3b9tq00SY86B3Y&usqp=CAU)

## SELECTING ELEMENTS USING ID ATTRIBUTES 

get El ementByi d () allows you 
to select a single element node 
by specifying the value of its 
id attribute. 

This method has one parameter: 

the value of the id attribute on 
the element you want to select. 
This value is placed inside quote 
marks because it is a string. The 
quotes can be single or double 
quotes, but they must match. 

In the example on the left, the 
first line of JavaScript code finds 
the element whose id attribute 
has a value of one, and stores 
a reference to that node in a 
variable called e 1. 

## SELECTI NG ELEMENTS USING CLASS ATTRIBUTES 
The get El ementsByCl ass Name() 

method allows you to select 
elements whose c 1 ass attribute 
contains a specific value. 

The method has one parameter: 

the class name which is given 
in quotes within the parentheses 
after the method name. 

Because several elements can 
have the same value for their 
cl ass attribute, this method 
always returns a Nodelist

## SELECTING ELEMENTS 
BY TAG NAME 
The get El ementsByTagName () 
method allows you to select 
elements using their tag name. 

JAVASCRIPT 
The element name is specified 
as a parameter, so it is placed 
inside the parentheses and is 
contained by quote marks. 

Note that you do not include the 
angled brackets that surround 
the tag name in the HTML (just 
the letters inside the brackets). 

## ADDING ELEMENTS USING DOM MANIPULATION 

DOM manipulation offers another technique 
to add new content to a page (rather than 
i nnerHTML). It involves three steps: 
1 
CREATE THE ELEMENT 
createEl ement () 
You start by creating a new 
element node using the 
createElement() method. 
This element node is stored 
in a variable. 

When the element node is 
created, it is not yet part of the 
DOM tree. It is not added to 
the DOM tree until step 3. 

In the example at the end of the 
chapter, you will see another 
method that can be used to 
insert an element into the DOM 
tree. The i nsertBefore () 
method is used to add a new 
element before the selected 
DOM node. 

GIVE IT CONTENT ADD IT TO THE DOM 
createTextNode() appendChild() 
createTextNode() creates a Now that you have your element 
new text node. Again, the node (optionally with some content 
is stored in a variable. It can be in a text node), you can add 
added to the element node using it to the DOM tree using the 
the appendChi l d () method. appendChi 1 d () method. 

This provides the content for the The appendChi 1 d () method 
element, although you can skip allows you to specify which 
this step if you want to attach an element you want this node 
empty element to the DOM tree. added to, as a child of it. 

## REMOVING ELEMENTS VIA DOM MANIPULATION 
DOM manipulation can be used to remove 
elements from the DOM tree.


The browser represents the page using a DOM tree.

DOM trees have four types of nodes: document nodes, 
element nodes, attribute nodes, and text nodes. 

You can select element nodes by their id or cl ass 
attributes, by tag name, or using CSS selector syntax. 

Whenever a DOM query can return more than one 
node, it will always return a Nadel i st. 

From an element node, you can access and update its 
content using properties such as textContent and 
i nnerHTML or using DOM manipulation techniques. 

An element node can contain multiple text nodes and 
child elements that are siblings of each other. 

In older browsers, implementation of the DOM is 
inconsistent (and is a popular reason for using jQuery). 

Browsers offer tools for viewing the DOM tree . 
