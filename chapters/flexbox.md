# FlexBox Layout

## Navigation Bar

```
.main-nav {
  display: flex;
  flex-direction: row;
}

.main-nav a {
  width: 200px;
}

.main-nav .title {
  flex: 1;
}
```

Your title should be on the left, and links on the right.

## Content Panels

```
.panels-container {
  display: flex;
  flex-direction: row;
}

.panel {
  flex: 1;
}
```

Your panels should now be horizontal and equally sized.

