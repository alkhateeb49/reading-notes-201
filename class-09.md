# Class 9

## HTML
* ### Forms

**Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.**

**HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.**

Whether you are adding a simple search box to your website or you need to create more complicated insurance applications, HTML forms give you a set of elements to collect data from your users. In this chapter you will learn:
- - How to create a form on your website
- - The different tools for collecting data
- - New HTML5 form controls

**Text Input**
* * **_`<input>` :_** The `<input>` element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.
* * **_`type="text"` :_** When the type attribute has a value of text, it creates a singleline text input.
* * **_`name` :_** When users enter information into a form, the server needs to know which form control each piece of data was entered into. (For example, in a login form, the server needs to know what has been entered as the username and what has been given as the password.) Therefore, each form control requires a name attribute. The value of this attribute identifies the form control and is sent along with the information they enter to the server.
* * **_`maxlength` :_** You can use the maxlength attribute to limit the number of characters a user may enter into the text field. Its value is the number of characters they may enter. For example, if you were asking for a year, the maxlength attribute could have a value of 4.


* ### Lists
**The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker). It can be used on rules that apply to the `<ol>`, `<ul>`, and `<li>` elements.**

* ### Tables & Forms
**You have already met several properties that are commonly used with tables. Here we will put them together in a single example using the following:**
* * **_`width` :_**  to set the width of the table
* * **_`padding` :_**  to set the space between the border of each table cell and its content
* * **_`text-transform` :_**  to convert the content of the table headers to uppercase
* * **_`letter-spacing, font-size` :_** to add additional styling to the content of the table headers
* * **_`border-top, border-bottom` :_** to set borders above and below the table headers
* * **_`text-align` :_** to align the writing to the left of some table cells and to the right of the others
* * **_`background-color` :_** to change the background color of the alternating table rows
* * **_`:hover ` :_** to highlight a table row when a user's mouse goes over it


## JS
* ### Events
**When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.**

**When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as event handling. .**

* * Select t he element node(s) you want the script to respond to. For example, if you want to trigger a function when a user clicks on a specific link, you need to get the DOM node for that link element. You do this using a DOM query. 
* * Indicate which event on the selected node(s) will trigger the response. Programmers call this binding an event to a DOM node. The previous two pages showed a selection of the popular events that you can monitor for.
* * State the code you want to run when the event occurs. When the event occurs, on a specified element, it will trigger a function. This may be a named or an anonymous function.