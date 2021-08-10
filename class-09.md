# Forms
Traditionally, the term "form" refers to a printed document that contains spaces to fill in information. Perhaps the best known form on the web is the search box in the middle of the Google homepage.
### Form Controls
**Add text:**
* Input text (one line): Used for one line of text such as email addresses and names.
* Enter password: Like a single line text box but it hides the entered characters.
* Text area (multi-line): For longer areas of text, such as messages and comments

**Make choices :**
* Radio buttons: for use when the user has to select an option
* Checkboxes: When the user can select and deselect one or more options.
* Dropdown boxes: When the user has to choose one of a number of options from the list.

**Submission of forms :**
* Submit buttons: To send data from your form to another web page.
* Picture buttons: Similar to send buttons but allow you to use an image.
* File Upload: Allows users to upload files

Form Structure: (form) Form controls are inside an object (form). This element must always have an action attribute and will usually have a method attribute and an action identifier as well. Each element (form) requires an action attribute. Its value is the URL of the page on the server that will receive the information in the form when it is submitted. Method You can submit forms using one of two methods: get or post.

identifier: we look at the id attribute on page 183, but the value is used to clearly identify the form from other elements on the page (and is often used by scripts - such as those that check that information is entered into fields that require values)

**Enter text:**
(input) The input element is used to create many different controls on the form. The value of the type attribute determines the type of input that will be created.
type = "text" When the type attribute contains a text value, it creates a single line text entry.

When you want to collect information from visitors, you will need a form that lives inside an object (form). Information from the form is sent in name/value pairs. Each control on the form is given a name, and the text the user types or the values of the options they select are sent to the server. HTML5 introduces new form elements that make it easier for visitors to fill out forms.
# Lists, Tables and Forms
**list-style-type :** The list-style-type property allows you to control the shape or style of a bullet point (also known as a tag).

**list-style-image :** You can specify an image to act as a bullet using the list-style-image property.

**List-style lists :** are indented on the page by default and the List-Style Position property indicates whether the tag should appear inside or outside the box containing the key points.

**Menu Style :** As with many other CSS properties, there is a property that acts as a shortcut to Menu Styles. It's called list style, and it allows you to express the style of tags, image, and position properties in any order.

In addition to the CSS properties included in the other classes that work with the contents of all elements, there are many other properties that are specifically used to control the appearance of lists, tables, and forms. Menu tags can be given different looks using the menu style type and menu style image properties. Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent. Forms are easier to use if the form controls are aligned vertically with CSS. Forms make use of patterns that make them more interactive.

# Events
When you browse the web, your browser records different types of events. It's the browser's way of saying, "Hey, this just happened." Your text can then respond to these events.
When a user interacts with HTML on a web page, there are three steps involved in getting it to run some JavaScript code. Together, these steps are known as event handling.
1. Select t he element node(s) you want the script to respond to. 
2. Indicate which event on the selected node(s) will trigger the response. 
3. State the code you want to run when the event occurs.

Here you can see how event processing can be used to provide feedback to users who fill out the registration form. An error message will appear if the username is too short.
* Select item specification! Financial event The element that users interact with is the text entry where they enter the username
* SPECIFICATIONS! Financial event: When users exit text entry, focus loses, and blur event fires on that element.
* CALL CODE: When the blur event fires on the username input, it will fire a function called check Username(), this function checks if the username is less than 5 characters.

Events are the browser's way of indicating that something has happened (such as a page loading finished or a button being clicked). Binding is the process of identifying the event you are waiting for and the element you are waiting for. When an event occurs on an element, it can trigger a JavaScript function. When this function changes the web page in some way, it appears interactive because it responded to the user. You can use event delegation to monitor events that occur on all child elements of an element. The most commonly used events are W3C DOM events, although there are other events in the HTMLS specification in addition to browser-specific events.