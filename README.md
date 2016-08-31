![alt tag](http://duskoperic.com/svg/svg.png)
# SVG Self-drawing Icons

[Check DEMO here!](http://duskoperic.com/svg/)

##Basic Usage
1. Include the stylesheet and script on your document's `<head>`

  ```html
  <head>
    <link rel="stylesheet" href="icon-style.min.css">
    <script type="text/javascript" src="jsicon.min.js"></script>
  </head>
  ```
2. Add the svg tag with attributes

  ```html
<svg draw="single" effect="rotate-auto" width="128" height="128" color="#00B5E8" class="svg-icon  dummbell " viewBox="0 0 256 256"></svg>
  ```

3. Instead of dummbell class add name of your icon. A list of all the icons can be found [here](http://duskoperic.com/svg/#/icons)

##Attributes
draw:

 * `single`
 * `infinite`
 
effect:

 * `rotate-auto`
 * `rotate-hover`
 * `flip-vertical-auto`
 * `flip-vertical-hover`
 * `flip-horisontal-auto`
 * `flip-horisontal-hover`
 * `bounce-auto`
 * `bounce-hover`
 
width:

 * `0-256`

height:

 * `0-256`
