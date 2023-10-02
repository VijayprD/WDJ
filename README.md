# Web Development Journey 2023
Hi, This is course page of codexvijay web development journey.From zero to hero.
## Follow me on [instagram](https://www.instagram.com/codexvijay).

# HTML Series

## Part 1 -Basic Introduction
### What is HTML?
HTML is an acronym which stands for Hyper Text Markup Language which is used for creating web pages and web applications. Let's see what is meant by Hypertext Markup Language, and Web page.

Hyper Text: HyperText simply means "Text within Text." A text has a link within it, is a hypertext. Whenever you click on a link which brings you to a new webpage, you have clicked on a hypertext. HyperText is a way to link two or more web pages (HTML documents) with each other.

Markup language: A markup language is a computer language that is used to apply layout and formatting conventions to a text document. Markup language makes text more interactive and dynamic. It can turn text into images, tables, links, etc.

### History of HTML
In the late 1980's , a physicist, Tim Berners-Lee who was a contractor at CERN, proposed a system for CERN researchers. In 1989, he wrote a memo proposing an internet based hypertext system.

Tim Berners-Lee is known as the father of HTML. The first available description of HTML was a document called "HTML Tags" proposed by Tim in late 1991. The latest version of HTML is HTML5.

## Part 2 -Building Blocks of HTML
* Tags
* Attribute
* Element

### Tags
HTML tags are like keywords which defines that how web browser will format and display the content. With the help of tags, a web browser can distinguish between an HTML content and a simple content. HTML tags contain three main parts: opening tag, content and closing tag. But some HTML tags are unclosed tags.

* All HTML tags must enclosed within < > these brackets.
* Every tag in HTML perform different tasks.
* If you have used an open tag <tag>, then you must use a close tag </tag> (except some tags)

**syntax :`<tag>Content</tag>`**

### Attribute
* HTML attributes are special words which provide additional information about the elements or attributes are the modifier of the HTML element.
* Each element or tag can have attributes, which defines the behaviour of that element.
* Attributes should always be applied with start tag.
* The Attribute should always be applied with its name and value pair.
* The Attributes name and values are case sensitive, and it is recommended by W3C that it should be written in Lowercase only.
* You can add multiple attributes in one HTML element, but need to give space between two attributes.

**syntax :`<tag attribute_name="value">content</tag>`**

### Element
An HTML file is made of elements. These elements are responsible for creating web pages and define content in that webpage. An element in HTML usually consist of a start tag <tag name>, close tag </tag name> and content inserted between them. Technically, an element is a collection of start tag, attributes, end tag, content between them.

![Element](https://static.javatpoint.com/htmlpages/images/html-building-blocks.png)

## Part 3 - Coding Start

### Simple example of HTML.
```html
<!DOCTYPE>  
<html>  
<head>  
<title>Web page title</title>  
</head>  
<body>  
<h1>Heading</h1>  
<p>Paragraph.</p>  
</body>  
</html>
```
`<!DOCTYPE>`: It defines the document type or it instruct the browser about the version of HTML.

`<html >` :This tag informs the browser that it is an HTML document. Text between html tag describes the web document. It is a container for all other elements of HTML except <!DOCTYPE>

`<head>`: It should be the first element inside the `<html>` element, which contains the metadata(information about the document). It must be closed before the body tag opens.

`<title>`: As its name suggested, it is used to add title of that HTML page which appears at the top of the browser window. It must be placed inside the head tag and should close immediately.

`<body>` : Text between body tag describes the body content of the page that is visible to the end user. This tag contains the main content of the HTML document.

`<h1>` : Text between `<h1>` tag describes the first level heading of the webpage.

`<p>` : Text between `<p>` tag describes the paragraph of the webpage.

## Part 4 - HTML Formatting

HTML Formatting is a process of formatting text for better look and feel. HTML provides us ability to format text without using CSS. There are many formatting tags in HTML. These tags are used to make text bold, italicized, or underlined. 

|Element Name|Description|

|`<b>`|This is a physical tag, which is used to bold the text written between it.|

|`<strong>`|This is a logical tag, which tells the browser that the text is important.|

|`<i>`|	This is a physical tag which is used to make text italic.|

|`<em>`|This is a logical tag which is used to display content in italic.|

|`<mark>`|This tag is used to highlight text.|

|`<u>`|	This tag is used to underline text written between it.|

|`<sup>`|It displays the content slightly above the normal line.|

|`<sub>`|It displays the content slightly below the normal line.|