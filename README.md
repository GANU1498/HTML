# HTML
Firstly HTML stands for Hyper-Text-Markup-Language.
HTML is the standard markup language for creating Web pages.HTML elements tell the browser how to display the content.
A simple HTML code is Below:
<img width="689" alt="Screenshot 2024-03-07 172124" src="https://github.com/GANU1498/HTML/assets/143490640/f495571c-3f1f-4fc6-829c-262776407dc4">

The <!DOCTYPE html> declaration defines that this document is an HTML5 document.
The <html> element is the root element of an HTML page.
The <head> element contains meta information about the HTML page.
The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).
The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

The h1 element defines a large heading.
The p element defines a paragraph.
The DOCTYPE Declaration.
The DOCTYPE declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The DOCTYPE declaration is not case sensitive.

The DOCTYPE declaration for HTML5 is:

<img width="633" alt="Screenshot 2024-03-07 173130" src="https://github.com/GANU1498/HTML/assets/143490640/7613dba6-2a13-4c32-837e-79e4ba2955e9">


HTML is Not Case Sensitive
HTML tags are not case sensitive: <P> means the same as <p>.
There is another important attribute of img tag that is'alt'.
The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.


The HTML standard does not require lowercase tags, but We recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.
All HTML elements can have attributes.
Attributes provide additional information about elements.
Attributes are always specified in the start tag.
Attributes usually come in name/value pairs like: name="value".
The src Attribute---
the <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

<img width="341" alt="Screenshot 2024-03-08 171130" src="https://github.com/GANU1498/HTML/assets/143490640/17b43381-6f4c-4522-94de-6037c5ed2ab8">


In above image there are 3 Attributes src, width, height.


<img width="361" alt="Screenshot 2024-03-08 171521" src="https://github.com/GANU1498/HTML/assets/143490640/a397e81b-13b5-4b24-89fc-2203afd56017">


The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader



### HTML Documents
All HTML documents must start with a document type declaration: <!DOCTYPE html>.

The HTML document itself begins with <html> and ends with </html>.

The visible part of the HTML document is between <body> and </body>.


```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>.
```


### The <!DOCTYPE> Declaration
The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The <!DOCTYPE> declaration is not case sensitive.

The <!DOCTYPE> declaration for HTML5 is:

`<!DOCTYPE html>`


### HTML Headings
HTML headings are defined with the `<h1> to <h6>` tags.

`<h1> defines the most important heading. <h6> defines the least important heading:` 

```
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```


### HTML Links

HTML links are defined with the <a> tag:


`<a href="https://www.w3schools.com">This is a link</a>`

### HTML Images
HTML images are defined with the <img> tag.

The source file (src), alternative text (alt), width, and height are provided as attributes:


`<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">`


## HTML Elements

An HTML element is defined by a start tag, some content, and an end tag.


HTML Elements
The HTML element is everything from the start tag to the end tag:

<tagname>Content goes here...</tagname>
Examples of some HTML elements:

`<h1>My First Heading</h1>`
`<p>My first paragraph.</p>`


## HTML Attributes:

HTML attributes provide additional information about HTML elements.

All HTML elements can have attributes.


Attributes provide additional information about elements.


Attributes are always specified in the start tag.


Attributes usually come in name/value pairs like: name="value".


### The href Attribute:

The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:

`<a href="https://www.w3schools.com">Visit W3Schools</a>`

### The src Attribute:

The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

`<img src="img_girl.jpg">`

#### There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.


### The width and height Attributes:

The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):

`<img src="img_girl.jpg" width="500" height="600">`


### The alt Attribute :

The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

`<img src="img_girl.jpg" alt="Girl with a jacket">`

### The style Attribute:

The style attribute is used to add styles to an element, such as color, font, size, and more.

`<p style="color:red;">This is a red paragraph.</p>`

### The lang Attribute:

You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

The following example specifies English as the language:

```
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```

Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

The following example specifies English as the language and United States as the country:


```
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```


### HTML Comments:

HTML comments are not displayed in the browser, but they can help document your HTML source code.

`<!-- Write your comments here -->`

Notice that there is an exclamation point (!) in the start tag, but not in the end tag.


```
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->
```
