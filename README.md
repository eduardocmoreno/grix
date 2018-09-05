# GRIX - a sass flexbox-grid mixin tool

### HTML
```HTML
<div class="grid">
  <div class="grid-item">
    <div class="item-contents">
      my contents here
    </div>
  </div>
  ...more grid items here
</div>
```

### SASS/SCSS
```scss
/*
* $cols: number
* $gap: number + px sufix
* $width: flex (default) or fixed
*/

//example
.grid{
  //four cols, 20px gap and flexible width
  @include grid(4, 20px);
  
  //three cols, 10px gap and fixed width
  @include grid(3, 10px, fixed);
}
```
