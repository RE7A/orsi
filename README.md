ORSI CSS Responsive Grid System
-------------------------------
##ORSI?
Orsi system has made by a comination of Floting and Flexing properties which is faster to make your webpage Layout and If you are a web developer, Orsi system can build an easy and efficient path by [SASS](http://sass-lang.com) to improve this system.
### ORSI Grids
Orsi grid includes 12 Responsive grids that you can use them easily.
###How to Work?
What you'll do, is so simple.
you can choose the size of your element For each unit in each row with the help of below chart.
To understand better Look at The [examples](https://codepen.io/orsi-grid). 
####Main-classes
Classes | media Queries<br>(min-width) | Pixel Range | Devices  
------------ | ------------- | ----------- | -------
.lg-[1-12] | null |  > 1200Px | Descktop PC and Retina Displays
.md-[1-12] | 75em |  < 998Px | Desktop PC and Tablets
.sm-[1-12] | 62.375 em | < 768PX | Tablets and Mobiels
.xs-[1-12] | 48em | < 400Px | mobiles
####Other-Classes
**.Container**<br>
Floating parent container elments.<br><br>
**.flex-center**<br>
To align to several items,we gave Flex-center class to parent element.<br><br>
**.align-self**<br>
After using ***.flex-center*** you can horizantally self item align to center with this class.<br><br>
**.Text-center**<br>
Align to center text.<br><br>
**.img-responsive**<br>
to the image so that it scales nicely to the parent element. <br><br> 
**.Float-right & .Float-left**<br>
floating elements to right or left.<br><br>
##Get Start
####1.Include Stylesheets File
```html
<!--orsi with comments-->
<link rel="stylesheet" href="/dist/ltr/orsi-ltr.css">
<!--orsi without comments-->
<link rel="stylesheet" href="/dist/ltr/orsi-ltr-min.css">
```
####2.Add the Viewport Meta Tag
Place in the <head> of your HTML. This enables use of media queries for cross-device layouts.
```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```
####3.Create Column Sizes
```html
   <div class="container">
       <div class="lg-2 md-6"></div>
       <div class="lg-2 md-6"></div>
       <div class="lg-2 md-6"></div>
   </div>
```
####4.Style for Showing
```css
  .lg-2{
    background:#ccc;
    height:2.5rem;
  }
```
##Examples
you can see other Examples [This Page](https://codepen.io/orsi-grid).

*Hope enjoy it.*
  
  







