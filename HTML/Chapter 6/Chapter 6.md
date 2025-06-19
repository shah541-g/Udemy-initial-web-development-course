# Article on HTML Chapter 06
## HTML Tables: Structuring Data in Web Pages

HTML tables are a powerful tool for structuring and presenting tabular data on web pages. In this guide, we'll explore how to create and style HTML tables effectively.

## Introduction to HTML Tables
HTML tables are defined using the <table> element. They consist of rows (<tr>) and columns (<td> for data cells and <th> for header cells).
```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
    <tr>
        <td>Data 4</td>
        <td>Data 5</td>
        <td>Data 6</td>
    </tr>
</table>
```
## Basic HTML Table Structure
&lt;table&gt;: Defines the beginning of the table.

&lt;tr&gt;: Defines a row in the table.

&lt;th&gt;: Defines a header cell in the table.

&lt;td&gt;: Defines a data cell in the table.

## Example: Creating a Simple HTML Table
```html
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Country</th>
    </tr>
    <tr>
        <td>John</td>
        <td>25</td>
        <td>USA</td>
    </tr>
    <tr>
        <td>Amy</td>
        <td>30</td>
        <td>UK</td>
    </tr>
</table>
```
## Styling HTML Tables with CSS
You can use CSS to style HTML tables and make them visually appealing:
```css
table {
    width: 100%;
    border-collapse: collapse;
}
 
th, td {
    padding: 8px;
    text-align: left;
    border-bottom: 1px solid #ddd;
}
 
th {
    background-color: #f2f2f2;
}
```

## Example: Styled HTML Table
```html
<!DOCTYPE html>
<html>
<head>
    <title>Styled HTML Table</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            padding: 8px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
 
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Country</th>
    </tr>
    <tr>
        <td>John</td>
        <td>25</td>
        <td>USA</td>
    </tr>
    <tr>
        <td>Amy</td>
        <td>30</td>
        <td>UK</td>
    </tr>
</table>
 
</body>
</html>
```

## Conclusion
HTML tables are a powerful tool for structuring and presenting tabular data on web pages. By using proper HTML markup and CSS styling, you can create visually appealing and accessible tables for your website