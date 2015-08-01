# Oh yes… another Flexbox Grid

Grid based on the `flex` display property using Sass and BEM naming convention.

## Quick install

Open your main Sass file, import `_grid.sass` and compile.

## Usage

It works like flexboxgrid, but using BEM naming convention which it makes it easier for developers to follow and import their projects.

There is two kinds of containers: normal and fluid.

```
.container
  .row

.container--fluid
  .row

```

A typical row with 3 colum would be:

```
.container
  .row
    .col__lg--4
      ...
    .col__lg--4
      ...
    .col__lg--4
      ...
```

You can make them also with self and achieve the same result:

.container
  .row
    .col__lg--self
      ...
    .col__lg--self
      ...
    .col__lg--self
      ...
```

You can apply some attributes to `.row` anytime:

```
.container
  .row.row--reverse
    .col__lg--4
      3
    .col__lg--4
      2
    .col__lg--4
      1
```

Inspiration
-----------
- [flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid/)
- [topcoat-grid](https://github.com/topcoat/grid)
- [flexbox-grid by @zeMicro](https://github.com/zeMirco/flexbox-grid)
- [ptb2.me/flexgrid](http://ptb2.me/flexgrid/)
- [codepen.io/marcolago/pen/lqGFb](http://codepen.io/marcolago/pen/lqGFb)
- [philipwalton.github.io/solved-by-flexbox/demos/grids](http://philipwalton.github.io/solved-by-flexbox/demos/grids/)
- [davidwalsh.name/stylus-grid](http://davidwalsh.name/stylus-grid)