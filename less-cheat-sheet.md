### usage
```
lessc [options] <input> [<output>]

// eg:
lessc style.less style.css

lessc --source-map-inline	{ sourceMap: { sourceMapFileInline: true } }

```

```demos

// logic

@some: foo;

div {
    margin: if((2 > 1), 0, 3px);
    color:  if((iscolor(@some)), @some, black);
}

=> 
div {
    margin: 0;
    color:  black;
}


```
