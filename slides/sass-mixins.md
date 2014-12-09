##  SASS Mixins

_Mixins are friendly, Mixins are cool, Mixins are reusable_

```
$btn-font-size: 18px;
$primary-color: #ff00ff;
@mixin btn-base{
    font-size: $btn-font-size;
    border: 1px solid;
    text-align: center;
}

@mixin btn-variant($color, $background, $border){
    color: $color;
    border-color: $border;
    background-color: $background;
}

.btn {
    @include btn-base();
}

.btn-variant-1 {
    @include btn-variant($primary-color, darken($primary-color, 10),lighten($primary-color, 10));
}

<a class="btn btn-variant-1"></a>
```
