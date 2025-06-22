# Article on CSS Chapter 01

## Mastering CSS Basics

CSS (Cascading Style Sheets) is a fundamental technology used to style the visual presentation of web pages. In this guide, we'll explore the basics of CSS, including simple selectors, styling methods, attribute selectors, combinators, and more.

### 1. CSS Introduction
CSS is used to control the style and layout of multiple web pages all at once. It allows developers to control the appearance of HTML elements on a web page.

### Example:
```css
/* CSS example */
body {
    background-color: lightblue;
}
```

### 2. CSS Simple Selectors
Simple selectors are basic CSS selectors that select elements based on their name, id, class, or attribute.

### Example:
```css
/* CSS for simple selectors */
p {
    color: red;
}
```

### 3. CSS in HTML with Different Methods
CSS can be included in HTML documents using various methods such as inline, internal, and external styles.

### Example:
```css
<!-- Inline CSS -->
<p style="color:blue;">This is a paragraph.</p>
 
<!-- Internal CSS -->
<style>
    p {
        color: red;
    }
</style>
 
<!-- External CSS -->
<link rel="stylesheet" type="text/css" href="styles.css">
```

### 4. CSS Attributes Selectors
Attribute selectors allow you to select elements based on the presence or value of their attributes.

### Example:
```css
/* CSS for attribute selectors */
input[type="text"] {
    background-color: lightblue;
}
```

### 5. CSS Combinators
Combinators are used to combine multiple selectors into more complex ones.

### Example:
```css
/* CSS with combinators */
div p {
    color: blue;
}
```

### 6. important Keyword in CSS
The important keyword is used to give a CSS property more weight than it would normally have.

### Example:
```css
/* CSS with important keyword */
p {
    color: red !important;
}
```

### 7. CSS Comments
CSS comments allow developers to add comments to their code for documentation or debugging purposes.

### Example:
```css
/* CSS comment */
p {
    /* This is a comment */
    color: blue;
}
```

### 8. CSS Colors
CSS provides various ways to specify colors using color names, hexadecimal, RGB, RGBA, HSL, and HSLA values.

### Example:
```css
/* CSS for colors */
p {
    color: #ff0000; /* Red */
}
```

### 9. CSS Background
CSS background property is used to set the background of an HTML element.

### Example:
```css
/* CSS for background */
body {
    background-image: url('background.jpg');
}
```

### Conclusion

Mastering the basics of CSS is essential for web development. By understanding simple selectors, styling methods, attribute selectors, combinators, and other CSS concepts, you can effectively style and layout your web pages