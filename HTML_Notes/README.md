## Introduction

### Introduction to HTML

HTML, or HyperText Markup Language, is the standard language used to create and design documents on the World Wide Web. It is the backbone of web development, providing the basic structure of web pages. HTML is used to orga## Introduction

### Introduction to HTML

HTML, or HyperText Markup Language, is the standard language used to create and design documents on the World Wide Web. It is the backbone of web development, providing the basic structure of web pages. HTML is used to organize content and elements on a web page, such as text, images, links, and other multimedia.

### Key Points about HTML:

1. **Markup Language**: HTML is not a programming language; it's a markup language. It uses a system of tags to annotate text, images, and other content for display in a web browser.
2. **HyperText**: The "HyperText" part of HTML refers to the ability to create links that connect to other documents, making it easy to navigate between web pages.
3. **Web Page Structure**: HTML provides the basic structure of a web page, which is then enhanced and modified by other technologies like CSS (Cascading Style Sheets) and JavaScript.
4. **Cross-Platform Compatibility**: HTML is a cross-platform language, meaning it can be used on different types of devices and operating systems. Web browsers, such as Google Chrome, Mozilla Firefox, and Microsoft Edge, are designed to interpret HTML and render web pages accordingly.
5. **Evolution of HTML**: HTML has evolved over the years, with HTML5 being the latest version. HTML5 introduced new elements and attributes that provide more functionality and are designed to support multimedia and graphical content without the need for additional plugins.

## How HTML work in browser?

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3c43b6f9-f834-47e5-a7c0-02dc3ba52eca/Untitled.png)

## Boilerplate

<!DOCTYPE html> 
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
<!-- Add any additional meta tags, stylesheets, or scripts here -->
</head>
<body>

```
<!-- Your HTML content goes here -->

<!-- JavaScript code can be placed at the end of the body tag for better performance -->

```

</body>
</html>

Each section of the HTML boilerplate serves a specific purpose:

- `<!DOCTYPE html>`: Declares the document type and version of HTML being used.
- `<html lang="en">`: Defines the language of the document, in this case, English.
- `<head>`: Contains meta-information about the document, such as character encoding, viewport settings, and the document title.
- `<meta charset="UTF-8">`: Sets the character encoding to UTF-8, which supports a wide range of characters.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport properties for responsive design, ensuring the page renders properly on various devices and screen sizes.
- `<title>Document</title>`: Sets the title of the document, which appears in the browser tab.
- `<body>`: Contains the content of the HTML document, including text, images, links, and other elements.
- Comments (`<!-- -->`): Used to provide explanations or notes within the HTML code without affecting the document's rendering in the browser.

## SHORTCUT KEY

1. ALT + SHIFT + DOWN ARROW KEY (for doing copy of whole element).
2. ALT + Select tag one and then second tag (for do changes in both at once).
3. CTRL + /  arrow at the end of the word or end of the tag (for single line comment).
4. 

## EMMET

Emmet is a powerful toolkit for web developers that allows for faster and more efficient HTML and CSS workflow. It's especially popular among front-end developers for its ability to generate HTML and CSS code using simple abbreviations and shortcuts.

Here's a brief overview of how Emmet works in HTML:

1. **Abbreviations**: Emmet allows you to use abbreviations to generate HTML quickly. For example, typing `div` and then pressing the Tab key will expand into `<div></div>`.
2. **Nested Elements**: Emmet makes it easy to create nested elements by using the `>` symbol. For example, `ul>li*3` will generate a `<ul>` with three `<li>` items inside.
3. **Attributes**: You can also specify attributes for elements using square brackets. For example, `a[href=#]` will generate an anchor `<a>` tag with the `href` attribute set to `#`.
4. **ID and Class**: Emmet allows you to specify IDs and classes for elements using `#` and `.` respectively. For example, `div#header` will generate a `<div>` with the `id` attribute set to `header`.
5. **Multiplication**: You can create multiple elements at once using multiplication. For example, `ul>li*5` will generate a `<ul>` with five `<li>` items inside.

Emmet greatly speeds up the process of writing HTML code, making it an essential tool for web developers looking to improve their productivity. It's supported by many popular code editors and IDEs, including Visual Studio Code, Sublime Text, and Atom.

## **Inline VS Block Elements**

In HTML, elements are categorized as either block-level elements or inline elements based on their default display behavior and layout characteristics.

**Block-level elements**

occupy the full width of their parent container and always start on a new line, thereby creating a block of content. They can contain other block-level elements as well as inline elements, making them ideal for structuring the main sections of a webpage. Common block-level elements include <div>

- 

, <p>, <h1> to <h6>, and <ul>. 
On the other hand,

**inline elements**

only take up as much width as necessary for their content and do not start on a new line, allowing them to sit within a line of text alongside other inline elements. They are typically used for small pieces of content within block-level elements, such as links, emphasized text, and images. Common inline elements include <span>, <a>, <strong>, and <img>.

## HTML TAGS(Genie Ashwani Suggested)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/88f0fa14-6200-4cab-a2e0-ef515a24eb59/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/d2a25774-bba2-473c-b040-5bc35b216fb8/Untitled.png)

### 1. `<html>`

**Description**: The root element of an HTML document.
**Attributes**:

- `lang`: Specifies the language of the document (e.g., `lang="en"` for English).

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/d907b5dd-9faf-4ef0-9456-5cfb5a421823/Untitled.png)

### 2. `<head>`

**Description**: Contains meta-information about the document.

**Attributes**: None.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/e32e1baf-dc78-48b7-b517-adfc2372cd08/Untitled.png)

### 3. `<title>`

**Description**

: Specifies the title of the document, shown in the browser’s title bar or tab.

**Attributes**

: None.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/86390ba3-8ca1-480c-bacb-cdbb193a7335/Untitled.png)

### 4. `<body>`

**Description**

: Contains the content of the HTML document.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
onload
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/f711ea46-b74e-428c-b81f-5f263eabbc3d/Untitled.png)

### 5. `<h1>` to `<h6>`

**Description**

: Defines HTML headings, with

```
<h1>
```

being the highest level and

```
<h6>
```

the lowest.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
title
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3b9a82e4-b853-4a72-a50d-1b9b2a98bfbe/Untitled.png)

### 6. `<p>`

**Description**

: Defines a paragraph of text.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

,

```
title
```

, and

```
align
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/80d9dd18-c93d-4505-8043-6799c04d6545/Untitled.png)

### 7. `<a>`

**Description**: Defines a hyperlink.
**Attributes**:

- `href`: Specifies the URL of the page the link goes to.
- `target`: Specifies where to open the linked document (e.g., `_blank` to open in a new tab).
- `rel`: Specifies the relationship between the current document and the linked document.
- `download`: Specifies that the target should be downloaded when the link is clicked.

Example:

<a href="[https://www.example.com](https://www.example.com/)" target="_blank" rel="noopener noreferrer">Visit Example</a>

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/dba6e984-6ee0-4ba4-b5ea-0aaaba238391/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/5583c481-730f-46f1-a9ab-a4936aacf2f8/Untitled.png)

### 8. `<img>`

**Description**: Embeds an image in the document.
**Attributes**:

- `src`: Specifies the path to the image.
- `alt`: Provides alternative text if the image cannot be displayed.
- `width` and `height`: Specifies the width and height of the image.
- `title`: Provides additional information about the image (shown as a tooltip).

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/1289b700-13ff-4b91-92a5-3f989956ee92/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2a67625f-59fc-49a1-9711-d3bdf0f14220/Untitled.png)

### 9. `<ul>`

**Description**

: Defines an unordered list.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

, and

```
style
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/9b0f4884-1a65-4391-a9a3-a66ebafdc432/Untitled.png)

### 10. `<ol>`

**Description**: Defines an ordered list.
**Attributes**:

- `type`: Specifies the type of numbering (`1`, `A`, `a`, `I`, `i`).
- `start`: Specifies the starting number of the list.
- `reversed`: Reverses the numbering order.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/ce862cce-1cf2-4e16-92f0-0367174b2561/Untitled.png)

### 11. `<li>`

**Description**

: Defines a list item.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
value
```

(for ordered lists).

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/7832a492-6cc5-413c-be67-140c25de1910/Untitled.png)

### 12. `<div>`

**Description**

: Defines a division or a section in an HTML document.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

, and

```
style
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/76f0737f-6a2a-4873-9a1b-42d226af40ff/Untitled.png)

### 13. `<span>`

**Description**

: Defines a section in a document.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

, and

```
style
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/5ff6d224-54be-4747-a5fc-6454694e09ca/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2dc93303-dfed-401b-a6d7-60a9b60c0236/Untitled.png)

### 14. `<table>`

**Description**

: Defines a table.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
border
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/e64e4df0-b316-4fcc-93e3-1168ae32c062/Untitled.png)

### 15. `<tr>`

**Description**

: Defines a row in a table.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

, and

```
style
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2e37f942-631a-4156-a729-3f2e699b6972/Untitled.png)

### 16. `<th>`

**Description**

: Defines a header cell in a table.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
scope
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/243569d3-f84d-4c01-be67-28066c4547e1/Untitled.png)

### 17. `<td>`

**Description**

: Defines a cell in a table.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
colspan
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/16a0bed8-816d-4e46-9065-001919f680ba/Untitled.png)

### 18. `<form>`

A form is created using the <form> element, which acts as a container for various input elements. The basic structure of a form includes attributes like action and method that specify how form data is submitted.

***<form action="/submit-form" method="post">***

***<!-- Form elements go here -->***

***</form>***

There are various types of input elements:

1. <input type="text">
2. <input type="password">
3. <input type="email">
4. <input type="number">
5. <input type="tel"> etc..

**Description**: Defines an HTML form for user input.
**Attributes**:

- `action`: Specifies where to send the form data.
- `method`: Specifies the HTTP method to use (`GET` or `POST`).
- `name`: Specifies the name of the form.
- `target`: Specifies where to display the response.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/c5d830b4-c73b-4ec3-8613-e8c4ca323f0f/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/22aac8c6-31f2-45aa-9fd0-0220b78c23d4/Untitled.png)

### 19. `<input>`

**Description**: Defines an input control.
**Attributes**:

- `type`: Specifies the type of input (`text`, `password`, `submit`, etc.).
- `name`: Specifies the name of the input.
- `value`: Specifies the default value.
- `placeholder`: Specifies a short hint inside the input.
- `required`: Specifies that the input field is required.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/b6c56778-49dc-4761-814b-280609bbfd4c/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3a0862ea-d470-4cd2-868d-8f33e5b20e15/Untitled.png)

### 20. `<textarea>`

**Description**: Defines a multi-line text input control.
**Attributes**:

- `name`: Specifies the name of the textarea.
- `rows`: Specifies the number of visible text lines.
- `cols`: Specifies the visible width of the text area.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/bc55b99d-d16d-4e5c-97dc-bd2c4fa7c6ab/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/f435c458-3be4-4f16-b155-b18a01d661fd/Untitled.png)

### 21. `<select>`

**Description**

: Defines a drop-down list.

**Attributes**:

- `name`: Specifies the name of the select element.
- `multiple`: Allows multiple selections.
- `size`: Specifies the number of visible options.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/8a21a692-cd8a-4018-9837-446f364fc0b0/Untitled.png)

### 22. `<option>`

**Description**: Defines an option in a drop-down list.
**Attributes**:

- `value`: Specifies the value to be sent to a server.
- `selected`: Specifies that the option should be pre-selected when the page loads.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/25602c42-5e35-46de-ad9c-45174740526f/Untitled.png)

### 23. `<button>`

**Description**: Defines a clickable button.
**Attributes**:

- `type`: Specifies the type of button (`button`, `submit`, `reset`).
- `name`: Specifies the name of the button.
- `value`: Specifies the initial value of the button.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/b08c398a-d7be-489b-9e76-41092b8e5612/Untitled.png)

### 24. `<label>`

**Description**: Defines a label for an input element.
**Attributes**:

- `for`: Specifies which form element a label is bound to.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3d07419d-f4e0-4982-85c3-5fd1ea4df030/Untitled.png)

### 25. `<iframe>`

**Description**: Defines an inline frame, which can embed another HTML page within the current page.
**Attributes**:

- `src`: Specifies the URL of the page to embed.
- `width` and `height`: Specifies the width and height of the iframe.
- `name`: Specifies the name of the iframe.
- `frameborder`: Specifies whether or not to display a border around the iframe.
- `allowfullscreen`: Allows the iframe to be displayed in fullscreen mode.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/37106112-7cbd-4437-bc41-1905b0c22a30/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/5c11125f-03b0-4c2c-baa7-9d17a37f067e/Untitled.png)

### 26. `<meta>`

**Description**: Provides metadata about the HTML document.
**Attributes**:

- `charset`: Specifies the character encoding for the HTML document.
- `name`: Specifies the name of the metadata.
- `content`: Specifies the value of the metadata.
- `http-equiv`: Provides an HTTP header for the information/value of the content attribute.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/0c897132-3ffc-44d8-b002-ef1b489ac87f/Untitled.png)

### 27. `<style>`

**Description**

: Contains style information (CSS) for a document.

**Attributes**

: Common attributes include

```
type
```

(usually set to "text/css").

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/64f6b946-42e1-42c2-8bc3-b60c5231adb1/Untitled.png)

### 28. `<script>`

**Description**

: Used to embed or reference executable code; typically used to embed JavaScript.

**Attributes**:

- `src`: Specifies the URL of an external script file.
- `type`: Specifies the scripting language (usually "text/javascript").
- `defer`: Indicates that the script should be executed after the document has been parsed.
- `async`: Indicates that the script should be executed asynchronously.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/ab4ffcfc-411a-454a-b34f-9b1147160c34/Untitled.png)

### 29. `<link>`

**Description**: Defines the relationship between the current document and an external resource; commonly used to link to stylesheets.
**Attributes**:

- `rel`: Specifies the relationship between the current document and the linked document (e.g., "stylesheet").
- `href`: Specifies the URL of the linked document.
- `type`: Specifies the media type of the linked document.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/5b32faab-6ae2-468c-9f79-1956ebf06d10/Untitled.png)

### 30. `<!DOCTYPE>`

**Description**

: Declares the document type and version of HTML.

**Attributes**

: None.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/a8b35cbd-d973-4077-95aa-12b25c7dc660/Untitled.png)

## Other Tags (Chai aur code)

### 1.`<hr>` Tag

The `<hr>` tag is used to insert a horizontal rule (a horizontal line) in a web page. It is a self-closing tag, meaning it does not have a closing tag.

### Notes:

- **Purpose**: The `<hr>` tag is primarily used to separate content or define a thematic break in an HTML page.
- **Styling**: By default, it creates a simple horizontal line, but it can be styled using CSS to change its width, color, height, and other properties.
- Example attributes: `align`, `color`, `noshade`, `size`, `width`.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/84652185-86d0-4f28-8b8f-33c965784ebe/Untitled.png)

### 2.`<br>` Tag

The `<br>` tag is used to insert a line break in a web page. It is also a self-closing tag.

- Example attribute: `clear`.

### Notes:

- **Purpose**: The `<br>` tag is used to start a new line within text content without starting a new block-level element (like a paragraph).
- **Common Use**: Often used within paragraphs or other inline elements to add line breaks without extra spacing.
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/13b4e2d1-afeb-44fa-8831-029c12866dc5/Untitled.png)
    

## 3. `<pre>` Tag

The `<pre>` tag is used to define preformatted text. Text inside a `<pre>` element is displayed in a fixed-width font (usually Courier) and preserves both spaces and line breaks.

### Notes:

- **Purpose**: The `<pre>` tag is used when you want to display text exactly as it is written, preserving spaces and line breaks.
- **Styling**: By default, it uses a monospace font, but can be styled with CSS.
- Example attribute: `width`.

### Example:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/817f0979-47ff-4a4d-bab9-f287cb8e839a/Untitled.png)

## Inline Text Formatting Tags

### 1. `<b>` Tag

- **Meaning**: The `<b>` tag is used to make text bold without adding any extra importance.
- **Attributes**: None specific to `<b>`.
- **Example**:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2948b318-e075-4ee0-8d1d-552a5bc5c249/Untitled.png)

### 2. `<strong>` Tag

- **Meaning**: The `<strong>` tag is used to indicate that the text is of strong importance, and it is typically rendered in bold.
- **Attributes**: None specific to `<strong>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/e61d0193-721c-4b06-9f22-22bdc49d3052/Untitled.png)

### 3. `<i>` Tag

- **Meaning**: The `<i>` tag is used to make text italic without implying any extra emphasis or importance.
- **Attributes**: None specific to `<i>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/b3b75368-a029-44b3-a45c-2e65a4f386a5/Untitled.png)

### 4. `<em>` Tag

- **Meaning**: The `<em>` tag is used to emphasize text, typically rendering it in italics. The emphasis can change the meaning of the sentence.
- **Attributes**: None specific to `<em>`.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/f78eef5a-d242-46fd-a2a8-f2a81787c668/Untitled.png)

### 5. `<small>` Tag

- **Meaning**: The `<small>` tag is used to decrease the font size of the text.
- **Attributes**: None specific to `<small>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/a611aa47-8d67-4c5d-bc54-80f598101d35/Untitled.png)

### 6. `<sub>` Tag

- **Meaning**: The `<sub>` tag is used to display text as subscript (below the baseline).
- **Attributes**: None specific to `<sub>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/04ce9855-f428-4049-8a38-cccb2f617cc2/Untitled.png)

### 7. `<del>` Tag

- **Meaning**: The `<del>` tag is used to indicate deleted or removed text, often rendered with a strikethrough.
- **Attributes**:
    - `cite`: URL of a document that explains the change.
    - `datetime`: Date and time of when the text was deleted.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/787468e8-6b90-4934-8baa-4364c571a0a4/Untitled.png)

### 8. `<mark>` Tag

- **Meaning**: The `<mark>` tag is used to highlight or mark text, typically rendered with a yellow background.
- **Attributes**: None specific to `<mark>`.
- **Example**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/ae42930f-2644-4a71-83df-19d1a0a57509/Untitled.png)

### 9. `<style>` Tag

- **Meaning**: The `<style>` tag is used to define internal CSS styles.
- **Attributes**:
    - `media`: Specifies the media type(s) for which the styles are defined.
    - `type`: Specifies the MIME type of the `<style>` tag. Default is "text/css".
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2ffe52a4-383d-4162-87d0-58514ee9eae0/Untitled.png)

### 10. `<blockquote>` Tag

The `<blockquote>` tag is used to define a section that is quoted from another source. It typically displays the quoted text as an indented block.

### Attributes:

- **`cite`**: Specifies the URL of the source of the quote.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/82717dfc-fdff-4fcb-83a2-61967a894489/Untitled.png)

### 11. `<q>` Tag

The `<q>` tag is used for short quotations. Browsers usually insert quotation marks around the text contained within the `<q>` element.

### Attributes:

- **`cite`**: Specifies the URL of the source of the quote.

### Example:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/756f9dc2-5cd5-4a9e-99f1-0b80c0a37ddd/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/52bc5ed1-8bee-4108-ada9-55e5687f5666/Untitled.png)

### 12.`<abbr>` Tag

The `<abbr>` tag is used to define an abbreviation or acronym. When used, it provides a full description when hovered over (often via the `title` attribute).

### Attributes:

- **`title`**: Specifies the full description or expansion of the abbreviation.

### Example:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/1fa90c5a-1e8b-491a-aa92-fb19454c00a1/Untitled.png)

### 13. `<address>` Tag

The `<address>` tag is used to define contact information for the author/owner of a document or an article. It typically renders in italics and includes line breaks where appropriate.

### Attributes: None specific to `<address>`.

### Example:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/9db5cd4d-08af-4e9e-8e85-e55d1c0031ca/Untitled.png)

### 14. `<cite>` Tag

The `<cite>` tag is used to reference the title of a creative work (like a book, website, article, etc.). It typically renders the text in italics.

### Attributes: None specific to `<cite>`.

### Example:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/483e1a71-1bc2-4bce-8436-61b23ed39eac/Untitled.png)

### 15.`<bdo>` Tag

The `<bdo>` (bidirectional override) tag is used to override the current text direction.

### Attributes:

- **`dir`**: Specifies the text direction. Values can be `ltr` (left-to-right) or `rtl` (right-to-left).

### Example:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/70be6490-6365-4034-bce5-8f8f6d596720/Untitled.png)

### 16. `<map>` Tag

The `<map>` tag is used to define an image map. An image map is an image with clickable areas, which can be linked to different destinations. The `<map>` element is used in conjunction with the `<area>` element to define the clickable areas.

### Attributes of the `<map>` Tag:

- **`name`**: Specifies the name of the image map. This name is referenced by the `usemap` attribute in the `<img>` element.

### Attributes of the `<area>` Tag (used within `<map>`):

- **`shape`**: Specifies the shape of the clickable area. Possible values are `rect` (rectangle), `circle`, and `poly` (polygon).
- **`coords`**: Specifies the coordinates for the shape. The format and number of values depend on the shape.
    - For `rect`: `coords="x1,y1,x2,y2"`
    - For `circle`: `coords="x,y,radius"`
    - For `poly`: `coords="x1,y1,x2,y2,x3,y3,...,xn,yn"`
- **`href`**: Specifies the URL of the page to link to.
- **`alt`**: Provides alternative text for the area, used for accessibility.
- **`target`**: Specifies where to open the linked document (like in a new tab).

### Example of Using the `<map>` Tag

Here is an example that demonstrates how to use the `<map>` tag with an image map. The image will have three clickable areas: a rectangle, a circle, and a polygon.

### HTML Code:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/116a2465-158b-4adb-9e4b-1d0ae95649dc/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/d6fb0ec2-1338-4d48-9a23-c14a3943cead/Untitled.png)

## HTML5 Semantic Tags:

### 1. `<article>` Tag

- **Meaning**: Represents a self-contained composition in a document, page, or site.
- **Attributes**: None specific to `<article>`.
- **Example**:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/f3e36414-ff8d-4c84-b911-6a31d67f2fc1/Untitled.png)

### 2. `<aside>` Tag

- **Meaning**: Represents content that is tangentially related to the content around it (like a sidebar).
- **Attributes**: None specific to `<aside>`.
- **Example**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/54aa34e9-fb3e-49e3-ac52-ba10e3c5e0ea/Untitled.png)

### 3. `<details>` Tag

- **Meaning**: Represents a disclosure widget from which the user can obtain additional information or controls.
- **Attributes**: None specific to `<details>`.
- **Example**:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/ab2ff85f-f053-43cd-a6d9-db35c6394e10/Untitled.png)

### 4. `<figcaption>` Tag

- **Meaning**: Represents a caption or legend for a figure.
- **Attributes**: None specific to `<figcaption>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/bdebd005-23ef-4b9a-af08-afb6bdf30167/Untitled.png)

### 5. `<figure>` Tag

- **Meaning**: Represents self-contained content, such as illustrations, diagrams, photos, code listings, etc.
- **Attributes**: None specific to `<figure>`.
- **Example**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/6602aeb1-bcf7-433a-a8e6-5671d26aa7d7/Untitled.png)

### 6. `<footer>` Tag

- **Meaning**: Represents a footer for its nearest sectioning content or sectioning root element.
- **Attributes**: None specific to `<footer>`.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/61661ff9-9e5d-40da-bffe-67e925d1720d/Untitled.png)

### 7. `<header>` Tag

- **Meaning**: Represents introductory content, typically a group of introductory or navigational aids.
- **Attributes**: None specific to `<header>`.
- **Example**:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/9cf006cf-c222-4114-b80b-d0c559e752c6/Untitled.png)

### 8. `<main>` Tag

- **Meaning**: Represents the dominant content of the <body> of a document.
- **Attributes**: None specific to `<main>`.
- Example:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3f8b0e91-f861-47e5-be0d-bf83a555f154/Untitled.png)

### 9. `<nav>` Tag

- **Meaning**: Represents a section of a page intended for navigation links.
- **Attributes**: None specific to `<nav>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/1a73ef52-dd81-4ad2-8fb5-2f50b9508140/Untitled.png)

### 10. `<section>` Tag

- **Meaning**: Represents a generic section of a document, used to group together related content.
- **Attributes**: None specific to `<section>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/e0ae1da7-d890-4af8-867f-d1bd9c6a8852/Untitled.png)

### 11. `<summary>` Tag

- **Meaning**: Represents a summary, legend, or caption for the `<details>` element.
- **Attributes**: None specific to `<summary>`.nize content and elements on a web page, such as text, images, links, and other multimedia.

### Key Points about HTML:

1. **Markup Language**: HTML is not a programming language; it's a markup language. It uses a system of tags to annotate text, images, and other content for display in a web browser.
2. **HyperText**: The "HyperText" part of HTML refers to the ability to create links that connect to other documents, making it easy to navigate between web pages.
3. **Web Page Structure**: HTML provides the basic structure of a web page, which is then enhanced and modified by other technologies like CSS (Cascading Style Sheets) and JavaScript.
4. **Cross-Platform Compatibility**: HTML is a cross-platform language, meaning it can be used on different types of devices and operating systems. Web browsers, such as Google Chrome, Mozilla Firefox, and Microsoft Edge, are designed to interpret HTML and render web pages accordingly.
5. **Evolution of HTML**: HTML has evolved over the years, with HTML5 being the latest version. HTML5 introduced new elements and attributes that provide more functionality and are designed to support multimedia and graphical content without the need for additional plugins.

## How HTML work in browser?

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3c43b6f9-f834-47e5-a7c0-02dc3ba52eca/Untitled.png)

## Boilerplate

<!DOCTYPE html> 
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
<!-- Add any additional meta tags, stylesheets, or scripts here -->
</head>
<body>

```
<!-- Your HTML content goes here -->

<!-- JavaScript code can be placed at the end of the body tag for better performance -->

```

</body>
</html>

Each section of the HTML boilerplate serves a specific purpose:

- `<!DOCTYPE html>`: Declares the document type and version of HTML being used.
- `<html lang="en">`: Defines the language of the document, in this case, English.
- `<head>`: Contains meta-information about the document, such as character encoding, viewport settings, and the document title.
- `<meta charset="UTF-8">`: Sets the character encoding to UTF-8, which supports a wide range of characters.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport properties for responsive design, ensuring the page renders properly on various devices and screen sizes.
- `<title>Document</title>`: Sets the title of the document, which appears in the browser tab.
- `<body>`: Contains the content of the HTML document, including text, images, links, and other elements.
- Comments (`<!-- -->`): Used to provide explanations or notes within the HTML code without affecting the document's rendering in the browser.

## SHORTCUT KEY

1. ALT + SHIFT + DOWN ARROW KEY (for doing copy of whole element).
2. ALT + Select tag one and then second tag (for do changes in both at once).
3. CTRL + /  arrow at the end of the word or end of the tag (for single line comment).
4. 

## EMMET

Emmet is a powerful toolkit for web developers that allows for faster and more efficient HTML and CSS workflow. It's especially popular among front-end developers for its ability to generate HTML and CSS code using simple abbreviations and shortcuts.

Here's a brief overview of how Emmet works in HTML:

1. **Abbreviations**: Emmet allows you to use abbreviations to generate HTML quickly. For example, typing `div` and then pressing the Tab key will expand into `<div></div>`.
2. **Nested Elements**: Emmet makes it easy to create nested elements by using the `>` symbol. For example, `ul>li*3` will generate a `<ul>` with three `<li>` items inside.
3. **Attributes**: You can also specify attributes for elements using square brackets. For example, `a[href=#]` will generate an anchor `<a>` tag with the `href` attribute set to `#`.
4. **ID and Class**: Emmet allows you to specify IDs and classes for elements using `#` and `.` respectively. For example, `div#header` will generate a `<div>` with the `id` attribute set to `header`.
5. **Multiplication**: You can create multiple elements at once using multiplication. For example, `ul>li*5` will generate a `<ul>` with five `<li>` items inside.

Emmet greatly speeds up the process of writing HTML code, making it an essential tool for web developers looking to improve their productivity. It's supported by many popular code editors and IDEs, including Visual Studio Code, Sublime Text, and Atom.

## **Inline VS Block Elements**

In HTML, elements are categorized as either block-level elements or inline elements based on their default display behavior and layout characteristics.

**Block-level elements**

occupy the full width of their parent container and always start on a new line, thereby creating a block of content. They can contain other block-level elements as well as inline elements, making them ideal for structuring the main sections of a webpage. Common block-level elements include <div>

- 

, <p>, <h1> to <h6>, and <ul>. 
On the other hand,

**inline elements**

only take up as much width as necessary for their content and do not start on a new line, allowing them to sit within a line of text alongside other inline elements. They are typically used for small pieces of content within block-level elements, such as links, emphasized text, and images. Common inline elements include <span>, <a>, <strong>, and <img>.

## HTML TAGS(Genie Ashwani Suggested)

### 1. `<html>`

**Description**: The root element of an HTML document.
**Attributes**:

- `lang`: Specifies the language of the document (e.g., `lang="en"` for English).

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/d907b5dd-9faf-4ef0-9456-5cfb5a421823/Untitled.png)

### 2. `<head>`

**Description**: Contains meta-information about the document.

**Attributes**: None.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/e32e1baf-dc78-48b7-b517-adfc2372cd08/Untitled.png)

### 3. `<title>`

**Description**

: Specifies the title of the document, shown in the browser’s title bar or tab.

**Attributes**

: None.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/86390ba3-8ca1-480c-bacb-cdbb193a7335/Untitled.png)

### 4. `<body>`

**Description**

: Contains the content of the HTML document.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
onload
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/f711ea46-b74e-428c-b81f-5f263eabbc3d/Untitled.png)

### 5. `<h1>` to `<h6>`

**Description**

: Defines HTML headings, with

```
<h1>
```

being the highest level and

```
<h6>
```

the lowest.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
title
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3b9a82e4-b853-4a72-a50d-1b9b2a98bfbe/Untitled.png)

### 6. `<p>`

**Description**

: Defines a paragraph of text.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

,

```
title
```

, and

```
align
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/80d9dd18-c93d-4505-8043-6799c04d6545/Untitled.png)

### 7. `<a>`

**Description**: Defines a hyperlink.
**Attributes**:

- `href`: Specifies the URL of the page the link goes to.
- `target`: Specifies where to open the linked document (e.g., `_blank` to open in a new tab).
- `rel`: Specifies the relationship between the current document and the linked document.
- `download`: Specifies that the target should be downloaded when the link is clicked.

Example:

<a href="[https://www.example.com](https://www.example.com/)" target="_blank" rel="noopener noreferrer">Visit Example</a>

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/dba6e984-6ee0-4ba4-b5ea-0aaaba238391/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/5583c481-730f-46f1-a9ab-a4936aacf2f8/Untitled.png)

### 8. `<img>`

**Description**: Embeds an image in the document.
**Attributes**:

- `src`: Specifies the path to the image.
- `alt`: Provides alternative text if the image cannot be displayed.
- `width` and `height`: Specifies the width and height of the image.
- `title`: Provides additional information about the image (shown as a tooltip).

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/1289b700-13ff-4b91-92a5-3f989956ee92/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2a67625f-59fc-49a1-9711-d3bdf0f14220/Untitled.png)

### 9. `<ul>`

**Description**

: Defines an unordered list.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

, and

```
style
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/9b0f4884-1a65-4391-a9a3-a66ebafdc432/Untitled.png)

### 10. `<ol>`

**Description**: Defines an ordered list.
**Attributes**:

- `type`: Specifies the type of numbering (`1`, `A`, `a`, `I`, `i`).
- `start`: Specifies the starting number of the list.
- `reversed`: Reverses the numbering order.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/ce862cce-1cf2-4e16-92f0-0367174b2561/Untitled.png)

### 11. `<li>`

**Description**

: Defines a list item.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
value
```

(for ordered lists).

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/7832a492-6cc5-413c-be67-140c25de1910/Untitled.png)

### 12. `<div>`

**Description**

: Defines a division or a section in an HTML document.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

, and

```
style
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/76f0737f-6a2a-4873-9a1b-42d226af40ff/Untitled.png)

### 13. `<span>`

**Description**

: Defines a section in a document.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

, and

```
style
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/5ff6d224-54be-4747-a5fc-6454694e09ca/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2dc93303-dfed-401b-a6d7-60a9b60c0236/Untitled.png)

### 14. `<table>`

**Description**

: Defines a table.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
border
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/e64e4df0-b316-4fcc-93e3-1168ae32c062/Untitled.png)

### 15. `<tr>`

**Description**

: Defines a row in a table.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

, and

```
style
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2e37f942-631a-4156-a729-3f2e699b6972/Untitled.png)

### 16. `<th>`

**Description**

: Defines a header cell in a table.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
scope
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/243569d3-f84d-4c01-be67-28066c4547e1/Untitled.png)

### 17. `<td>`

**Description**

: Defines a cell in a table.

**Attributes**

: Common attributes include

```
class
```

,

```
id
```

,

```
style
```

, and

```
colspan
```

.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/16a0bed8-816d-4e46-9065-001919f680ba/Untitled.png)

### 18. `<form>`

**Description**: Defines an HTML form for user input.
**Attributes**:

- `action`: Specifies where to send the form data.
- `method`: Specifies the HTTP method to use (`GET` or `POST`).
- `name`: Specifies the name of the form.
- `target`: Specifies where to display the response.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/c5d830b4-c73b-4ec3-8613-e8c4ca323f0f/Untitled.png)

### 19. `<input>`

**Description**: Defines an input control.
**Attributes**:

- `type`: Specifies the type of input (`text`, `password`, `submit`, etc.).
- `name`: Specifies the name of the input.
- `value`: Specifies the default value.
- `placeholder`: Specifies a short hint inside the input.
- `required`: Specifies that the input field is required.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/b6c56778-49dc-4761-814b-280609bbfd4c/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3a0862ea-d470-4cd2-868d-8f33e5b20e15/Untitled.png)

### 20. `<textarea>`

**Description**: Defines a multi-line text input control.
**Attributes**:

- `name`: Specifies the name of the textarea.
- `rows`: Specifies the number of visible text lines.
- `cols`: Specifies the visible width of the text area.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/bc55b99d-d16d-4e5c-97dc-bd2c4fa7c6ab/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/f435c458-3be4-4f16-b155-b18a01d661fd/Untitled.png)

### 21. `<select>`

**Description**

: Defines a drop-down list.

**Attributes**:

- `name`: Specifies the name of the select element.
- `multiple`: Allows multiple selections.
- `size`: Specifies the number of visible options.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/8a21a692-cd8a-4018-9837-446f364fc0b0/Untitled.png)

### 22. `<option>`

**Description**: Defines an option in a drop-down list.
**Attributes**:

- `value`: Specifies the value to be sent to a server.
- `selected`: Specifies that the option should be pre-selected when the page loads.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/25602c42-5e35-46de-ad9c-45174740526f/Untitled.png)

### 23. `<button>`

**Description**: Defines a clickable button.
**Attributes**:

- `type`: Specifies the type of button (`button`, `submit`, `reset`).
- `name`: Specifies the name of the button.
- `value`: Specifies the initial value of the button.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/b08c398a-d7be-489b-9e76-41092b8e5612/Untitled.png)

### 24. `<label>`

**Description**: Defines a label for an input element.
**Attributes**:

- `for`: Specifies which form element a label is bound to.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3d07419d-f4e0-4982-85c3-5fd1ea4df030/Untitled.png)

### 25. `<iframe>`

**Description**: Defines an inline frame, which can embed another HTML page within the current page.
**Attributes**:

- `src`: Specifies the URL of the page to embed.
- `width` and `height`: Specifies the width and height of the iframe.
- `name`: Specifies the name of the iframe.
- `frameborder`: Specifies whether or not to display a border around the iframe.
- `allowfullscreen`: Allows the iframe to be displayed in fullscreen mode.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/37106112-7cbd-4437-bc41-1905b0c22a30/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/5c11125f-03b0-4c2c-baa7-9d17a37f067e/Untitled.png)

### 26. `<meta>`

**Description**: Provides metadata about the HTML document.
**Attributes**:

- `charset`: Specifies the character encoding for the HTML document.
- `name`: Specifies the name of the metadata.
- `content`: Specifies the value of the metadata.
- `http-equiv`: Provides an HTTP header for the information/value of the content attribute.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/0c897132-3ffc-44d8-b002-ef1b489ac87f/Untitled.png)

### 27. `<style>`

**Description**

: Contains style information (CSS) for a document.

**Attributes**

: Common attributes include

```
type
```

(usually set to "text/css").

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/64f6b946-42e1-42c2-8bc3-b60c5231adb1/Untitled.png)

### 28. `<script>`

**Description**

: Used to embed or reference executable code; typically used to embed JavaScript.

**Attributes**:

- `src`: Specifies the URL of an external script file.
- `type`: Specifies the scripting language (usually "text/javascript").
- `defer`: Indicates that the script should be executed after the document has been parsed.
- `async`: Indicates that the script should be executed asynchronously.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/ab4ffcfc-411a-454a-b34f-9b1147160c34/Untitled.png)

### 29. `<link>`

**Description**: Defines the relationship between the current document and an external resource; commonly used to link to stylesheets.
**Attributes**:

- `rel`: Specifies the relationship between the current document and the linked document (e.g., "stylesheet").
- `href`: Specifies the URL of the linked document.
- `type`: Specifies the media type of the linked document.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/5b32faab-6ae2-468c-9f79-1956ebf06d10/Untitled.png)

### 30. `<!DOCTYPE>`

**Description**

: Declares the document type and version of HTML.

**Attributes**

: None.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/a8b35cbd-d973-4077-95aa-12b25c7dc660/Untitled.png)

## Other Tags (Chai aur code)

### 1.`<hr>` Tag

The `<hr>` tag is used to insert a horizontal rule (a horizontal line) in a web page. It is a self-closing tag, meaning it does not have a closing tag.

### Notes:

- **Purpose**: The `<hr>` tag is primarily used to separate content or define a thematic break in an HTML page.
- **Styling**: By default, it creates a simple horizontal line, but it can be styled using CSS to change its width, color, height, and other properties.
- Example attributes: `align`, `color`, `noshade`, `size`, `width`.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/84652185-86d0-4f28-8b8f-33c965784ebe/Untitled.png)

### 2.`<br>` Tag

The `<br>` tag is used to insert a line break in a web page. It is also a self-closing tag.

- Example attribute: `clear`.

### Notes:

- **Purpose**: The `<br>` tag is used to start a new line within text content without starting a new block-level element (like a paragraph).
- **Common Use**: Often used within paragraphs or other inline elements to add line breaks without extra spacing.
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/13b4e2d1-afeb-44fa-8831-029c12866dc5/Untitled.png)
    

## 3. `<pre>` Tag

The `<pre>` tag is used to define preformatted text. Text inside a `<pre>` element is displayed in a fixed-width font (usually Courier) and preserves both spaces and line breaks.

### Notes:

- **Purpose**: The `<pre>` tag is used when you want to display text exactly as it is written, preserving spaces and line breaks.
- **Styling**: By default, it uses a monospace font, but can be styled with CSS.
- Example attribute: `width`.

### Example:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/817f0979-47ff-4a4d-bab9-f287cb8e839a/Untitled.png)

## Inline Text Formatting Tags

### 1. `<b>` Tag

- **Meaning**: The `<b>` tag is used to make text bold without adding any extra importance.
- **Attributes**: None specific to `<b>`.
- **Example**:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2948b318-e075-4ee0-8d1d-552a5bc5c249/Untitled.png)

### 2. `<strong>` Tag

- **Meaning**: The `<strong>` tag is used to indicate that the text is of strong importance, and it is typically rendered in bold.
- **Attributes**: None specific to `<strong>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/e61d0193-721c-4b06-9f22-22bdc49d3052/Untitled.png)

### 3. `<i>` Tag

- **Meaning**: The `<i>` tag is used to make text italic without implying any extra emphasis or importance.
- **Attributes**: None specific to `<i>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/b3b75368-a029-44b3-a45c-2e65a4f386a5/Untitled.png)

### 4. `<em>` Tag

- **Meaning**: The `<em>` tag is used to emphasize text, typically rendering it in italics. The emphasis can change the meaning of the sentence.
- **Attributes**: None specific to `<em>`.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/f78eef5a-d242-46fd-a2a8-f2a81787c668/Untitled.png)

### 5. `<small>` Tag

- **Meaning**: The `<small>` tag is used to decrease the font size of the text.
- **Attributes**: None specific to `<small>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/a611aa47-8d67-4c5d-bc54-80f598101d35/Untitled.png)

### 6. `<sub>` Tag

- **Meaning**: The `<sub>` tag is used to display text as subscript (below the baseline).
- **Attributes**: None specific to `<sub>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/04ce9855-f428-4049-8a38-cccb2f617cc2/Untitled.png)

### 7. `<del>` Tag

- **Meaning**: The `<del>` tag is used to indicate deleted or removed text, often rendered with a strikethrough.
- **Attributes**:
    - `cite`: URL of a document that explains the change.
    - `datetime`: Date and time of when the text was deleted.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/787468e8-6b90-4934-8baa-4364c571a0a4/Untitled.png)

### 8. `<mark>` Tag

- **Meaning**: The `<mark>` tag is used to highlight or mark text, typically rendered with a yellow background.
- **Attributes**: None specific to `<mark>`.
- **Example**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/ae42930f-2644-4a71-83df-19d1a0a57509/Untitled.png)

### 9. `<style>` Tag

- **Meaning**: The `<style>` tag is used to define internal CSS styles.
- **Attributes**:
    - `media`: Specifies the media type(s) for which the styles are defined.
    - `type`: Specifies the MIME type of the `<style>` tag. Default is "text/css".
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/2ffe52a4-383d-4162-87d0-58514ee9eae0/Untitled.png)

## HTML5 Semantic Tags:

### 1. `<article>` Tag

- **Meaning**: Represents a self-contained composition in a document, page, or site.
- **Attributes**: None specific to `<article>`.
- **Example**:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/f3e36414-ff8d-4c84-b911-6a31d67f2fc1/Untitled.png)

### 2. `<aside>` Tag

- **Meaning**: Represents content that is tangentially related to the content around it (like a sidebar).
- **Attributes**: None specific to `<aside>`.
- **Example**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/54aa34e9-fb3e-49e3-ac52-ba10e3c5e0ea/Untitled.png)

### 3. `<details>` Tag

- **Meaning**: Represents a disclosure widget from which the user can obtain additional information or controls.
- **Attributes**: None specific to `<details>`.
- **Example**:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/ab2ff85f-f053-43cd-a6d9-db35c6394e10/Untitled.png)

### 4. `<figcaption>` Tag

- **Meaning**: Represents a caption or legend for a figure.
- **Attributes**: None specific to `<figcaption>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/bdebd005-23ef-4b9a-af08-afb6bdf30167/Untitled.png)

### 5. `<figure>` Tag

- **Meaning**: Represents self-contained content, such as illustrations, diagrams, photos, code listings, etc.
- **Attributes**: None specific to `<figure>`.
- **Example**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/6602aeb1-bcf7-433a-a8e6-5671d26aa7d7/Untitled.png)

### 6. `<footer>` Tag

- **Meaning**: Represents a footer for its nearest sectioning content or sectioning root element.
- **Attributes**: None specific to `<footer>`.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/61661ff9-9e5d-40da-bffe-67e925d1720d/Untitled.png)

### 7. `<header>` Tag

- **Meaning**: Represents introductory content, typically a group of introductory or navigational aids.
- **Attributes**: None specific to `<header>`.
- **Example**:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/9cf006cf-c222-4114-b80b-d0c559e752c6/Untitled.png)

### 8. `<main>` Tag

- **Meaning**: Represents the dominant content of the <body> of a document.
- **Attributes**: None specific to `<main>`.
- Example:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/3f8b0e91-f861-47e5-be0d-bf83a555f154/Untitled.png)

### 9. `<nav>` Tag

- **Meaning**: Represents a section of a page intended for navigation links.
- **Attributes**: None specific to `<nav>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/1a73ef52-dd81-4ad2-8fb5-2f50b9508140/Untitled.png)

### 10. `<section>` Tag

- **Meaning**: Represents a generic section of a document, used to group together related content.
- **Attributes**: None specific to `<section>`.
- **Example:**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/79cbe1fd-25c8-4d93-9a05-27e66730dc0f/e0ae1da7-d890-4af8-867f-d1bd9c6a8852/Untitled.png)

### 11. `<summary>` Tag

- **Meaning**: Represents a summary, legend, or caption for the `<details>` element.
- **Attributes**: None specific to `<summary>`.
