# UIPath Student Community Web dev Course



10. [Transitions and Animations](#transitions-and-animations)
11. [Advanced Concepts](#advanced-concepts)





## Transitions and Animations
CSS transitions and animations allow you to create dynamic effects.

### Transitions
```css
.element {
  transition: background-color 0.5s ease;
}
.element:hover {
  background-color: #ff0000;
}
```

### Animations
```css
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

.element {
  animation: example 5s infinite;
}
```

## Advanced Concepts
### CSS Variables
```css
:root {
  --main-color: #3498db;
}
.element {
  color: var(--main-color);
}
```

### CSS Preprocessors
- **Sass**
- **Less**
- **Stylus**

### BEM Methodology
Block Element Modifier (BEM) is a methodology that helps you to create reusable components and code sharing in front-end development.

```css
.block__element--modifier {
  /* styles */
}
```
