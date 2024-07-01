
# CSS Full Notes

## Some Important point about CSS

- Keep CSS DRY (Don't Repeat Yourself).
- Use meaningful class names.
- Organize your CSS with comments.
- Use a CSS preprocessor for better structure and maintainability.
- Optimize for performance by minimizing CSS file size and using efficient selectors.


## Table of Contents

1. [Introduction to CSS](#introduction-to-css)
2. [Selectors](#selectors)
3. [Box Model](#box-model)
4. [Typography](#typography)


## Introduction to CSS
CSS (Cascading Style Sheets) is a stylesheet language used for describing the presentation of a document written in HTML or XML. CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.

### Basic Syntax
```css
selector {
  property: value;
}
```

## Selectors
Selectors are used to target HTML elements for styling.

### Basic Selectors
- **Element Selector**: `p { ... }`
- **ID Selector**: `#id { ... }`
- **Class Selector**: `.class { ... }`

### Attribute Selectors
- `[attribute]`
- `[attribute=value]`
- `[attribute~=value]`
- `[attribute|=value]`

### Pseudo-classes and Pseudo-elements
- `:hover`
- `:focus`
- `:nth-child()`
- `::before`
- `::after`

## Box Model
The box model describes how the elements are structured and how they are affected by margin, border, padding, and content.

### Components
- **Content**: The actual content of the box.
- **Padding**: Clears an area around the content.
- **Border**: A border surrounding the padding (if any) and content.
- **Margin**: Clears an area outside the border.

```css
.box {
  margin: 20px;
  border: 10px solid black;
  padding: 20px;
  width: 200px;
}
```



### Units
- Relative units: `%`, `em`, `rem`, `vw`, `vh`
- Absolute units: `px`, `pt`, `cm`, `mm`

## Typography
Typography is the art and technique of arranging type.

### Properties
- `font-family`
- `font-size`
- `font-weight`
- `line-height`
- `text-align`
- `color`

```css
.text {
  font-family: 'Arial, sans-serif';
  font-size: 16px;
  font-weight: bold;
  line-height: 1.5;
  text-align: center;
  color: #333;
}
```

