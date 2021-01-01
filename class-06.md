# Class 6

## JS
* ### Object Literals
**Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.**


**_CREATING· OBJECTS USING LITERAL NOTATION_**

Similarly, to use the method,you can use the object name followed by the method name. hotel . checkAvailability() If the method needs parameters, you can supply them in the parentheses (just like you can pass arguments to a function). 

* ### Document Object Model
**The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.**

**_ACCESSING ELEMENTS_**

DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes. 

Sometimes you will just want to access one individual element (or a fragment of the page that is stored within that one element). Other times you may want to select a group of element s, for example, every <hl> element in the page or every <1 i> element within a particular list. 

Here, the DOM tree shows the body of the page of
the list example. We focus on accessing elements
first so it only shows element nodes. The diagrams
in the coming pages highlight which elements a
DOM query would return. (Remember, element
nodes are the DOM representation of an element.)

**_SELECTING ELEMENTS BY TAG NAME_**

The get El ementsByTagName () method allows you to select elements using their tag name. 

The element name is specified
as a parameter, so it is placed
inside the parentheses and is
contained by quote marks. 

Note that you do not include the
angled brackets that surround
the tag name in the HTML (just
the letters inside the brackets). 

**_WHITESPACE NODES_**

Traversing the DOM can be difficult because
some browsers add a text node whenever they
come across whitespace between elements.