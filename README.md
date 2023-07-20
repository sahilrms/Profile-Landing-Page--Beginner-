# Profile-Landing-Page--Beginner
This Project shows the implementation of flex for making basic profile landing page.<br><br>
Brief about flex in css <br>
**Flex in CSS**

CSS flexbox is a layout model that allows you to easily arrange items in a container. It is a more flexible and efficient way to create responsive layouts than the traditional `float` and `position` properties.

To use flexbox, you first need to set the `display` property of your container element to `flex` or `inline-flex`. This will make the element a flex container, and its children will become flex items.

Once you have defined your flex container, you can use the following properties to control the layout of your flex items:

* **flex-direction:** This property defines the direction in which the flex items will be laid out. The possible values are `column` and `row`.
* **flex-wrap:** This property defines whether the flex items will wrap to the next line if they do not fit within the container. The possible values are `nowrap` and `wrap`.
* **flex-grow:** This property controls how much space a flex item will take up if there is extra space in the container. The possible values are `0` (no extra space), `1` (equal space), and `auto` (as much space as needed).
* **flex-shrink:** This property controls how much a flex item will shrink if there is not enough space in the container. The possible values are `0` (no shrinking), `1` (equal shrinking), and `auto` (as much as needed).
* **flex-basis:** This property defines the default size of a flex item before the remaining space is distributed.

Here is an example of a web page that uses flexbox to create a responsive layout:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flex Layout Demo</title>
</head>
<body>
  <div class="container">
    <div class="item">This is a red box</div>
    <div class="item">This is a green box</div>
    <div class="item">This is a blue box</div>
  </div>
</body>
</html>
```

This web page uses flexbox to create a flex container with 3 flex items. The flex items are laid out in a row by default, and they will wrap to the next line if they do not fit within the container. The flex items will take up as much space as they need, and they will shrink equally if there is not enough space.

You can try this example yourself by opening it in a web browser. You should see a row of 3 boxes, one after the other. If you resize the browser window, the boxes will wrap to the next line if necessary.

Flexbox is a powerful and flexible layout model that can be used to create a variety of layouts. By understanding the basic concepts of flexbox, you can create beautiful and responsive web pages that will look great on any device.
