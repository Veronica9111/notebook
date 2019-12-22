# HTML

*Reference:*
https://www.w3schools.com/html/
https://html.com/
https://developer.mozilla.org/en-US/docs/Web/HTML



Stands for **Hyper Text Markup Language**

\<!DOCTYPE html\> defines the document to be html5

HTML headings are defined with the <h1\> to <h6\> tags.

<br\>  defines a line break.

HTML is not case sensitive, lowercase is recommaned, and demanded for XHTML.

alt speicifies an alternative text if the image could not be displayed.

Language could be declared with *lang* in <html\> tag.

title could be a tooltip for <p\> tag.

Use lowercase and quotes for the attributes.

<hr\> is used to separate the content, or define a change.

The <p\> tag will remove all extra spaces and lines, use <br\> to change line.

/<pre/> could define a preformatted text

<b /><b>bold</b>  only visually look bold

<strong/> <strong>strong</strong> also semantically emphasizes

<i/> <i>ilatic</i>

<em/> <em>emphasized</em>

<mark/> <mark>marked</mark>

<small/> <small>small</small>

<del /> <del>deleted</del>

<ins/> <ins>inserted</ins>

<sub/> <sub>subscript</sub>

<sup/><sup>superscript</sup>

<q/> <q> quote</q>

/<blockquote />  <blockquote cite="www.google.com"> blockquote</blockquote>

<!-- Comment --> 

css could be added to HTML elements in three ways:
Inline: with the attribute: style
Internal: using <style> tag
External: using an external css file

a::target
_blank open in a new window/tab
_self open in current window/tab(default)
_parent open in the parent frame :question:
_top open in the full body of the window :question:

Title could be shown as tooltip if mouse over the link.

a:link a:visited a:hover a:active

Link bookmark

```html
<h1 id="mybookmark">My bookmark</h1>
<a href="#mybookmark">Jump to My bookmark</a>
```

Better to use set the width and height of the image using style attribute since we need to prevent style sheet modify the value.

Image Maps
define an image with multiple clickable areas of different actions.

```html
<img src="mypic.jpg" alt="mypic" usemap="#mymap">

<map name="mymap">
  <area shape="rect" coords="0,0,20,20" alt="Rectangle" href="rectangle.htm">
  <area shape="circle" coords="50,50,20" alt="Circle" href="circle.htm">
</map>
```

Attributes: rec, circle, poly, default

### Picture tag

Introduced by HTML5

```html
<picture>
  <source media="(min-width: 1000px)" srcset="big.jpg">
  <source media="(min-width: 500px)" srcset="small.jpg">
  <img src="default.jpg">
</picture>
```

The browser will choose the image with matches best to the device.





 