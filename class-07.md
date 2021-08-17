# HTML Links, JS Functions, and Intro to CSS Layout

# Links:

Links are created using the \<a> element. Users can click on anything 
between the opening \</a> tag and the closing \</a> tag. You specify 
which page you want to link to using the href attribute


The text between the opening 
\<a> tag and closing \</a> tag 
is known as link text. Where 
possible, your link text should 
explain where visitors will be 
taken if they click on it (rather 
than just saying "click here"). 
  
Below you can see the link to 
IMDB that was created on the 
previous page. 
  
Many people navigate websites 
by scanning the text for links. 
Clear link text can help visitors 
find what they want. 
  
This 
will give them a more positive 
impression of your site and may 
encourage them to visit it for 
longer. 
  
  (It also helps people 
using screen reader software.)
To write good link text, you can 
think of words people might 
use when searching for the 
page that you are linking to. 
  
  
(For example, rather than write 
"places to stay" you could use 
something more specific such as 
"hotels in New York."
  
# \<a> 
Links are created using the <a>
element which has an attribute 
called href. The value of the 
href attribute is the page that 
you want people to go to when 
they click on the link.
  
Users can click on anything that 
appears between the opening 
<a> tag and the closing \</a>
tag and will be taken to the page 
specified in the href attribute.
  
When you link to a different 
website, the value of the href
attribute will be the full web 
address for the site, which is 
known as an absolute URL.


+ Links are created using the <a> element.
  
+ The <a> element uses the href attribute to indicate 
the page you are linking to.
  
+ If you are linking to a page within your own site, it is 
best to use relative links rather than qualified URLs.
  
+ You can create links to open email programs with an 
email address in the "to" field.
  
+ You can use the id attribute to target elements within 
a page that can be linked to
  
  ![Links](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2020/06/Links-in-HTML.jpg)
  
  -----------------------------------------------
  
  # Layout
## Building Blocks
CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box.
 
Block-level boxes start on a new line and act as the main building blocks 
of any layout, while inline boxes flow between surrounding text. You can 
control how much space each box takes up by setting the width of the 
boxes (and sometimes the height, too). To separate boxes, you can use 
borders, margins, padding, and background colors.

  # \<h1> \<p> \<ul> \<li>
  
 ## Containing Elements
If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element
  
  \<div> elements are often used as containing elements 
to group together sections of a page.  

+ Browsers display pages in normal flow unless you 
specify relative, absolute, or fixed positioning.
+ The float property moves content to the left or right 
of the page and can be used to create multi-column 
layouts. (Floated items require a defined width.)
+ Pages can be fixed width or liquid (stretchy) layouts.
+ Designers keep pages within 960-1000 pixels wide, 
and indicate what the site is about within the top 600 
pixels (to demonstrate its relevance without scrolling).
+ Grids help create professional and flexible designs.
+ CSS Frameworks provide rules for common tasks.
+ You can include multiple CSS files in one page

  ![layout](https://www.techfry.com/images/articles/html/html-page-layouts.jpg)
  
------------------------------------
# Functions, Methods, and Objects
  
## FUNCTIONS & OBJECTS BUILT-IN 
METHODS OBJECTS 
  
Functions consist of a In Chapter 1 you saw that The browser comes with 
series of statements programmers use objects a set of objects that act 
that have been grouped to create models of the like a toolkit for creating 
together because they world using data, and that interactive web pages. 
perform a specific task. objects are made up of This section introduces 
A method is the same as a properties and methods. you to a number of built-in 
function, except methods In this section, you learn objects, which you will 
are created inside (and are how to create your own then see used throughout 
part of) an object. objects using JavaScript. the rest of the book.
  
## WHAT IS A FUNCTION? 
Functions let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements). 

## WHAT IS AN OBJECT?
  Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. 

  Functions allow you to group a set of related 
+ statements together that represent a single task. 
Functions can take parameters (informatiorJ required 
to do their job) and may return a value. 
+ An object is a series of variables and functions that 
+ represent something from the world around you. 
+ In an object, variables are known as properties of the 
object; functions are known as methods of the object. 
+ Web browsers implement objects that represent both 
the browser window and the document loaded into the 
browser window. 
+ JavaScript also has several built-in objects such as 
String, Number, Math, and Date. Their properties and 
methods offer functionality that help you write scripts. 
+ Arrays and objects can be used to create complex data 
sets (and both can contain the other).
  
  ![fom](https://cf.ppt-online.org/files/slide/z/ZQB7W6CTo0jgKzhF5VLlfNdbm1HPD2exvrSG9q/slide-34.jpg)
