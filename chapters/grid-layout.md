# Grid Layout

This layout uses 1 column on mobile, 3 on medium screens and 5 on large screens.



## Mobile First

```html
<ul>
  <li>1</li>
  <li>2</li>
  <li>3</li>
  <li>4</li>
  <li>5</li>
  <li>6</li>
  <li>7</li>
  <li>8</li>
  <li>9</li>
</ul>
```

```css
/* mobile-first */
ul {
  list-style: none;
  padding: 0;
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: auto;
}

/* individual items */
li {
  box-sizing: border-box;
  border: 2px solid red;
  padding: 10px;
}
```

## Medium Screens

Use 3 columns when the screen is wider than 800px.

```css
/* medium screens */
@media(min-width: 800px) {
  ul {
    grid-template-columns: 1fr 1fr 1fr;
  }
}
```

## Large Screens

Use 5 columns when the screen is wider than 1000px.

```css
/* large screens */
@media(min-width: 1000px) {
  ul {
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
  }
}
```

## Row and Column Gaps

```
/* mobile-first */
ul {
  ...
  grid-row-gap: 10px;
  grid-column-gap: 10px;
}
```

## Completed Task

Here is the completed version of the above:

[https://glitch.com/edit/#!/puzzling-sunshine](https://glitch.com/edit/#!/puzzling-sunshine)

## Challenge

Have a go at [CSS Grid Garden](https://cssgridgarden.com)