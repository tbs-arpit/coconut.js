# Coconut.js
A jQuery plugin to show a information in circle

## What is this

This is a library which does this 

![image](https://user-images.githubusercontent.com/41741151/67190276-4de33980-f40d-11e9-8d8f-15823f0a03c5.png)

Trust me it looks way nicer when you implement.

Everything you see in above image is configurable. except the circle😜


## How to use it?

Inside document ready you can do this.

```
$('#selector').coconut({
    thickness: 1.15,
    values: [{
        amount: 10,
        color: "#001f3f"
    },
    {
        amount: 100,
        color: "#b58484"
    }],
    borderColor:"#0000FF",
    innerFill:"#8ac8ff",
    centerIconSrc: {
        url: "./PiggyBank.png",
        sizePortion: 2
    },
    //centerSideValue: 5
    centerValue:"99+"
});
```

Here are the all configs and what they do

| config | type | purpose |
| ------ | ------ | ------ |
| thickness | number | thickness of the surrounding border
| values | object | two objects with values and it's colors. will be drawn from bottom center of the circle
| centerIconSrc | object | URL of the center image and portion of that image in circle for example if your circle is 500x500 and portion is 2 then center image will be 250.
| centerValue | string | number or a string which will be shown on top of image
| borderColor | string (hex) | Color of the border around the circle
| innerFill | string (hex) | Inner color of the circle

## Got an issue?

If you have any issues feel free to contact me on skype or raise an issue [here on github](https://github.com/tbs-arpit/coconut/issues/new)

