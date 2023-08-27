- HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The src attribute in an img element specifies the image's URL (where the image is located).
Here is an example of an img element with a src attribute pointing to the freeCodeCamp logo:
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">
- Inside the existing img element, add an src attribute with this URL:
https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg

- All img elements should have an alt attribute. The alt attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load. For example, <img src="cat.jpg" alt="A cat"> has an alt attribute with the text A cat.
Inside the img element, add an alt attribute with this text:
A cute orange cat lying on its back

- You can link to another page with the anchor (a) element. For example, <a href='https://freecodecamp.org'></a> would link to freecodecamp.org.
Add an anchor element after the paragraph that links to https://freecatphotoapp.com. At this point, the link won’t show up in the preview.

- A link's text must be placed between the opening and closing tags of an anchor (a) element. For example, <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a> is a link with the text click here to go to freeCodeCamp.org.
Add the anchor text link to cat pictures to the anchor element. This will become the link's text.
- Add a target attribute with the value _blank to the anchor (a) element's opening tag, so that the link opens in a new tab.
- Before adding any new content, you should make use of a section element to separate the cat photos content from the future content.
Take your h2, comment, p, and anchor (a) elements and nest them in a section element.
- Use list item (li) elements to create items in a list. Here is an example of list items in an unordered list:
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
Within the ul element nest three list items to display three things cats love:
cat nip laser pointers lasagna
- 
