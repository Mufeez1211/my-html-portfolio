<<<<<<< HEAD
# Personal Portfolio Website – HTML5

A beginner-friendly personal portfolio website built using **HTML5** and **Visual Studio Code**.

This project demonstrates how to create a structured portfolio containing personal information, projects, technical skills, education, and a contact form.

---

## 1. Project Overview

### Features

- Personal introduction and profile image
- About Me section
- Projects showcase
- Technical skills
- Education details in a table
- Contact form
- Quick navigation links
- Footer section

### Technologies Used

- HTML5
- Visual Studio Code
- Web Browser

---

## 2. Project Structure

```text
My-Portfolio/
│
├── index.html
└── README.md
```

- `index.html` – Contains the complete portfolio webpage.
- `README.md` – Explains the project and the HTML concepts used.

---

# 3. Complete HTML Tags Explanation

## A. HTML Document Structure

### 1. `<!DOCTYPE html>`

Declares that the document uses HTML5.

**Purpose:** Helps the browser render the webpage using modern HTML standards.

It is a declaration, not an HTML tag.

### 2. `<html>`

The root element of an HTML document. All other HTML elements are placed inside it.

**Attribute:**
- `lang="en"` – Specifies that the page language is English.

### 3. `<head>`

Contains information about the webpage. Most of this information is not displayed inside the webpage.

### 4. `<meta>`

Provides metadata about the HTML document.

Important attributes used:

- `charset="utf-8"` – Supports a wide range of characters and symbols.
- `name="viewport"` – Identifies viewport settings.
- `content="width=device-width, initial-scale=1"` – Helps the webpage adapt to the device width.
- `name="description"` – Defines a description of the webpage.
- `name="author"` – Identifies the author.

`<meta>` is a void element and does not need a closing tag.

### 5. `<title>`

Defines the webpage title shown in the browser tab.

Example:

```html
<title>Syed Mufeez – AI Engineer Portfolio</title>
```

### 6. `<body>`

Contains the visible webpage content, such as headings, paragraphs, images, links, tables, and forms.

---

## B. Header and Navigation Tags

### 7. `<header>`

Defines the introductory section of a webpage or content section.

In this project, it contains the name, job title, profile image, contact information, and navigation.

### 8. `<h1>` to `<h6>`

Define headings with different levels of importance.

- `<h1>` – Main heading.
- `<h2>` – Major section heading.
- `<h3>` – Subsection heading.
- `<h4>` – Fourth-level heading.
- `<h5>` – Fifth-level heading.
- `<h6>` – Sixth-level heading.

Example:

```html
<h1>Syed Mufeez</h1>
<h2>AI Engineer</h2>
<h3>My Projects</h3>
```

### 9. `<p>`

Defines a paragraph of text.

### 10. `<q>`

Defines a short inline quotation. Browsers generally display quotation marks around the text.

### 11. `<img>`

Displays an image on a webpage.

Important attributes:

- `src` – Specifies the image location.
- `alt` – Provides alternative text if the image cannot load and supports screen readers.
- `width` – Sets image width.
- `height` – Sets image height.

Example:

```html
<img src="profile.jpg" alt="My Profile Picture" width="120" height="120">
```

`<img>` is a void element and does not need a closing tag.

### 12. `<address>`

Represents contact information for the author or owner of a webpage or article.

### 13. `<br>`

Creates a line break.

It is a void element and does not need a closing tag.

### 14. `<a>`

Creates a hyperlink.

Important attribute:

- `href` – Specifies the destination of the link.

Examples:

```html
<a href="https://example.com">Visit Website</a>

<a href="mailto:example@gmail.com">Send Email</a>

<a href="tel:+911234567890">Call Me</a>

<a href="#about">About Me</a>
```

### 15. `<nav>`

Defines a section containing navigation links.

Attribute:

- `aria-label` – Provides an accessible name for the navigation section.

### 16. `<ul>`

Creates an unordered list, usually displayed with bullet points.

### 17. `<li>`

Defines an individual list item inside a list.

Example:

```html
<ul>
    <li>Python</li>
    <li>SQL</li>
    <li>HTML</li>
</ul>
```

---

## C. Text Formatting Tags

### 18. `<strong>`

Indicates that text has strong importance. Browsers usually display it in bold.

### 19. `<em>`

Adds emphasis to text. Browsers usually display it in italics.

### 20. `<mark>`

Highlights text, usually with a coloured background.

### 21. `<abbr>`

Defines an abbreviation or acronym.

Attribute:

- `title` – Provides the full meaning of the abbreviation.

Example:

```html
<abbr title="Artificial Intelligence">AI</abbr>
```

### 22. `<small>`

Displays fine print or supplementary information, usually in smaller text.

### 23. `<time>`

Represents a date or time in a machine-readable format.

Attribute:

- `datetime` – Specifies the machine-readable date or time.

Example:

```html
<time datetime="2026-11-06">6 November 2026</time>
```

### 24. `<b>`

Draws attention to text without adding strong importance. Usually displayed in bold.

### 25. `<i>`

Represents text in an alternate voice or mood, such as a technical term or title. Usually displayed in italics.

---

## D. Semantic and Content Organization Tags

### 26. `<main>`

Contains the main content of the webpage.

A page should normally have one `<main>` element.

### 27. `<section>`

Groups related content into a thematic section.

Example:

```html
<section id="about">
    <h2>About Me</h2>
    <p>Welcome to my portfolio.</p>
</section>
```

Attribute:

- `id` – Gives an element a unique identifier.

### 28. `<article>`

Represents independent, self-contained content, such as a project description or blog post.

### 29. `<aside>`

Contains related or supplementary information that is not part of the main content.

### 30. `<footer>`

Defines the footer of a webpage or section. It often contains copyright information and related links.

### 31. `<hr>`

Creates a thematic break between sections. Browsers usually display it as a horizontal line.

---

## E. Details and Code Display Tags

### 32. `<details>`

Creates an expandable section that users can open and close.

### 33. `<summary>`

Defines the visible heading of a `<details>` element.

Example:

```html
<details>
    <summary>See sample output</summary>
    <p>This is the hidden content.</p>
</details>
```

### 34. `<figure>`

Groups self-contained content, such as an image, diagram, or code example.

### 35. `<figcaption>`

Provides a caption or description for content inside a `<figure>`.

### 36. `<pre>`

Displays preformatted text. It preserves spaces and line breaks.

### 37. `<code>`

Identifies a piece of computer code.

Example:

```html
<pre><code>print("Hello World")</code></pre>
```

---

## F. List Tags

### 38. `<dl>`

Creates a description list containing terms and their descriptions.

### 39. `<dt>`

Defines a term or name in a description list.

### 40. `<dd>`

Provides the description of a term inside a description list.

Example:

```html
<dl>
    <dt>Programming</dt>
    <dd>Python and SQL</dd>
</dl>
```

### 41. `<ol>`

Creates an ordered list, usually numbered.

Example:

```html
<ol>
    <li>Python</li>
    <li>SQL</li>
    <li>HTML</li>
</ol>
```

---

## G. Table Tags

### 42. `<table>`

Creates a table to display data in rows and columns.

### 43. `<caption>`

Provides a title or description for the table.

### 44. `<thead>`

Groups the heading rows of a table.

### 45. `<tbody>`

Groups the main data rows of a table.

### 46. `<tfoot>`

Groups footer rows containing summary or additional information.

### 47. `<tr>`

Defines a table row.

### 48. `<th>`

Defines a header cell in a table.

Attribute:

- `scope="col"` – Identifies the header as applying to a column.

### 49. `<td>`

Defines a standard data cell in a table.

Attribute:

- `colspan="4"` – Makes a cell span across four columns.

Example:

```html
<table border="1" cellpadding="8">
    <caption>Education Details</caption>
    <thead>
        <tr>
            <th scope="col">Year</th>
            <th scope="col">Qualification</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>2021–2025</td>
            <td>B.Tech</td>
        </tr>
    </tbody>
</table>
```

Additional table attributes:

- `border` – Specifies a table border in this example.
- `cellpadding` – Specifies space between cell content and its border.

Note: CSS is the modern recommended way to style table borders and spacing.

---

## H. Progress and Label Tags

### 50. `<meter>`

Displays a scalar measurement within a known range, such as a CGPA out of 10.

Important attributes:

- `min` – Minimum value.
- `max` – Maximum value.
- `value` – Current value.

Example:

```html
<meter min="0" max="10" value="8.11">
    8.11 out of 10
</meter>
```

### 51. `<label>`

Provides a descriptive label for a form control.

Attribute:

- `for` – Connects the label to an element with the matching `id`.

Example:

```html
<label for="name">Name:</label>
<input type="text" id="name">
```

---

## I. Form Tags

### 52. `<form>`

Creates a form to collect information from users.

Important attributes:

- `action` – Specifies where form data should be sent.
- `method` – Specifies the HTTP method used to submit data.
- `enctype` – Specifies how form data is encoded.

In this project, `mailto:` is used to open the user's email application. It is not a replacement for a secure server-side form handler.

### 53. `<fieldset>`

Groups related form controls together.

### 54. `<legend>`

Provides a title for a `<fieldset>`.

### 55. `<input>`

Creates an input field.

Input types used in this project:

- `type="text"` – Accepts ordinary text.
- `type="email"` – Accepts an email address and provides basic email validation.
- `type="tel"` – Accepts a telephone number.
- `type="radio"` – Allows one selection from a group.
- `type="checkbox"` – Allows a user to select or deselect an option.

Important attributes:

- `id` – Gives the input a unique identifier.
- `name` – Identifies the field when form data is submitted.
- `value` – Specifies the field's submitted value.
- `placeholder` – Displays a hint inside an empty field.
- `required` – Makes the field mandatory.
- `checked` – Selects a radio button or checkbox by default.
- `list` – Connects a text input to a `<datalist>`.

### 56. `<datalist>`

Provides predefined suggestions for an input field.

### 57. `<option>`

Defines an individual choice inside a `<select>` or a suggestion inside a `<datalist>`.

### 58. `<select>`

Creates a dropdown list.

### 59. `<textarea>`

Creates a multiline text input field.

Attributes:

- `rows` – Specifies the visible number of text lines.
- `cols` – Specifies the visible width in characters.

### 60. `<button>`

Creates a clickable button.

Button types used:

- `type="submit"` – Submits the form.
- `type="reset"` – Resets form controls to their initial values.

---

## 4. Additional HTML Tags Referenced in Comments

These tags are mentioned in the original file as learning references. They are not used as active elements in the displayed webpage.

| Tag | Explanation |
|---|---|
| `<blockquote>` | Represents a longer quotation. |
| `<cite>` | Identifies the title of a creative work or cited source. |
| `<sub>` | Displays subscript text, such as H₂O. |
| `<sup>` | Displays superscript text, such as 10². |
| `<kbd>` | Represents keyboard input, such as Ctrl. |
| `<del>` | Represents deleted text. |
| `<ins>` | Represents inserted text. |

Other elements mentioned in the original document:

- `<link>` – Connects an external resource, commonly a CSS stylesheet.
- `<script>` – Embeds or references JavaScript code.

They are not included as active elements in this HTML-only project.

---

## 5. Important HTML Entities

HTML entities display special characters.

| Entity | Output | Meaning |
|---|---|---|
| `&copy;` | © | Copyright symbol |
| `&amp;` | & | Ampersand |
| `&lt;` | < | Less-than symbol |
| `&gt;` | > | Greater-than symbol |
| `&quot;` | " | Double quotation mark |

Example:

```html
<p>&copy; 2026 Syed Mufeez</p>
```

---

## 6. Important HTML Attributes Summary

| Attribute | Purpose |
|---|---|
| `id` | Uniquely identifies an element |
| `class` | Groups elements for CSS or JavaScript |
| `href` | Specifies a link destination |
| `src` | Specifies an image or resource location |
| `alt` | Provides alternative image text |
| `width` | Sets width |
| `height` | Sets height |
| `title` | Provides additional descriptive information |
| `name` | Identifies form data |
| `value` | Specifies a value |
| `type` | Defines an input or button type |
| `for` | Connects a label to a form control |
| `required` | Makes a form field mandatory |
| `placeholder` | Displays an input hint |
| `target` | Specifies where to open a linked document |
| `rel` | Describes the relationship to the linked resource |
| `datetime` | Provides a machine-readable date or time |
| `colspan` | Makes a table cell span multiple columns |
| `rowspan` | Makes a table cell span multiple rows |
| `aria-label` | Provides an accessible name |
| `min` | Defines the minimum value |
| `max` | Defines the maximum value |
| `checked` | Sets a radio button or checkbox as selected |
| `rows` | Sets the visible number of textarea rows |
| `cols` | Sets the visible width of a textarea |
| `action` | Specifies the form submission destination |
| `method` | Specifies the form submission method |
| `enctype` | Specifies form-data encoding |

---

## 7. How to Run the Project

1. Open Visual Studio Code.
2. Open the project folder.
3. Open `index.html`.
4. Right-click and choose **Open with Live Server**, if installed.
5. Otherwise, open `index.html` directly in your web browser.

---

## 8. Learning Outcomes

After completing this project, I practised:

- HTML5 document structure
- Semantic HTML
- Headings and paragraphs
- Text formatting
- Images and hyperlinks
- Ordered and unordered lists
- Description lists
- Tables
- Forms and input controls
- HTML entities
- Accessibility-related attributes
- Organizing webpage content

---

## 9. Author

**Syed Mufeez**

B.Tech – Computer Science (Artificial Intelligence and Data Science)

## 10. License

This project is created for educational and learning purposes.
=======
# my-html-portfolio
>>>>>>> 338a2272f2af823ebb6e52306decd7a88f611bf6
