# Article on CSS Chapter 05
## Understanding CSS Specificity

CSS specificity determines which CSS rule is applied to an element when multiple rules conflict. In this guide, we'll explore CSS specificity and how it works with examples.

### CSS Specificity
CSS specificity is the mechanism by which browsers decide which CSS property values are the most relevant to an element and, therefore, will be applied. Specificity is based on the selector types and the number of occurrences of each type.

### Example:
```css
/* CSS rules with different specificity */
#id-selector {
    color: red; /* Specificity: ID selector (1 point) */
}
 
.container .class-selector {
    color: blue; /* Specificity: Class selector (1 point) + Element selector (1 point) */
}
 
h1 {
    color: green; /* Specificity: Element selector (1 point) */
}
 
/* The text color will be red because the ID selector has the highest specificity */
```

## Understanding Specificity Calculation
1- ID selectors have a specificity of 100 (1 ID selector = 100 points). <br/>
2- Class selectors, attribute selectors, and pseudo-classes have a specificity of 10 (1 class selector = 10 points).<br/>
3- Element selectors and pseudo-elements have a specificity of 1.<br/>

## Specificity Hierarchy
1- Inline styles (highest specificity)<br/>
2- ID selectors<br/>
3- Class selectors, attribute selectors, and pseudo-classes<br/>
4- Element selectors and pseudo-elements (lowest specificity)<br/>

## Conclusion
Understanding CSS specificity is crucial for writing efficient and maintainable CSS code. By understanding how specificity works, you can ensure that your styles are applied correctly and avoid unexpected behavior caused by conflicting CSS rules.