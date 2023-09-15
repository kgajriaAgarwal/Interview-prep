1. What is <!Doctype html> in Html5
ans. It is an "information" to the browser about what document type to expect.

2. Differnce between html and html 5 ?
ans.Key Difference between HTML and HTML5
HTML Doctype declaration is lengthy while DOCTYPE declaration in HTML5 is simpler.
Audio and video are not HTML parts, whereas audio and video tags are supported in HTML5.
In HTML, a Web Socket is not available, on the other hand, in HTML5 you can establish full-duplex communication channels with a server using Web Sockets.
HTML is less mobile-friendly, while HTML5 is mobile-friendly.

3. What is difference between div and span in Html
Differences between <div> and <span> tag: 
https://www.geeksforgeeks.org/difference-between-div-and-span-tag-in-html/
The <div> tag is a block level element.	The <span> tag is an inline element.
<div> is best to attach it to a section of a web page.	<span> is best to attach a CSS to a small section of a line in a web page.
<div> accepts align attribute.	<span> does not accept align attribute.
<div> This tag should be used to wrap a section, for highlighting that section.	<span> tag should be used to wrap any specific word that you want to highlight in your webpage.

4. What is semantic tags and non semantic tags in
Html
A semantic element clearly describes its meaning to both the browser and the developer.
Examples of semantic elements: <form>, <table>, and <article> - Clearly defines its content.

Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.

5. What is Iframe tag in Html5?
ans. An inline frame (iframe) is a HTML element that loads another HTML page within the document. It essentially puts another webpage within the parent page. They are commonly used for advertisements, embedded videos, web analytics and interactive content.

6. What are the formatting tags in html
Formatting elements were designed to display special types of text:
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text

7. What is difference <b> and <Strong> in html
The <strong> tag is used to define text with strong importance, The bold (<b>) tag specifies bold text without any extra importance

8. What is view port attribute in html.
The viewport is the user's visible area of a web page. The viewport varies with the device, and will be smaller on a mobile phone than on a computer screen.

9. What is attribute in html
HTML attributes provide additional information about HTML elements.
All HTML elements can have attributes
Attributes provide additional information about elements
Attributes are always specified in the start tag
Attributes usually come in name/value pairs like: name="value"

example:
The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:
<a href="https://www.w3schools.com">Visit W3Schools</a>


10. What is the difference between tags and attributes?
The main difference between tag and attribute is that a tag is a way of representing an HTML element in the program, while an attribute is a way of describing the characteristics of an HTML element.

11. What is block level element and inline element in html
There are two display values: block and inline
A block-level element always starts on a new line and takes up the full width available
An inline element does not start on a new line and it only takes up as much width as necessary
The <div> element is a block-level and is often used as a container for other HTML elements
The <span> element is an inline container used to mark up a part of a text, or a part of a document

12. Difference between figure and img tag
The difference between the figure and the image tag is pretty simple. The image tag is used to embed the image in an HTML document whereas the figure tag is used to semantically organize the content of an image in the HTML document.

13. How to optimize website assets loading?
To optimize website load time we need to optimize its asset loading and for that:

CDN hosting - A CDN or content delivery network is geographically distributed servers to help reduce latency.
File compression - This is a method that helps to reduce the size of an asset to reduce the data transfer
File concatenation - This reduces the number of HTTP calls
Minify scripts - This reduces the overall file size of js and CSS files
Parallel downloads - Hosting assets in multiple subdomains can help to bypass the download limit of 6 assets per domain of all modern browsers. This can be configured but most general users never modify these settings.
Lazy Loading - Instead of loading all the assets at once, the non-critical assets can be loaded on a need basis

14. In how many ways can we position an HTML element? Or what are the permissible values of the position attribute?
There are mainly 7 values of position attribute that can be used to position an HTML element:

- static: Default value. Here the element is positioned according to the normal flow of the document.
- absolute: Here the element is positioned relative to its parent element. The final position is determined by the values of left, right, top, bottom.
- fixed: This is similar to absolute except here the elements are positioned relative to the <html> element.
- relative: Here the element is positioned according to the normal flow of the document and positioned relative to its original/ normal position.
- initial: This resets the property to its default value.
- inherit: Here the element inherits or takes the property of its parent.

15. In how many ways you can display HTML elements?
inline: Using this we can display any block-level element as an inline element. The height and width attribute values of the element will not affect.
block: using this, we can display any inline element as a block-level element. 
inline-block: This property is similar to inline, except by using the display as inline-block, we can actually format the element using height and width values.
flex: It displays the container and element as a flexible structure. It follows flexbox property.
inline-flex: It displays the flex container as an inline element while its content follows the flexbox properties.
grid: It displays the HTML elements as a grid container.
none: Using this property we can hide the HTML element.

for more questions on html
https://www.javatpoint.com/html-interview-questions
https://www.interviewbit.com/html-interview-questions/#are-html-tags-and-elements-the-same