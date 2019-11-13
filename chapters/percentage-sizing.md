# Percentage Sizing

Percentage sizing should be the base of any responsive design. Start here, and use other techniques when you discover something you can't achieve with percentages.

Open this link then follow the instructions:



## Viewport Meta Tag

Add this tag so that the browser will use your responsive styling. Without this, a mobile browser will used a zoomed-out version of your desktop site.

```
<meta name="viewport" content="width=device-width,initial-scale=1">
```

Your site should now be zoomed in mobile view.

## Percentage Widths

Instead of using pixel sizing, use percentage sizing wherever possible. Percentage sizing can be used for layout elements. It can not be used for text.

```
.container {
  width: 100%;
}
```

Your main content box should resize with the browser.

## Use max-width to limit size

Combining a pixel max-width and a percentage width
gives you full-width on mobile and limited width on desktop.

```
.container {
  width: 100%;
  max-width: 800px;
  margin: 0 auto;
}
```

Your main content size should be limited on large screens.

## Use "cover" with background images

Using this setting will allow your background image to re-flow to fit any container size. Make sure to consider how the image could be cropped when choosing the image.

```
.header {
  background-image: url("https://cdn.glitch.com/0e9aefe5-f7e5-4bd0-8d41-68a0f1e2510c%2Fheader-background.jpg?v=1573535558245");
  background-size: cover;
  background-position: center center;
}
```

Your background image should resize to always fill the header.

## Completed Challenge

[https://glitch.com/edit/#!/sulky-cell](https://glitch.com/edit/#!/sulky-cell)