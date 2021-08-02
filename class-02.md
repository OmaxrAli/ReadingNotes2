# HTML Text, CSS Introduction, and Basic JavaScript Instructions

# HTML text
HTML pages are text documents uses tags (characters that sit inside angled 
brackets) to give the information they surround special 
meaning. Tags are often referred to as elements. Tags usually come in pairs.

The opening tag denotes 
the start of a piece of content; the closing tag denotes 
the end.

Opening tags can carry attributes, which tell us more 
about the content of that element.

1. Headings
1. Paragraphs
1. Bold & Italic
1. Superscript & Subscript


### Headings
h1 - h6

HTML has six "levels" of 
headings:
h1 is used for main headings
h2 is used for subheadings
If there are further sections 
under the subheadings then the 
h3 element is used, and so 
on.
Browsers display the contents of 
headings at different sizes.

![Headers](https://www.studybee.net/wp-content/uploads/2015/07/HTML-Heading-Tags.png)

###  Paragraphs
this tag is used to write paragraphs much easier 

![Paragraphs](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSlM0vCFJrhT0xlBCu45Y_kr5JscLqShyPpiQ&usqp=CAU)

### Bold & Italic

these tags are used to make a much better content by making the statments Bold & Italic

![Bold & Italic](http://4.bp.blogspot.com/-Bb57WWtiLqM/U1X8xm8Sz2I/AAAAAAAAAKw/ZOZzMEn5vEg/s280/strong-and-b-element-tag.gif)

### Superscript & Subscript
<.sup.>
The <.sup.> element is used 
to contain characters that 
should be superscript such 
as the suffixes of dates or 
mathematical concepts like 
raising a number to a power such 
as 22
.
<.sub.>
The <.sub.> element is used to 
contain characters that should 
be subscript. It is commonly 
used with foot notes or chemical 
formulas such as H2
0.

![Superscript & Subscript](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSHAvLjHPamlhioodSuDfMM4ECuqdNDD2PRwA&usqp=CAU)

---------------------

# CSS Introduction
## CSS
![CSS](https://miro.medium.com/max/1400/0*0Jt6AoXxmN0n0qhN)

### What is CSS?

CSS stands for Cascading Style Sheets with an emphasis placed on “Style.”
While HTML is used to structure a web document (defining things like headlines and paragraphs, 
and allowing you to embed images, video, and other media), CSS comes through and specifies your document’s style—page layouts
, colors, and fonts are all determined with CSS. Think of HTML as the foundation (every house has one),
and CSS as the aesthetic choices (there’s a big difference between a Victorian mansion and a mid-century modern home).

### How does CSS actually work?
When a browser displays a document, it must combine the document's content with its style information. 
It processes the document in a number of stages, which we've listed below. 
Bear in mind that this is a very simplified version of what happens when a browser loads a webpage,
and that different browsers will handle the process in different ways. But this is roughly what happens.

![CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_works/rendering.svg)

### CSS Syntax
#### Style of CSS
/* Create your test CSS here */

p {
  color: red;
}
#### Selectors


h1
a:link
.manythings
#onething
*
.box p
.box p:first-child
h1, h2, .intro

#### Specificity

.special {
  color: red;
}

p {
  color: blue;
}

<p class="special">What color am I?</p>

####  cascade and specificity.

p {
  color: red;
}

p {
  color: blue;
}


![CSS](https://www.w3schools.com/css/img_selector.gif)



---------------------
# Basic JavaScript Instructions

### What is JavaScript? 
When it comes to developing a web language we think of three layers

1.	HTML : Structure
2.	CSS : styling 
3.	JS :  logic

The JS is used of logical features like booking and registration and more
When you compare JS with other languages like Java or Python you’ll notice that these Programming langues are a backend programming languages while JS is a frontend programming language and the only one.

### Where do you write?

JS is a simple file that you write on a simple file using a text editor and these files have a keywords that are used to interact with the browser and the browser knows that by using the file extender **APP.js**

the JavaScript is Dynamic, Much powerful than other web languages evolves over the time.


#### JavaScript data types Data Type	Description

1. **String**	 represents sequence of characters e.g. "hello"

2. **Number**	represents numeric values e.g. 100
3. **Boolean**	represents boolean value either false or true
4. **Undefined**	represents undefined value
5. **NaN** No Number
6. **Null** No value benn added

#### JavaScript Syntax
JavaScript syntax is the set of rules, how JavaScript programs are constructed:

**How to create variables:**

+ var x;
* let y;

#### JavaScript Values
The JavaScript syntax defines two types of values:

+ Fixed values
+ Variable values

#### JavaScript Operators
JavaScript uses arithmetic operators ( + - * / ) to compute values:

(5 + 6) * 10

#### Identifier
An identifier is a sequence of characters in the code that identifies a variable, function, or property.

In JavaScript, identifiers are case-sensitive and can contain Unicode letters, $, _, and digits (0-9), but may not start with a digit.

An identifier differs from a string in that a string is data, while an identifier is part of the code. In JavaScript, there is no way to convert identifiers to strings, but sometimes it is possible to parse strings into identifiers.


## Switch

A switch statement starts with a 
variable called the switch value.

Each case indicates a possible 
value for this variable and the 
code that should run if the 
variable matches that value. 

Here, the variable named 1 eve l is the switch value. 
If the value of the l eve 1 variable is the string One, 
then the code for the first case is executed. If it is 
Two, the second case is executed. If it is Three, the 
third case is executed. If it is none of these, the code 
for the defaul t case is executed. 

The entire statement lives in one code block (set 
of curly braces), and a colon separates the option 
from the statements that are to be run if the case 
matches the switch value. 

At the end of each case is the break keyword. It tells 
the JavaScript interpreter that it has finished with 
this switch statement and to proceed to run any 
subsequent code that appears after it. 

IF ... ELSE 
• There is no need to provide an el se 
option. (You can just use an if 
statement.) 

• With a series of if statements, they are 
all checked even if a match has been found 
(so it performs more slowly than switch). 
164 DECISIONS & LOOP_S 
vs. 
0 
switch (level) { 
case 'One ': 
title= 'Level 1 ' ; 
break; 
case 'Two': 
tit 1 e = ' Level 2 ' ; 
break; 
case ' Three' : 
title = 'Level 3' ; 
break ; 
default : 
title= 'Test'; 
break; 

SWITCH 
• You have a default option that is run if 
none of the cases match. 
• If a match is found, that code is run; then 
the break statement stops the rest of 
the switch statement running (providing 
better performance than multiple i f 
statements).

![Switch](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQW18nXj97637_zvh9pDNQRprPtfLwpnZjI5Q&usqp=CAU)
