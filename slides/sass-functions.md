##  SASS Functions

_Functions are usefull_

```
@function calc-percent($target, $container) {
    @return ($target / $container) * 100%;
}
```

_Defining Functions keep your code dry and readable_

```
$container = 12;

.col-1 {
    width: calc-percent(1, $container);
}

```
