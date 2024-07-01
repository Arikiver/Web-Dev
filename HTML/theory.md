# What is HTML?
    HTML stands for Hyper Text Markup Language
    HTML is the standard markup language for creating Web pages
    HTML describes the structure of a Web page
    HTML consists of a series of elements
    HTML elements tell the browser how to display the content
    HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

**HTML is Not Case Sensitive**

---

# HTML elements:
    The HTML element is everything from the start tag to the end tag:

    <tagname>Content goes here...</tagname>

    Nested HTML Elements:
        HTML elements can be nested (this means that elements can contain other elements).

    Empty HTML Elements
        HTML elements with no content are called empty elements.

        The <br> tag defines a line break, and is an empty element without a closing tag:

# HTML Attributes:
    All HTML elements can have attributes
    Attributes provide additional information about elements
    Attributes are always specified in the start tag
    Attributes usually come in name/value pairs like: name="value"

    eg:
        <a href="https://www.w3schools.com">Visit W3Schools</a> -- here "href" is the name and "https://www.w3schools.com" is the value.
        <img src="img_girl.jpg"> -- here "src" is the name and "img_girl.jpg" is the value.

    ==The src Attribute:==
        The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:
            <img src="img_girl.jpg">

        There are two ways to specify the URL in the src attribute:

        1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

        Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

        2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

        Tip: It is almost always best to use relative URLs. They will not break if you change domain.

    *Tip:*
        Always Use Lowercase Attributes
        Always Quote Attribute Values

## Elements summary:
    All HTML elements can have attributes
    The href attribute of <a> specifies the URL of the page the link goes to
    The src attribute of <img> specifies the path to the image to be displayed
    The width and height attributes of <img> provide size information for images
    The alt attribute of <img> provides an alternate text for an image
    The style attribute is used to add styles to an element, such as color, font, size, and more
    The lang attribute of the <html> tag declares the language of the Web page
    The title attribute defines some extra information about an element

---

# HTML Headings:
    [headings.html](headings.html)

---

# HTML Paragraphs:
    [paragraphs.html](pragraphs.html)

---

# HTML Styles
    [styles.html](styles.html)\
    The HTML Style Attribute:\
        Setting the style of an HTML element, can be done with the style attribute.

        The HTML style attribute has the following syntax:

        <tagname style="property:value;">
        The property is a CSS property. The value is a CSS value.

---

# HTML Text Formatting
    [textformatting.html](textformatting.html)
