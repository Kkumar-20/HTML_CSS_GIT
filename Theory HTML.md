- HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The src attribute in an img element specifies the image's URL (where the image is located).
Here is an example of an img element with a src attribute pointing to the freeCodeCamp logo:
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">

- Inside the existing img element, add an src attribute with this URL:
https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg

- All img elements should have an alt attribute. The alt attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load. For example, <img src="cat.jpg" alt="A cat"> has an alt attribute with the text A cat.
Inside the img element, add an alt attribute with this text:
A cute orange cat lying on its back
- - -
- You can link to another page with the anchor (a) element. For example, <a href='https://freecodecamp.org'></a> would link to freecodecamp.org.
Add an anchor element after the paragraph that links to https://freecatphotoapp.com. At this point, the link won’t show up in the preview.
- - -
- A link's text must be placed between the opening and closing tags of an anchor (a) element. For example, <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a> is a link with the text click here to go to freeCodeCamp.org.
Add the anchor text link to cat pictures to the anchor element. This will become the link's text.
- - -
- Add a target attribute with the value _blank to the anchor (a) element's opening tag, so that the link opens in a new tab.
- - -
- Before adding any new content, you should make use of a section element to separate the cat photos content from the future content.
Take your h2, comment, p, and anchor (a) elements and nest them in a section element.
- - -
- Use list item (li) elements to create items in a list. Here is an example of list items in an unordered list:
```
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```
Within the ul element nest three list items to display three things cats love:
cat nip laser pointers lasagna
- - -
- After the unordered list, add a new image with an src attribute value set to: https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg
And its alt attribute value to: A slice of lasagna on a plate.
- - -
- The figure element represents self-contained content and will allow you to associate an image with a caption.
Nest the image you just added within a figure element.
- - -
- A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element. For example, <figcaption>A cute cat</figcaption> adds the caption A cute cat.
After the image nested in the figure element, add a figcaption element with text set to: Cats love lasagna.
- - -
- Emphasize the word love in the figcaption element by wrapping it in an emphasis em element.
- - -
- The code for an ordered list (ol) is similar to an unordered list, but list items in an ordered list are numbered when displayed.
After the second section element's last h3 element, add an ordered list with these three list items: flea treatment thunder other cats
- - -
- To improve accessibility of the image you added, add an alt attribute with the text:
Five cats looking around a field.
- - -
- The strong element is used to indicate that some text is of strong importance or urgent.
In the figcaption you just added, indicate that hate is of strong importance by wrapping it in a strong element.
- - -
- Now you will add a web form to collect information from users.
After the Cat Form heading, add a form element.
- - -
The input element allows you several ways to collect data from a web form. Like img elements, input elements are self-closing and do not need closing tags.
Nest an input element in the form element.
- - -
- There are many kinds of inputs you can create using the type attribute. You can easily create a password field, reset button, or a control to let users select a file from their computer.
Create a text field to get text input from a user by adding the type attribute with the value text to the input element.
- - -
- In order for a form's data to be accessed by the location specified in the action attribute, you must give the text field a name attribute and assign it a value to represent the data being submitted. For example, you could use the following syntax for an email address text field: <input type="text" name="email">.
Add the name attribute with the value catphotourl to your text field.
- - -
- Placeholder text is used to give people a hint about what kind of information to enter into an input. For example, <input type="text" placeholder="Email address">.
Add the placeholder text cat photo URL to your input element.
- - -
- Use the button element to create a clickable button. For example, <button>Click Here</button> creates a button with the text Click Here.
Add a button element with the text Submit below the input element. The default behavior of clicking a form button without any attributes submits the form to the location specified in the form's action attribute.
- - -
- You can use radio buttons for questions where you want only one answer out of multiple options.
Here is an example of a radio button with the option of cat: <input type="radio"> cat. Remember that input elements are self-closing.
Before the text input, add a radio button with the option set as: Indoor
- - -
- The id attribute is used to identify specific HTML elements. Each id attribute's value must be unique from all other id values for the entire page.
Add an id attribute with the value indoor to the radio button. When elements have multiple attributes, the order of the attributes doesn't matter.
- - -
- Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a name attribute with the same value.
Add the name attribute with the value indoor-outdoor to both radio buttons.
- - -
- The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line.
Nest the Indoor and Outdoor radio buttons within a fieldset element, and don't forget to indent the radio buttons.
- - -
- The legend element acts as a caption for the content in the fieldset element. It gives users context about what they should enter into that part of the form.
Add a legend element with the text Is your cat an indoor or outdoor cat? above both of the radio buttons.
- - -
- Forms commonly use checkboxes for questions that may have more than one answer. For example, here's a checkbox with the option of tacos: <input type="checkbox"> tacos.
Under the legend element you just added, add an input with its type attribute set to checkbox and give it the option of: Loving
- - -
- Add the name attribute with the value personality to the checkbox input element.
- - -
- 
