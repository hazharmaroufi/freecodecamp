smooth scrol
```
* {
  scroll-behavior :smooth;
}
```


submit botton 
```
input[type="submit"]{}
```

fix on top:
```
position:fixed;
top:0;
```



The :not pseudo-selector can be used to select all elements that do not match the given CSS rule.
```
div:not(#example) {
  color: red;
}

```

In this example, img elements will have a minimum width of 250px. And as the viewport grows, the image will grow accordingly to be 25 percent of the viewport width.
```
img {
  width: max(250px, 25vw);
}
```


content before something
```
p::before{
  content:"content before p";
}
```
