# HTML Tables

Tables are used to display data in rows and columns.
HTML tables are created using the `<table>` tag.

## Basic Structure
```html
<table>
    <tr>
        <th>Heading</th>
    </tr>

    <tr>
        <td>Data</td>
    </tr>
</table>
```
## Table Tags

* `<table>`-> Creates a table 
*  `<tr>`-> Table row 
* `<th>`->Table heading 
* `<td>`->Table data 

## Creating a Simple Table

```html
<table border="1">

    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>Yasha</td>
        <td>19</td>
    </tr>

</table>
```

## `<table>` Tag
Defines the table.

Example:
```html
<table>
</table>
```
## `<tr>` Tag
Defines a row.

Example:
```html
<tr>
</tr>
```
## `<th>` Tag
Defines a heading cell.

Example:
```html
<th>Name</th>
```

* Headings appear bold by default.
## `<td>` Tag
Defines a data cell.

Example:
```html
<td>Yasha</td>
```
## Border Attribute
Adds borders to the table.

```html
<table border="1">
```
## Table Caption
Adds a title to the table.

```html
<table border="1">

    <caption>
        Student Details
    </caption>

</table>
```
## Colspan
Merges columns.

```html
<td colspan="2">
    Student Details
</td>
```
## Rowspan
Merges rows.

```html
<td rowspan="2">
    AIML
</td>
```
## Example with Caption

```html
<table border="1">

    <caption>
        Student Information
    </caption>

    <tr>
        <th>Name</th>
        <th>Course</th>
    </tr>

    <tr>
        <td>Yasha</td>
        <td>AIML</td>
    </tr>

</table>
```
## Summary Table

* `<table>` -> Creates table 
* `<tr>` -> Row 
* `<th>` -> Heading 
* `<td>` -> Data 
*  `<caption>` -> Table title 
*  `rowspan` -> Merge rows 
*  `colspan` -> Merge columns 

