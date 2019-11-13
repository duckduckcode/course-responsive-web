# Media Query Grid

This layout uses 1 column on mobile, 3 on medium screens and 5 on large screens.

Open the link below and follow the instructions:

[https://glitch.com/edit/#!/puzzle-plutonium](https://glitch.com/edit/#!/puzzle-plutonium)

## Apply grid layout system to the list

```
ul {
  ...
  display: grid;
}
```

## Use two columns

```
ul {
  ...
  grid-template-columns: 1fr 1fr;
}
```

As you resize it will always use two columns.

## Use 4 columns for medium screens

```
@media(min-width: 800px) {
  ul {
    grid-template-columns: 1fr 1fr 1fr 1fr;
  }
}
```

## Use 6 columns on large screens

```
@media(min-width: 1000px) {
  ul {
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
  }
}
```

## Add some row gaps and column gaps

```
ul {
  ...
  grid-row-gap: 10px;
  grid-column-gap: 10px;
}
```

## Completed Task

Here is the completed version of the above:

[https://glitch.com/edit/#!/puzzling-sunshine](https://glitch.com/edit/#!/puzzling-sunshine)
