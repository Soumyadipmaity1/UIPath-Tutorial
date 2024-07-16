
## Table of Contents

5. [Flexbox](#flexbox)
6. [Grid Layout](#grid-layout)
7. [Responsive Design](#responsive-design)
8. [Positioning](#positioning)
9. [Colors and Backgrounds](#colors-and-backgrounds)

## Flexbox
Flexbox is a layout model that allows you to design a flexible and efficient layout structure without using float or positioning.

### Properties
- **Container**: `display: flex;`
  - `flex-direction`
  - `justify-content`
  - `align-items`
  - `flex-wrap`

- **Items**: 
  - `flex`
  - `align-self`
  - `order`

```css
.container {
  display: flex;
  justify-content: space-between;
}
```

## Grid Layout
CSS Grid Layout is a two-dimensional layout system for the web.

### Properties
- **Container**: `display: grid;`
  - `grid-template-columns`
  - `grid-template-rows`
  - `grid-gap`

- **Items**: 
  - `grid-column`
  - `grid-row`

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 10px;
}
```

## Positioning
The CSS `position` property specifies the type of positioning method used for an element.

### Types
- **Static**: Default position
- **Relative**: Positioned relative to its normal position
- **Absolute**: Positioned relative to the nearest positioned ancestor
- **Fixed**: Positioned relative to the viewport
- **Sticky**: Switches between relative and fixed, depending on scroll position

```css
.element {
  position: absolute;
  top: 50px;
  left: 100px;
}
```

## Colors and Backgrounds
CSS provides various properties to set colors and backgrounds for elements.

### Color Properties
- `color`
- `background-color`
- `opacity`

### Background Properties
- `background-image`
- `background-repeat`
- `background-size`
- `background-position`
- `background-attachment`

```css
.element {
  background-color: #f0f0f0;
  background-image: url('image.jpg');
  background-size: cover;
}
```
## Responsive Design
Responsive design ensures that the web page looks good on all devices.

### Media Queries
```css
@media (max-width: 600px) {
  .container {
    flex-direction: column;
  }
}
```