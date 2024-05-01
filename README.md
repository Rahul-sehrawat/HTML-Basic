# HTML IMP Questions


1. **what is HTMl:**

    HTML stands for HyperText Markup Language and is the language of the internet. It is the standard text formatting language used for creating and displaying pages on the Internet

2. **What is a marquee in HTML?**

    Marquee is used for scrolling text on a web page. It scrolls the image or text up, down, left, or right automatically. To apply for a marquee, you have to use `</marquee>` tags.

    ```
    
    ```

3. **What are void elements in HTML?**

    Void elements in HTML are tags that do not require a closing tag. They are used to insert images, line breaks, and other content that does not require additional information.For Example `<br />`, `<img />`, `<hr />`, etc.

4. **What are HTML Entities?**

    HTML Entities are special characters used to represent characters that cannot be typed on a keyboard. They are often used to display special symbols and foreign characters.

5. **What is the advantage of collapsing white space?**

    Collapsing white space in HTML can help to reduce the size of web pages and make them load faster. It involves removing unnecessary white space between HTML elements.

6. **What is semantic HTML?**

    Semantic HTML is a coding style. It is the use of HTML markup to reinforce the semantics or meaning of the content.For example: `<form>`, `<table>`, and `<article>`,

7. **What is SVG in HTML?**

    HTML SVG is used to describe the vector or raster graphics. SVG images and their behaviors are defined in XML text files. 

8. **How do you create nested web pages in HTML?**

    Nested web pages basically mean a webpage within a webpage. We can create nested web pages in HTML using the built-in iframe tag. The HTML `<iframe>` tag defines an inline frame

9. **What is the difference between the ‘id' and ‘class' attributes of HTML elements?**

    The ‘id' attribute defines a unique identifier for an HTML element, while the ‘class' attribute defines a class for a group of elements. An ‘id' can only be used once on a page, while a ‘class' can be used multiple times.

10. **What is the role of the `<meta>` tag in HTML?**

    The `<meta>` tag provides additional information about the web page, such as the author, description, and keywords. It is located within the `<head>` section of the HTML document.

11. **What is the role of the action attribute in HTML forms?**

    The action attribute is used to specify the URL of the script or program that will process the data submitted by the form. When the user clicks the submit button, the form data is sent to the specified URL for processing.

12. **What is the role of the method attribute in HTML forms?**

    The method attribute is used to specify the HTTP method that will be used to submit the form data. The two most common methods are GET and POST. GET is used to retrieve data from the server, while POST is used to send data to the server

13. **What is the difference between “display: none” and “visibility: hidden” when used as attributes to the HTML element?**

    Elements with “display: none” are not visible and do not take up any space on the page, while elements with “visibility: hidden” are not visible but still take up space.

14. **What is the difference between link tag `<link>` and anchor tag <a>?**

    The `<link>` tag links external resources, such as CSS stylesheets, to an HTML document. The `<a>` tag creates links to other pages or resources within the same document.

15. **Differnce between HTML tags and elements:**

    HTML elements are defined by a starting tag, may contain some content and a closing tag.For example, `<h1>` Heading 1`</h1>` is a HTML element but just `<h1>` is a starting tag and `</h1>` is a closing tag.    

16.  **How to optimize website assets loading?**

    -`CDN hosting` : A CDN or content delivery network is geographically distributed servers to help reduce latency.
    -`Minify scripts` : This reduces the overall file size of js and CSS files.
    -`Lazy Loading` : Instead of loading all the assets at once, the non-critical assets can be loaded on a need basis.

17. **What are the different kinds of Doctypes available?**

    Strict Doctype ,Transitional Doctype, Frameset Doctype    

18. **How can we club two or more rows or columns into a single row or column in an HTML table?**

    HTML provides two table attributes “rowspan” and “colspan” to make a cell span to multiple rows and columns respectively.

19. **In how many ways you can display HTML elements?**

    +`inline`: Using this we can display any block-level element as an inline element. The height and width attribute values of the element will not affect.

    +`block`: using this, we can display any inline element as a block-level element. 

    +`inline-block`: This property is similar to inline, except by using the display as inline-block, we can actually format the element using height and width values.

    +`flex`: It displays the container and element as a flexible structure. It follows flexbox property.

    +`inline-flex`: It displays the flex container as an inline element while its content follows the flexbox properties.

    +`grid`: It displays the HTML elements as a grid container.

    +`none`: Using this property we can hide the HTML element.

20. **What is the difference between `<figure>` tag and `<img>` tag?**

    The `<figure>` tag specifies the self-contained content, like diagrams, images, code snippets, etc. `<figure>` tag is used to semantically organize the contents of an image like image, image caption, etc., whereas the `<img>` tag is used to embed the picture in the HTML5 document

21. **What is the difference between `<meter>` tag and `<progress>` tag?**

    `<progress>` tag should be used when we want to show the completion progress of a task, whereas if we just want a scalar measurement within a known range or fraction value. Also, we can specify multiple extra attributes for `<meter>` tags like ‘form’, ‘low’, ‘high’, ‘min’, etc.

22. **Is drag and drop possible using HTML5 and how?**

    Yes, in HTML5 we can drag and drop an element. This can be achieved using the drag and drop-related events to be used with the element which we want to drag and drop.

23. **Explain the concept of web storage in HTML5.**

    This web storage helps in storing some of the static data in the local storage of the browser so that we do not need to fetch it from the server every time we need it.

    `Local Storage`: This helps in storing data that will be retained even though the user reopens the browser. It is stored for each webapp on different browsers.

    `Session Storage`: This is used for one session only. After the user closes the browser this gets deleted.

24. **What is the usage of a novalidate attribute for the form tag that is introduced in HTML5?**

    Its value is a boolean type that indicates whether or not the data being submitted by the form will be validated beforehand. By making this false, forms can be submitted without validation which helps users to resume later also.

25. **What are raster images and vector images?**

    `Raster Images`: The raster image is defined by the arrangement of pixels in a grid with exactly what color the pixel should be. Few raster file formats include PNG(.png), JPEG(.jpg), etc.

    `Vector Images`: The vector image is defined using algorithms with shape and path definitions that can be used to render the image on-screen written in a similar markup fashion. The file extension is .svg

26. **What is a manifest file in HTML5?**

    The manifest file is used to list down resources that can be cached. Browsers use this information to make the web page load faster than the first time. There are 3 sections in the manifest file

    `CACHE Manifest`: Files needs to be cached
    `Network`: File never to be cached, always need a network connection.
    `Fallback`: Fallback files in case a page is inaccessible

27. **What is URL Encoding? Why are URLs encoded in HTML?**

    URL Encoding is the process of encoding non-ASCII characters in URLs to a format that is universally accepted by web browsers. URLs are sent over the Internet using the ASCII character set. If a URL contains characters outside the ASCII set, the URL has to be converted. 
    URL is encoded in HTML as it converts non-ASCII characters into a format that can be transmitted over the web. The URL encoding replaces non-ASCII characters with a “%” followed by hexadecimal digits.

28. **What is HTML `<details>` tag.**

    HTML `<details>` tag is used to specify the additional details on the web page that the user can view or hide on demand.
    It is used together with a relevant tag known as `<summary>`. Technically, there is no need of summary tag, but if you ignore this then the browser will use some default text.
    