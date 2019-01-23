# Center and Crop Images

# Drawing structure steps

1.  Create a div wrapper around the image(s) and set a class.
2.  Set margin and padding attributes, at least margin so it fits on its own container.
3.  Set the following settings in the containded image.
```css
    .img-wrapper img {
    /*  */
    object-fit: cover; /* Do not scale the image and make it cover all spaces*/
    object-position: center; /* Center the image within the element */
    width: 100%;
    /* Fix the hight proportionally to the ViewPort or Fix It */
    /* height: 33vh; */
    height: 200px;
    }
```


# Notes

**Important:** Try to adjust the height with media queries to have it consistent in all devices.

[Reference](https://stackoverflow.com/questions/11552380/how-to-automatically-crop-and-center-an-image)
[Mozilla MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit)