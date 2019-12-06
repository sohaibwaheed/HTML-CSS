# HTML AND CSS 


### DOMAIN NAME SYSTEM (DNS) SERVER

- In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.

- It is the DNS servers that tell your browser how to find the website.

- *When you connect to the web, you do so via an Internet Service Provider (ISP)*

- *An IP address is a number of up to 12 digits separated by periods / full stops. Every device connected to the web has a unique IP address; it is like the phone number for
   that computer*

### WEB SERVER 

- A web server is a computer that is constantly connected to the web, and is set up especially to send web pages to users.


### HTML ELEMENTS

- Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something
  about the information that sits between its opening and closing tags. e.g </h>, <p>

- Tags act like containers. They tell you something about the information that lies between their opening and closing tags.

### TAGS

- The opening `<html>` tag indicates that anything between it and a closing `</html>` tag is HTML code

- The `<body>` tag indicates that anything between it and the closing `</body>` tag should be shown inside the main browser window

- Words between `<h1>` and `</h1>` are a main heading

- A paragraph of text appears between these `<p>` and `</p>` tags

- Words between `<h2>` and `</h2>` form a sub-heading

- Another sub-heading inside `<h2>` and `</h2>` tags

- The closing `</body>` tag indicates the end of what should appear in the main browser window.

- The closing `</html>` tag indicates that it is the end of the HTML code.

- Before the `<body>` element you will often see a <head> element. This contains information about the page (rather than information that is shown within the main part of the 
  browser

- The contents of the `<title>` element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that
  page (if your browser uses tabs to allow you to view multiple pages at the same time).

- By enclosing words in the tags `<b>` and `</b>` we can make characters appear bold.

- By enclosing words in the tags `<i>` and `</i>` we can make characters appear italic.

- The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such
  as 2 to the power 2 

- The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H 2 0.

- if you wanted to add a line break inside the middle of a paragraph you can use the line break tag `<br />`

- To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the `<hr />` tag.

- The use of the `<strong>` element indicates that its content has strong importance.

- The `<em>` element indicates emphasis that subtly changes the meaning of a sentence.

- The `<blockquote>` element is used for longer quotes that take up an entire paragraph. Note how the <p> element is still used inside the <blockquote> element. Browsers tend to 
  indent the contents of the `<blockquote>` element.

- The `<q>` element is used for shorter quotes that sit within a paragraph. Browsers are supposed to put quotes around the `<q>` element, however Internet Explorer does not —
  therefore many people avoid using the `<q>` element.

- If you use an abbreviation or an acronym, then the `<abbr>` element can be used
  - Both elements may use the cite attribute to indicate where the quote is from. Its value should be a URL that will have more information about the source of the quotation. 
  - In HTML 4 there was a separate `<acronym>` element for acronyms. To spell out the full form of the acronym, the title attribute was used (as with the `<abbr>` element above).

- Browsers will render the content of a `<cite>` element in italics.

- The <dfn> element is used to indicate the defining instance of a new term 
  - Some browsers show the content of the `<dfn>` element in italics. Safari and Chrome do not change its appearance.

- The `<address>` element has quite a specific use: to contain contact details for the author of the page

- The `<s>` element indicates something that is no longer accurate or relevant (but that should not be deleted)
### ATTRIBUTES

- Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value,
  separated by an equals sign.

- The majority of attributes can only be used on certain elements, although a few attributes (such as lang ) can appear on any element.

- The value of the lang attribute is an abbreviated way of specifying which language is used inside the element that all browsers understand.


## HTML stands for HyperText Markup Language.


### Structural markup
- the elements that you can use to describe both headings and paragraphs


### Semantic markup
-  which provides extra information


### WHITE SPACE COLLAPSING
- When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single
  space too. This is known as white space collapsing.

### EMPTY ELEMENTS

- There are a few elements that do not have any words between an opening and closing tag. They are known as empty elements

- An empty element usually has only one tag. Before the closing angled bracket of an empty element there will often be a space and a forward slash character.
