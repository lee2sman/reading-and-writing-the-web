# Class 11

# More CSS

Just when you thought you were done with CSS....

* Flexbox
* CSS Grid
* CSS Frameworks

## Flexbox
Flexbox is a relatively new approach to laying out content and making it responsive without using floats.

![Flexbox](https://davidwalsh.name/demo/flexbox-twelve/codepen9.png)

1. Start by defining a container to hold everything

```
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```

In your CSS

```
.flex-container {
  display: flex;
}
```

#### Flex container properties available

```
flex-direction
flex-wrap
flex-flow
justify-content
align-items
align-content
```

For example, to stack items in a column vertically

```
.flex-container {
  display: flex;
  flex-direction: column;
}
```

To stack horizontally

```
.flex-container {
  display: flex;
  flex-direction: row;
}
```

To wrap items, use ```flex-wrap: wrap;```. The default is *no-wrap*.

```
.flex-container {
  display: flex;
  flex-wrap: wrap;
}
```

To center items, use *justify*

```
.flex-container {
  display: flex;
  justify-content: center;
}
```

**There are a lot more options!** Check out the Responsive Design template section at the bottom of the W3Schools tutorial below.

### Flexbox Resources

* W3Schools [tutorial](https://www.w3schools.com/csS/css3_flexbox.asp)
* [Flexbox Froggy](https://flexboxfroggy.com/) is a web-browser game where you practice writing with flexbox to move froggies around a screen
* Flexbox [Basic Concepts](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)

# CSS Grid

CSS grid is another layout system, as an alternate to using float-positioning or Flexbox. The Grid Layout system specifies rows and columns and makes it easier to design web pages without having to use floats and positioning.

Like Flexbox, you set up a container. Inside the container are *child* items wrapped inside the div. Any div or item can be set as a container by setting its css property to ```display: grid```.

```
.grid-container {
  display: grid;
}
```

#### Example

```
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>
  <div class="grid-item">7</div>
  <div class="grid-item">8</div>
  <div class="grid-item">9</div>
</div>
```

### Gaps

Rows and Columns are self-explanatory. Gaps are the spaces between each row and column.

![CSS Grid gaps](https://www.w3schools.com/csS/grid_gaps.png)

Set the space between columns with any of these 3
* rid-column-gap
* grid-row-gap
* grid-gap   

Grid gap sets column and row together. Specify two values for column, row - or a single value to set both to the same value.

### CSS Grid Resources

* W3Schools [tutorial](https://www.w3schools.com/csS/css_grid.asp)
* Grid container [info](https://www.w3schools.com/csS/css_grid_container.asp)

# CSS Templates

* [Templates](https://www.w3schools.com/csS/css_templates.asp) for basic pages with Floats, Flexbox and Grid

# Final Project in-class review

# Homework
* CSS Flexbox Froggy [tutorial/game](https://flexboxfroggy.com)
* CSS Grid Garden [tutorial/game](http://cssgridgarden.com/)
* Presentations next week!
