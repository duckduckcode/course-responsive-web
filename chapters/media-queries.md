# Media Queries

Media queries can apply CSS based on screen size.
They can not modify HTML.

Click the link then follow along:

[https://glitch.com/edit/#!/lyrical-sturgeon](https://glitch.com/edit/#!/lyrical-sturgeon)

## Screens wider than a certain measure

```
@media only screen and (min-width: 500px) {
  .bigger-than-500 {
    border-color: green;
  }
}
```

## Screens narrower than a certain measure

```
@media only screen and (max-width: 500px) {
  .smaller-than-500 {
    border-color: green;
  }
}
```

## Screens between two sizes

```
@media only screen and (min-width: 500px) and (max-width: 800px) {
  .between-500-and-800 {
    border-color: green;
  }
}
```

## Horizontal aspect ratio

```
@media only screen and (min-aspect-ratio: 1/1) {
  .aspect-ratio-horizontal {
    border-color: green;
  }
}
```

## Vertical Aspect Ratio

```
@media only screen and (max-aspect-ratio: 1/1) {
  .aspect-ratio-vertical {
    border-color: green;
  }
}
```

## Completed Activity

[https://glitch.com/edit/#!/frosted-ankylosaurus](https://glitch.com/edit/#!/frosted-ankylosaurus)


