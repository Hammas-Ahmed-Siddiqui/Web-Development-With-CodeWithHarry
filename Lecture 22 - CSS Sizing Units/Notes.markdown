# CSS Size Units

* px
* %
* vw = viewport width
* vh = viewport height
* rem
* em

*Q* - What is a size Unit?

*A* - A size unit is a standard of measurement for the size of something. It is used to compare the size of different things, or to measure the size of something over time. Size units can be used to measure the length, width, height, volume, or weight of something.

### Absolute Units
*Fixed*
### Relative Units
*Dependent upon any "X" factor*


# Relative Units

## %
It take the assigned perecentage of length or width of it's immediate parent


###### *What is viewport?*
###### *The viewport is the visible area of the browser window, excluding any browser UI elements such as the scrollbar or address bar.*
## vw [VIEWPORT WIDTH]
* 1vw is 1% of the viewport width.

Example 1: Using vw for Font Size

```
/* Set font size to 5% of the viewport width */
body {
  font-size: 5vw;
}

```

## vw [VIEWPORT HEIGHT]
* 1vh is 1% of the viewport height.

Example 1: Using vh for Container Height

```
/* Set container height to 50% of the viewport height */
.container {
  height: 50vh;
}
```
Example: Using Both vw and vh
```
/* Set width to 70% of the viewport width and height to 80% of the viewport height */
.rectangle {
  width: 70vw;
  height: 80vh;
}
```

# Absolute Units
Absolute units are typically used for things like:

* Image dimensions
* Font sizes
* Button sizes
* Margin and padding values

#### px
#### cm
#### inch
#### mm

## px
Pixels are relative to the device's pixel density, so a pixel on a high-resolution device will be smaller than a pixel on a low-resolution device.

```
/* Set the width of an image to 100 pixels */
img {
  width: 100px;
}

/* Set the font size of a heading to 20 pixels */
h1 {
  font-size: 20px;
}

/* Set the margin of a paragraph to 1 centimeter */
p {
  margin: 1cm;
}
```

# What is the difference between ppi and dpi?
