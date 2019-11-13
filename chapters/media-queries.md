# Media Queries

Media queries can apply CSS based on screen size.
They can not modify HTML.

## Background Styling

On all screens smaller than 800 pixels,
use a larger image for higher quality.

```
@media (min-width: 800px) {
  .header {
    background: url(images/header-background-large.jpg);
  }
}
```

On large screens, your header should now use the alternative image.

## Menu Layout Direction

On all screens smaller than 800 pixels,
make the main menu use a column layout.

```
@media (max-width: 800px) {
  .main-menu {
    flex-direction: column;
  }
}
```

On small screens, the main menu should be stacked.

## Column Stacking

```
/* default, 801px to 1999px: 3 columns */
.list-item {
  width:
}

/* screens smaller than 800px: 1 column */
@media (max-width: 800px) {
  .list-item {
    width: 100%;
  }
}

/* screens larger than 2000px: 5 columns */
@media (min-width: 2000px) {
  .list-item {

  }
}

```



## Hidden Content

## Body Text

Using vw and vh for sizing body text doesn't work so well, because it can end up getting too big or too small. It's better to choose a "normal" size and a "small" size.

The default font size for most browsers is 16px. All font sizes you use should be relative to the default font size, and then you should change the default font size to be smaller or larger as needed.

```
html {
  font-size: 10px;
}

h2 {
  font-size: 2.4rem; // 24px
}

p {
  font-size: 1.6rem; // 16px;
}
```

