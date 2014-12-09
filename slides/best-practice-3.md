#  Best Practice

## Write Less

_try to use the css3 pseudo-selector, this allow to write a shorter and more readable code_
<hr>

This is good:<br>
```
ul > li {
    background: #fff;
}

ul > li:not(:last-child){
    border-bottom: 1px solid #000;
}
```
<br><br>
This is Bad:<br>
```
ul > li {
    background: #fff;
    border-bottom: 1px solid #000;
}

ul > li:last-child{
    border-bottom: none;
}
```
