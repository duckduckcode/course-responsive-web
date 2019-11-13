# Grid Layout

Open this link and follow the instructions:

[https://glitch.com/edit/#!/olive-silene](https://glitch.com/edit/#!/olive-silene)

## Apply grid layout rules

```
.grid-container {
  display: grid;
}
```

## Split into two columns

```
.grid-container {
  ...
  grid-template-columns: 200px auto;
}
```

## Make the header span two columns

```
.header {
  grid-column-start: 1;
  grid-column-end: span 2;
}
```

## Make the grid take up the whole page

```
body {
  ...
  margin: 0;
}

.grid-container {
  ...
  height: 100vh;
}
```

## Set the height of the header row

```
.grid-container {
  ...
  grid-template-rows: 100px auto;
}
```

## Add a scrollable content area

```
<div class="content">
  <div class="scroll-area">
    Content
  </div>
</div>
```


Copy text from catipsum.com and replace the word Content

## Size scroll area to fit the grid cell

```
.content {
  ...
  position: relative;
}

.scroll-area {
  height: 100%;
  overflow: auto;
  
  /* size this box relative to its parent */
  position: absolute;
}

```


## Completed Task

[https://glitch.com/edit/#!/prong-silene](https://glitch.com/edit/#!/prong-silene)


## Challenge

Have a go at [CSS Grid Garden](https://cssgridgarden.com)
