# HTML Lists
lists are very importent to organize and list things in our lives and **HTML** has this kind of thing and it provides us with
and it three different types: 

![Lists](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ7pS_3EzFCBKG_MoyfCmMDPlOQDzCa8KJudw&usqp=CAU)

+ **Ordered lists** are lists where each item in the list is 
numbered. For example, the list might be a set of steps for 
a recipe that must be performed in order, or a legal contract 
where each point needs to be identified by a section 
number.

+ **Unordered** lists are lists that begin with a bullet point 
(rather than characters that indicate order)

+ **Definition** lists are made up of a set of terms along with the 
definitions for each of those terms.

## Ordered List
## \<ol>

The ordered list is created with 
the \<ol> element.
## \<li>
 
Each item in the list is placed 
between an opening \<li> tag 
and a closing \</li> tag. (The li
stands for list item.)
Browsers indent lists by default.

Sometimes you may see a type
attribute used with the \<ol>
element to specify the type of 
numbering (numbers, letters, 
roman numerals and so on).

----------------

## Unordered List
## \<ul>
The unordered list is created 
with the \<ul> element.
## \<li>
Each item in the list is placed 
between an opening \<li> tag 
and a closing \</li> tag. (The li
stands for list item.)

Browsers indent lists by default.
Sometimes you may see a type
attribute used with the \<ul>
element to specify the type of 
bullet point (circles, squares, 
diamonds and so on).

-----------------

## Definition Lists

## \<dl>
The definition list is created with 
the \<dl> element and usually 
consists of a series of terms and 
their definitions.

Inside the \<dl> element you will 
usually see pairs of \<dt> and 
\<dd> elements.
## \<dt>
This is used to contain the term 
being defined (the definition 
term).
## \<dd>
This is used to contain the 
definition.
  
Sometimes you might see a list 
where there are two terms used 
for the same definition or two 
different definitions for the same 
term.

![Lists](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1BCJ3dIdUJzNQ-H9Q2gwE3YwFXpTUlmxPoQ&usqp=CAU)
-------------------
# Control Flow with JS

## Loops

Instead of writing the code multiple times we use the loops to reduce the time and efforst Loops offer a quick and easy way to do something repeatedly.

There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times.
### Loop types in JavaScript
![Loops](https://media.geeksforgeeks.org/wp-content/uploads/20191023174139/1021.png)

* for statement
* while statement
* for in
* for of
* do..while


### Loop statments
* for statement
* do...while statement
* while statement
* labeled statement
* break statement
* continue statement
* for...in statement
* for...of statement



-------------------
# the CSS Box Model

At the beginning of this section on CSS, 
you saw how CSS treats each HTML 
element as if it lives in its own box.

You can set several properties that affect the appearance of 
these boxes. In this chapter you will see how to:

+ dimensions of your boxes
+ Creating borders around boxes
+ Set margins and padding for boxes
+ Show and hide boxes

## dimensions of your boxes

### width, height

By default a box is sized just big 
enough to hold its contents. To 
set your own dimensions for a 
box you can use the height and 
width properties.

##  Creating Borders
### min-width, max-width

Some page designs expand and 
shrink to fit the size of the user's 
screen. In such designs, the 
min-width property specifies 
the smallest size a box can be 
displayed at when the browser 
window is narrow, and the 
max-width property indicates 
the maximum width a box can 
stretch to when the browser 
window is wide.

## Set margins and padding for boxes
### margin

The margin property controls 
the gap between boxes. Its value 
is commonly given in pixels, 
although you may also use 
percentages or ems.

If one box sits on top of another, 
margins are collapsed , which 
means the larger of the two 
margins will be used and the 
smaller will be disregarded.

## Show and hide boxes
### display

The display property allows 
you to turn an inline element 
into a block-level element or vice 
versa, and can also be used to 
hide an element from the page.
The values this property can 
take are:
##### inline
This causes a block-level 
element to act like an inline 
element.

##### block
This causes an inline element to 
act like a block-level element.

##### inline-block
This causes a block-level 
element to flow like an inline 
element, while retaining other 
features of a block-level element.

##### none
This hides an element from the 
page. In this case, the element 
acts as though it is not on the 
page at all (although a user could 
still see the content of the box if 
they used the view source option 
in their browser).

### visibility

The visibility property allows 
you to hide boxes from users 
but It leaves a space where the 
element would have been.

This property can take two 
##### values:
hidden
This hides the element.
##### visible
This shows the element

![Boxses in CSS](https://miro.medium.com/max/1276/1*PGOsy3OmNgYwHaomZbYePQ.png)

