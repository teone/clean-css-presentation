#  Best Practice

## Get Dirty

#### (at least try to)

_if you are using a SASS framework try to customize his behavior instead override it_
<hr>

**This examples are base on Bootstrap's** _(of course SASS)_

Change this is good:<br>
```
// file: bootstrap/_variables.scss

$brand-primary:         #AC216F !default;
$brand-success:         #5cb85c !default;
$brand-warning:         #f0ad4e !default;
$brand-danger:          #d9534f !default;
$brand-info:            #5bc0de !default;

```
<br><br>
Doing this is Bad:<br>
```
.my-custom-color: {
    color: #fff;
}

<button class="btn btn-primary my-custom-color"></button>
```
