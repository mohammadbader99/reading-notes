# Images, Color, Text

## Adding images

You can add **images** to web pages with *HTML* by using `<img>` element and specifying an `src` attribute to put the url or the source of the image.

Also you need to add an `alt` attribute to tell the content of the image.

```
<img src="pic.jpg" alt="Picture">
<img src="URL" alt="Picture">
```

## Colors

The ways to add or change a **color** using *CSS*:

* RGB:
  * `background-color:rgb(255, 166, 13)`
* RGBA:
  * `background-color:rgba(255, 0, 0, 0.3);`
* Hex code:
  * `background-color:#fe4g77`
* Color name:
  * `background-color:Blue`
* HSL:
  * `background-color:hsl(100, 100%, 50%)`
* HSLA:
  * `background-color:hsla(100, 100%, 50%, 0.5)`

There are color pickers to help you with rgb and hex codes:

![CSS color picker](https://docs.jboss.org/richfaces/latest_3_3_X/en/devguide/html/images/colorPicker_init.png)

## Text

You can control the text font, color, size, etc..

```
h1 {
    font-size: 50px;
    text-align: center;
    color: white;
    text-shadow: 2px 2px 2px black;
}
```