# css-framework
A custom 12 Grid css frame-work developed with sass.

## Installation
This framework is hosted with https://gitcdn.link/ .You can include this in project by simply including this link between your "head" tags in your html file.
```html
<link rel="stylesheet" href="https://gitcdn.xyz/repo/Cena-JM/css-framework/development/assets/css/styles.css" />
```

## Live Demo to the project
https://raw.githack.com/cena-JM/css-framework/development/

## A project by:
-Musa Jabbaaru Ntege : https://github.com/Cena-JM<br>
-Kingsley Omotayo : https://github.com/kvnlay

## Specs
Everything is a flexbox, it's the main positioning technique in this framework. So make sure that you fully understand how these classes work `row`, `container`, and `col-sz-*`. This framework is made to fit all screen sizes with mobile responsiveness as a primary issue to tackle.
It also has offset classes that can be accessed by the class names `col-offset-sz-*`
**Note:** `sz` is the screen size (breakpoint). The screen sizes are `sm: 576`, `md: 768`,`lg: 992`,`xl: 1200`
**Note:** `*` is the number of columns from `1` to `12`



## Box-sizing:
We are using border-box as default box-sizing
```css
html {
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: inherit;
}
```


## Grids
We are using 12 columns grid without gutters between the columns.

## Padding & Margins

We use m and p for padding and margin respectively in both a specific direction with the suffix `-lr`,`-tb`,`-t`, `-r`, `-b` and `-l`, or in all directions with varying size `1px` to `80px`.

### Examples:
- `m-20`  -> 20px margins from all directions
- `p-r-30` -> 30px padding from right
- `m-lr-2` -> 2px padding from both left and right
- `p-tb-10` -> 10px padding from both top and bottom


## Buttons
Buttons can be used by:
- including the `btn` class to your element and selecting the color by including `btn-[color]` where `[color]` can be `green`,`blue`, `yellow`, `red`, `dark`, `tp`

## Font Size
Font sizes are varied from `font-size-8` to `font-size-64`. You can also used `font-size-a[num]-rem` where `[num]` ranges from `0.1rem to 5rem`. It's not so flexible, but remember you can always use custom css.


## Font Weight
Font weights can be accessed by using the `font-weight-[number]` where `[number]` are varied from `300`, `400`, `500`, `700` and `800` and also classes `font-weight-light`, `font-weight-normal`, `font-weight-medium`, `font-weight-bold` and `font-weight-bolder`.


## Flex 
First to use custom flex boxes, you just need to add `d-flex` class to your tag.


### Flex Direction
You can specify the direction using `flex-row`, `flex-column`, `flex-col-rvs` or `flex-row-rvs` for the flex parent.

### Flex Horizontal Positioning
You can use `align-items-start`, `align-items-end`, `align-items-center`, `align-items-around` and `align-items-between` to adjust the *content* justification horizontally inside the flex parent. 

### Flex Vertical Positioning
Similarly, you can use `justify-content-start`, `justify-content-end`, `justify-content-center`, `justify-content-around` and `justify-content-between` to adjust the *content* justification vertically inside the flex parent. 


**Okay, but what about positioning items?**
## Positioning
Also, you can use `position-relative`, `position-absolute`, `position-fixed`, `position-sticky`, `position-static` for item positioning.

## text Positioning
you can use `text-align-center`, `text-align-right`, `text-align-left`, `text-align-justify`, `text-align-initial`, `text-align-inherit` for text positioning.

