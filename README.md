1. What is the Emmet shortcut used to create the HTML boilerplate?

The Emmet shortcut is !.

In VS Code, type ! and press Enter or Tab. It automatically generates the basic HTML5 structure.

2. What is DOCTYPE in HTML?

<!DOCTYPE html> is a declaration that tells the browser that the document uses HTML5.

It is written at the beginning of an HTML document.

<!DOCTYPE html>
3. What is a Void Element? Give examples.

A void element is an HTML element that does not have a closing tag and cannot contain any content.

Examples:

<img>
<br>
<hr>
<input>
<meta>
<link>

Example:

<img src="image.jpg" alt="My Image">
4. What is the difference between Elements and Attributes?

An element defines the structure or content of a webpage.

Example:

<p>Hello World</p>

An attribute provides additional information about an element.

Example:

<img src="image.jpg" alt="My Image">

Here:

img → Element
src → Attribute
alt → Attribute

In short: Elements define what appears on the webpage, while attributes provide additional information about elements.

5. What are HTML Entities and why are they needed in HTML?

HTML entities are special codes used to display reserved characters and special symbols in HTML.

Examples:

&lt;   → <
&gt;   → >
&amp;  → &
&quot; → "
&copy; → ©

For example:

<p>5 &lt; 10</p>

It displays:

5 < 10

They are needed because some characters, such as < and >, have special meanings in HTML.

6. What are Meta Tags and why are they used?

Meta tags provide information about a webpage to the browser and search engines. They are placed inside the <head> section.

Example:

<meta charset="UTF-8">

This defines the character encoding.

Another important example is:

<meta name="viewport" content="width=device-width, initial-scale=1.0">

This helps the webpage display correctly on different screen sizes, especially mobile devices.

Meta tags are used for character encoding, responsive design, SEO-related information, and other webpage metadata.

7. What is the best way to add images to a website?

The standard way to add an image is by using the <img> tag.

<img src="image.jpg" alt="Description of image">

For a local image:

<img src="./images/photo.jpg" alt="My Photo">

For an image from a CDN:

<img src="https://example.com/photo.jpg" alt="My Photo">

It is important to use the alt attribute because it provides alternative text if the image cannot be displayed and improves accessibility.

For better website performance, images should also be properly compressed and optimized.
