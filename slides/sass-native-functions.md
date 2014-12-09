##  SASS Native Functions

_SASS have a lot of pre-defined functions_

_[Read More Here](http://sass-lang.com/documentation/Sass/Script/Functions.html)_

<hr>

_One for all_

```
$container = 12;
@for $i from 1 through $container {
    .col-#{$i} {
        width: calc-percent(1, $container); //from before
    }
}

//result
.col-1{width: 8.3%}
.col-2{width: 16.6%}
...
.col-12{width: 100%}
```

_Another One (just because i like this one - Compass)_

```
$color: #ff0;
#{enumerate("h",1,5,"")}{
    color: $color;
}

//result
h1, h2, h3, h4, h5{
    color: #ff0;
}
```