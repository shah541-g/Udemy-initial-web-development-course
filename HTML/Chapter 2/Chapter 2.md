# Article on HTML Chapter 02: HTML Styling and Structure - Enhancing Web Pages

HTML provides various methods to style and structure web pages effectively. In this guide, we'll explore different techniques such as inline styling, CSS, block and inline elements, div and span elements, classes, IDs, and hyperlinks with examples.

## 1. HTML Style Attribute
The style attribute is used to add inline styles to HTML elements.

```html
<p style="color: red; font-size: 16px;">This is styled text.</p>
```

## 2. HTML with CSS in Three Methods
### External CSS

```html
<link rel="stylesheet" type="text/css" href="styles.css">
```

### Internal CSS

```html
<style>
    p {
        color: red;
        font-size: 16px;
    }
</style>
```

### Inline CSS

```html
<p style="color: red; font-size: 16px;">This is styled text.</p>
```

## 3. HTML Block and Inline Level Element
### Block Level Element
```html
<div>This is a block level element.</div>
```

### Inline Level Element
```html
<span>This is an inline level element.</span>
```

## 4. div and span Elements

### <div> Element
```html
<div>This is a block level element.</div>
```

### <span> Element
```html
<span>This is an inline level element.</span>
```

## 5. HTML Class (Lecture 164)
```html
<p class="highlight">This text is highlighted.</p>

<style>
    .highlight {
        background-color: yellow;
    }
</style>
```

## 6. HTML ID Attributes
```html
<p id="intro">This is the introduction.</p>

<style>
    #intro {
        font-size: 20px;
    }
</style>
```

## 7. Bookmarking with ID and Hyperlinks
### Creating a Bookmark
```html
<a id="section1"></a>
<h2>Section 1</h2>
```

### Linking to the Bookmark
```html
<a href="#section1">Go to Section 1</a>
```

### Example: HTML Styling and Structure
```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Styling and Structure</title>
    <style>
        .highlight {
            background-color: yellow;
        }
        #intro {
            font-size: 20px;
        }
    </style>
</head>
<body>

<p style="color: red; font-size: 16px;">This is styled text.</p>

<link rel="stylesheet" type="text/css" href="styles.css">

<style>
    p {
        color: red;
        font-size: 16px;
    }
</style>


<div>This is a block level element.</div>
<span>This is an inline level element.</span>

<p class="highlight">This text is highlighted.</p>

<p id="intro">This is the introduction.</p>

<a id="section1"></a>
<h2>Section 1</h2>
<a href="#section1">Go to Section 1</a>

</body>
</html>
```

## Conclusion
By using HTML styling attributes, CSS, block and inline elements, div and span elements, classes, IDs, and hyperlinks effectively, you can enhance the appearance and structure of your web pages, making them more visually appealing and user-friendly