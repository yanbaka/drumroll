#jquery.drumroll

## Description

Image partial enlargement

## Demo

[DemoPage](https://yanbaka.github.io/drumroll/index.html)

## Usage

### Step 1: Required files
```html
<!-- jquery library -->
<script type="text/javascript" src="jquery-1.11.3.min.js"></script>
<!-- jquery.drumroll javascript file -->
<script type="text/javascript" src="jquery.drumroll.min.js"></script>
<!-- jquery.drumroll css file -->
<link rel="stylesheet" type="text/css" href="jquery.drumroll.min.css">
```

### Step 2: HTML markup
```html
<div id="drumroll1">
    <img src="images/num0.png">
    <img src="images/num1.png">
    <img src="images/num2.png">
    <img src="images/num3.png">
    <img src="images/num4.png">
    <img src="images/num5.png">
    <img src="images/num6.png">
    <img src="images/num7.png">
    <img src="images/num8.png">
    <img src="images/num9.png">
</div>
```

### Step 3: Excute
```javascript
$("#drumroll1").drumroll();
```

## Parameters
|Parameter|Type|Default|Description|
|:--|:--|:--|:--|
|targetNum|number|1||
|loop|number|1|loop count|
|delay|number|0||
|duration|number|1000||
|easing|string|linear|*required library jquery.easing.1.3.js|
|onDrumrollLoad|function|||
|onDrumrollAfter|function|||

## Licence

[MIT](https://github.com/yanbaka/drumroll/blob/master/LICENSE)

## Author

[yanbaka](https://github.com/yanbaka)