#  Best Practice

## Every time add, never reset

_if you need to reset some styles this mean that you have been to custom at the base definition_
<hr>

This is good:<br>
```
.blockquote {
    background: #fff;
}

.header .blockquote{
    border-radius: 10px;
}
```
<br><br>
This is Bad:<br>
```
.blockquote {
    background: #fff;
    border-radius: 10px;
}

.header .blockquote{
    border-radius: 0;
}
```
