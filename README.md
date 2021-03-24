# ✒️ My CSS Notes, Codes, Resources.

### https://flexboxfroggy.com/

-   `flex-start`: Items align to the left side of the container.
-   `flex-end`: Items align to the right side of the container.
-   `center`: Items align at the center of the container.
-   `space-between`: Items display with equal spacing between them.
-   `space-around`: Items display with equal spacing around them.

- `justify-content: center;` : Centralize items in the center
	
-   `stretch`: Items are stretched to fit the container.

- `align-items: flex-end;`: Align items bottom

- `justify-content: center;`
`align-items: center;`: Align item horizontally and vertically
-   `row`: Items are placed the same as the text direction.
-   `row-reverse`: Items are placed opposite to the text direction.
-   `column`: Items are placed top to bottom.
-   `column-reverse`: Items are placed bottom to top.
- `flex-direction`: This CSS property defines the direction items are placed in the container
- `order` : Reorder property
- `align-self`. This property accepts the same values as `align-items` and its value for the specific item.
- `flex-wrap`:
	-   `nowrap`: Every item is fit to a single line.
	-   `wrap`: Items wrap around to additional lines.
	-   `wrap-reverse`: Items wrap around to additional lines in reverse.

- `flex-flow`:
	- `flex-direction`
	- `flex-wrap`

- `align-content`:
	-   `flex-start`: Lines are packed at the top of the container.
	-   `flex-end`: Lines are packed at the bottom of the container.
	-   `center`: Lines are packed at the vertical center of the container.
	-   `space-between`: Lines display with equal spacing between them.
	-   `space-around`: Lines display with equal spacing around them.
	-   `stretch`: Lines are stretched to fit the container.

### https://www.w3schools.com/css/
`font-family: verdana`: Change the text font.
`font-size: 20px`: Change the text-size.
`color: white`: Change the main color (front).
`text-align: center`: Change the text position.
`background-color: lightblue`: Change the background color.

### CSS Syntax:

<div align="center">
	<img src="https://www.w3schools.com/css/selector.gif" />
</div>

### The CSS `id` Selector
```css
#para1 { 
	text-align: center;  
  	color: red;
}
  ```
  
 ### The CSS `class` Selector
 ```css
 .center {
  text-align: center;
  color: red;
}
```

### Unique `elements` with specific `class` Selection
```css
// p elements with center class

p.center {
  text-align: center;
  color: red;
}
```

### More than one `class` append to an element 
```html
<p class="center large">This paragraph refers to two classes.</p>
```

 ### The CSS `universal/all` Selector
 ```css
 * {
  text-align: center;
  color: blue;
}
```

### The CSS `grouping` Selector

BAD {
```css
h1 { text-align: center;  
  color: red;
}  
  
h2 { text-align: center;  
  color: red;
}  
  
p { text-align: center;  
  color: red;
}
```
}

GOOD {
```css
h1, h2, p { 
	text-align: center;  
    color: red
}
  ```
}

### Importing CSS
External
```html
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
Internal
```html
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
} 
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

Inline
```html
<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>
```

Cascading Order
```
1.  Inline style (inside an HTML element)
2.  External and internal style sheets (in the head section)
3.  Browser default
```
