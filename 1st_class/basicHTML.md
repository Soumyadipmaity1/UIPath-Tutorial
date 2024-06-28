
# HTML Class 1 

## Syllabus

### Introduction to HTML
- **Overview of HTML**: Understand what HTML is and its role in web development.
- **Basic Structure of a Web Page**: Learn the basic structure of an HTML document including `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` tags.
- **Common HTML Tags**: Explore basic HTML tags like `<p>`, `<a>`, `<img>`, `<div>`, `<span>`, `<h1>` to `<h6>`, etc.

### HTML Elements and Attributes
- **HTML Elements**: Learn about block-level and inline elements.
- **HTML Attributes**: Understand how to use attributes to provide additional information about elements.
- **HTML Formatting**: Learn how to use HTML tags for text formatting like `<b>`, `<i>`, `<u>`, `<strong>`, `<em>`, etc.

### HTML Links, Lists, and Tables
- **HTML Links**: Learn how to create hyperlinks using the `<a>` tag.
- **HTML Lists**: Understand ordered lists `<ol>`, unordered lists `<ul>`, and list items `<li>`.
- **HTML Tables**: Learn to create tables using `<table>`, `<tr>`, `<th>`, `<td>`, `<thead>`, `<tbody>`, and `<tfoot>` tags.

### HTML Forms
- **Forms and Input Elements**: Learn how to create forms with various input elements like `<input>`, `<textarea>`, `<button>`, `<select>`, and `<option>`.
- **Form Attributes**: Understand form attributes such as `action`, `method`, `name`, `value`, etc.
- **Form Validation**: Learn basic form validation using HTML5 attributes like `required`, `min`, `max`, `pattern`, etc.

## HTML Notes

### 1. Introduction to HTML
HTML (HyperText Markup Language) is the standard language for creating web pages and web applications. It describes the structure of a web page using markup. HTML elements are represented by tags, which are used to create the content and structure of a web page.

### 2. Basic Structure of a Web Page
```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```
- `<!DOCTYPE html>`: Declares the document type.
- `<html>`: The root element of an HTML page.
- `<head>`: Contains meta-information about the HTML document.
- `<body>`: Contains the content of the HTML document.

### 3. Common HTML Tags
- **Headings**: `<h1>` to `<h6>`
- **Paragraph**: `<p>`
- **Links**: `<a href="url">Link text</a>`
- **Images**: `<img src="url" alt="description">`
- **Divisions**: `<div>`
- **Spans**: `<span>`

### 4. HTML Elements and Attributes
HTML elements can have attributes that provide additional information about the elements. Attributes are always included in the opening tag and usually come in name/value pairs.
```html
<a href="https://www.example.com" target="_blank">Visit Example</a>
```
- `href`: Specifies the URL of the page the link goes to.
- `target`: Specifies where to open the linked document.

---
### 5. HTML Formatting Tags

### Headings

Headings in HTML are used to define the hierarchy and structure of the content. There are six levels of headings, `<h1>` to `<h6>`, with `<h1>` being the highest level (most important) and `<h6>` the lowest.

Example usage:
```html
<h1>This is Heading 1</h1>
<h2>This is Heading 2</h2>
<h3>This is Heading 3</h3>
```

---

### Paragraphs

The `<p>` tag is used to define paragraphs of text. It is a block-level element that automatically creates space before and after the paragraph.

Example usage:
```html
<p>This is a paragraph of text.</p>
<p>This is another paragraph.</p>
```
---
### Bold

- `<strong>` or `<b>` tags are used to make text bold.

  ```html
  <p>This is <strong>bold</strong> text.</p>
  ```

### Italic
- `<em>` or `<i>` tags are used to italicize text.
  ```html
  <p>This is <em>italic</em> text.</p>
  ```

### Underline
- `<u>` tag is used to underline text.
  ```html
  <p>This is <u>underlined</u> text.</p>
  ```

### Strikethrough
- `<s>` or `<del>` tags are used to strike through text.
  ```html
  <p>This is <s>strikethrough</s> text.</p>
  ```

### Blockquote
- `<blockquote>` is used for longer quotations that should be set apart from the main text.
  ```html
  <blockquote>
    This is a longer quotation that is set apart from the main text.
  </blockquote>
  ```

### Inline Quote
- `<q>` tag is used for shorter, inline quotations.
  ```html
  <p>This is an inline quote: <q>This is the quote.</q></p>
  ```

---


### 6. HTML Links, Lists, and Tables
- **Links**: `<a href="url">Link text</a>`
- **Ordered List**:
```html
<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>
```
- **Unordered List**:
```html
<ul>
    <li>First item</li>
    <li>Second item</li>
</ul>
```
- **Tables**:
```html
<table>
    <tr>
        <th>Header</th>
        <th>Header</th>
    </tr>
    <tr>
        <td>Data</td>
        <td>Data</td>
    </tr>
</table>
```



### 7. HTML Forms

HTML forms are essential for collecting user input on web pages. They are created using the `<form>` tag and include various input elements for different types of data.


### Form Structure

Forms in HTML follow a structured format using the `<form>` tag. Here's a basic example:

```html
<form action="/submit-form" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" cols="50"></textarea>

    <input type="submit" value="Submit">
</form>
```

### Explanation

- **`<form>`**: Defines the start of the form.
- **`action`**: Specifies where to send the form data when submitted (`/submit-form` in this example).
- **`method`**: Specifies the HTTP method (`GET` or `POST`) for submitting the form.
- **Inputs**: Various input elements (`<input>`, `<textarea>`) collect user data (`name`, `email`, `message` in this example).
- **`<input type="submit">`**: Creates a submit button to send the form data.

---

### Form Elements

HTML provides several form elements to collect different types of data:

- **Text Input**: `<input type="text">` - Used for single-line text input.
- **Email Input**: `<input type="email">` - Specifically for email addresses.
- **Password Input**: `<input type="password">` - Masks input for passwords.
- **Textarea**: `<textarea></textarea>` - Allows multi-line text input.
- **Checkbox**: `<input type="checkbox">` - Allows selection of multiple options.
- **Radio Buttons**: `<input type="radio">` - Allows selection of a single option from multiple choices.
- **Dropdown Menu**: `<select><option>...</option></select>` - Creates a dropdown list of options.

---

### Form Attributes

Form elements can have various attributes to specify behavior and validation:

- **`required`**: Makes an input field mandatory before submitting the form.
- **`placeholder`**: Provides a hint or example of expected input.
- **`maxlength`**: Limits the number of characters for text inputs.
- **`disabled`**: Disables user interaction with the input element.

---

## Different Form Style

### Textarea
```html
<textarea id="message" name="message" rows="4" cols="50"></textarea>
```
- `<textarea>`: Creates a multi-line text input field.
- `id`: Specifies a unique identifier for the textarea.
- `name`: Defines the name of the textarea, used when submitting the form data.
- `rows`: Specifies the visible number of lines in the textarea.
- `cols`: Specifies the visible number of characters per line in the textarea.

### Checkbox
```html
<input type="checkbox" id="checkbox1" name="checkbox1" value="value1">
<label for="checkbox1">Checkbox Option 1</label><br>
<input type="checkbox" id="checkbox2" name="checkbox2" value="value2">
<label for="checkbox2">Checkbox Option 2</label><br>
<input type="checkbox" id="checkbox3" name="checkbox3" value="value3" checked>
<label for="checkbox3">Checkbox Option 3 (Checked by default)</label>
```
- `<input type="checkbox">`: Creates a checkbox input.
- `id`: Unique identifier for the checkbox.
- `name`: Name of the checkbox, used when submitting form data.
- `value`: Value associated with the checkbox when checked.
- `checked`: Specifies whether the checkbox is initially checked.

### Radio Buttons
```html
<input type="radio" id="radio1" name="radioGroup" value="option1">
<label for="radio1">Option 1</label><br>
<input type="radio" id="radio2" name="radioGroup" value="option2">
<label for="radio2">Option 2</label><br>
<input type="radio" id="radio3" name="radioGroup" value="option3" checked>
<label for="radio3">Option 3 (Selected by default)</label>
```
- `<input type="radio">`: Creates a radio button input.
- `id`: Unique identifier for the radio button.
- `name`: Name of the radio button group, used to group related buttons.
- `value`: Value associated with the radio button when selected.
- `checked`: Specifies whether the radio button is initially selected.

### Dropdown Menu
```html
<select id="dropdown" name="dropdown">
    <option value="option1">Option 1</option>
    <option value="option2">Option 2</option>
    <option value="option3" selected>Option 3 (Selected by default)</option>
</select>
```
- `<select>`: Creates a dropdown menu.
- `id`: Unique identifier for the dropdown menu.
- `name`: Name of the dropdown menu, used when submitting form data.
- `<option>`: Defines an option within the dropdown menu.
- `value`: Value associated with the option.
- `selected`: Specifies whether the option is initially selected.


---




# Contact

 For any assistance or queries, feel free to contact me at [22053029@kiit.ac.in](mailto:22053029@kiit.ac.in). Happy coding!

--- 