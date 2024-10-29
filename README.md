# Master HTML

## What is the Internet?

![the internet](https://github.com/user-attachments/assets/ceafe694-70b1-468d-8693-9224ce6048e2)

The Internet is a global network of interconnected computers and servers that communicate with each other using standardized protocols. It allows users to access and share data, communicate with others, and use various online services.

## How does the Internet work?

![working of internet](https://github.com/user-attachments/assets/c29a450c-ce51-4098-b036-a2ea3701dabf)

The Internet works by using a system of interconnected networks that use standardized protocols to communicate with each other. When you enter a URL into your web browser, your computer sends a request to a server, which then sends the requested data back to your computer. This data is transmitted over the Internet using protocols such as TCP/IP (Transmission Control Protocol/Internet Protocol).

## Why is HTML required?

HTML (Hypertext Markup Language) is required to create web pages that can be displayed on the Internet. HTML provides the structure and content that web browsers render to the user. Without HTML, web pages would not display text, images, links, or other multimedia content.

## What is HTML?

HTML is the standard markup language used to create web pages. It forms the backbone of a website, providing the structure and content that the web browser renders.

## History of HTML

HTML was first introduced in 1993 by Tim Berners-Lee, the inventor of the World Wide Web. Since then, it has undergone several revisions, with the latest version being HTML5.

## Basic HTML Structure

A basic HTML document consists of several core parts:

```html
<!DOCTYPE html> <!-- Declaration defining the document type as HTML5 -->
<html lang="en"> <!-- Root element specifying the language -->
<head>
  <meta charset="UTF-8"> <!-- Character encoding for the document -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Responsive design settings -->
  <title>Document Title</title> <!-- Title shown in the browser tab -->
</head>
<body>
  <!-- Main content of the webpage goes here -->
</body>
</html>
```

### Explanation:

-   **<!DOCTYPE html>**: Specifies HTML5 as the document type.
-   **<html>**: Root element; the entire document is contained within this tag.
-   **<head>**: Contains meta-information about the document (e.g., title, metadata).
-   **<body>**: Holds the content displayed on the page (e.g., text, images, links).

HTML Tags
---------

HTML tags define elements on a web page. Most HTML elements have an opening tag and a closing tag (e.g., `<p>...</p>`). Some tags are self-closing (e.g., `<img>`).

Example of HTML Tags:

`<p>This is a paragraph.</p> <!-- Defines a paragraph of text -->
<img src="image.jpg" alt="Description of the image"> <!-- Embeds an image -->`

HTML Elements
-------------

HTML elements are used to structure web content. Each element serves a specific purpose, such as defining headings, paragraphs, links, and more.

### Headings

HTML provides six levels of headings, from `<h1>` to `<h6>`, with `<h1>` being the most important and `<h6>` the least.

`<h1>Main Heading</h1>`
`<h2>Subheading</h2>`

### Paragraphs


`<p>This is a paragraph of text.</p>`

Paragraphs help organize content into readable blocks.

### Links

Links allow users to navigate between pages or websites.



`<a href="https://www.example.com">Visit Example Website</a>`

-   `href`: Specifies the URL the link points to.

### Images

Images add visual content to a webpage.


`<img src="image.jpg" alt="Image Description">`

-   `src`: Source of the image.
-   `alt`: Text description for accessibility.

### Lists

Lists organize items in a structured manner.

#### Unordered List




`<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>`

#### Ordered List





`<ol>
  <li>First Item</li>
  <li>Second Item</li>
  <li>Third Item</li>
</ol>`

Semantic HTML
-------------

### What is Semantic HTML?

Semantic HTML uses elements that convey meaning and context to the structure of a webpage, aiding accessibility and search engine optimization (SEO).

### Semantic HTML Elements

Some commonly used semantic elements:

-   `<header>`: Defines the header of a webpage or section.
-   `<nav>`: Contains the primary navigation links.
-   `<main>`: Indicates the main content of the webpage.
-   `<section>`: Defines a section within the document.
-   `<article>`: Represents independent content or articles.
-   `<aside>`: Contains content related to the main content.
-   `<footer>`: Defines the footer at the end of a page or section.

Example:





`<header>
  <h1>Website Title</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
  </nav>
</header>
<main>
  <section>
    <article>
      <h2>Article Title</h2>
      <p>Article content...</p>
    </article>
  </section>
</main>
<footer>
  <p>Contact us at info@example.com</p>
</footer>`

HTML Tables
-----------

Tables organize data in rows and columns.

### Creating a Table

html



`<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Cell 1</td>
    <td>Cell 2</td>
  </tr>
  <tr>
    <td>Cell 3</td>
    <td>Cell 4</td>
  </tr>
</table>`

### Explanation:

-   `<table>`: Creates the table.
-   `<tr>`: Defines a table row.
-   `<th>`: Creates a header cell in the row.
-   `<td>`: Creates a standard cell.

HTML Forms
----------

Forms enable user input on a webpage, such as for login, registration, or feedback.

### Creating a Form

html



`<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <input type="submit" value="Submit">
</form>`

### Explanation:

-   `<form>`: Encapsulates form elements.
-   `action`: Specifies where to send form data.
-   `method`: Defines the HTTP method used (`GET` or `POST`).
-   `<label>`: Describes the form field.
-   `<input>`: Field for user input.

Best Practices
--------------

1.  **Keep it Simple**: Write clean, simple HTML for readability.
2.  **Use Semantic HTML**: Provides meaning to the structure, improving SEO and accessibility.
3.  **Validate Your Code**: Use validators to catch errors in HTML.
4.  **Comment Your Code**: Use comments to explain complex sections.
5.  **Organize CSS Separately**: Keep styling in external CSS files for cleaner code.

## Contact

Feel free to reach out if you have any questions or suggestions!

- [Website](https://adityadhiman.in)
- [GitHub](https://github.com/adityadhiman-in)
- [LinkedIn](https://www.linkedin.com/in/adityadhiman-in)

Made with ❤️ by [Aditya Dhiman](https://adityadhiman.in)

