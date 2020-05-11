---
title: CSS tricks with images that would make web designing easier
date: "2020-05-10T18:49:37.121Z"
description: "Simple CSS tricks with images that would help you develop web pages a little better and faster. Among these are backgroud-repeat, media queries and how to import a new library in CSS."
---

*This article shares some of my most pleasing moments learning CSS, and I hope it's the same for you as well.*

CSS is a Cascading Style Sheet and used to describe how HTML elements should display. CSS can not only provide colours, positions to the HTML elements, etc., but it can also create animations and enhance the web page. It's totally worth to know some useful tips and tricks which may help you create amazing web pages.

## 1. background-repeat

The <font color ="#905"> <span style="background-color:#e1e2e3">background-repeat</span></font> property sets if and how a background image will be repeated. It is used in conjunction with the <span style="background-color:#e1e2e3">background-image</span> property. We can repeat the background image along the horizontal, vertical axis or not repeat at all.<br>
*By default, a <span style="background-color:#e1e2e3">background-image</span> is repeated both vertically and horizontally.*

<b>Syntax</b>
```CSS
background-repeat: value; 
```
<br>
<b>Property Values </b>

<style>
.shadow {
    background: #F7F8F9;
    padding: 3px;
    margin: 10px 0;
    }
.space {
    margin-bottom: 25px!important;
}
table.data th {
    color: #000;
    padding: 8px 7px;
    text-align: left;
    font-size: 15px;
    background: #F8F8F8;
}
table.data th, table.data td {
    vertical-align: top;
    border: 1px solid #DCE3EB;
}
table.data td {
    color: #484848;
    padding: 5px 7px;
}
table {
    border-collapse: collapse;
    border-spacing: 0;
    -webkit-border-horizontal-spacing: 0px;
    -webkit-border-vertical-spacing: 0px;
}
</style>

 <div class="shadow space">
    <table class="data">
        <tr>
            <th style="width:85px;">Value</th>
            <th>Description</th>
        </tr>
        <tr>
            <td><code>repeat</code></td>
            <td>The background image will be repeated both vertically and horizontally.</td>
        </tr>
        <tr>
            <td><code>repeat-x</code></td>
            <td>The background image will be repeated horizontally only.</td>
        </tr>
        <tr>
            <td><code>repeat-y</code></td>
            <td>The background image will be repeated vertically only.</td>
        </tr>
        <tr>
            <td><code>space</code></td>
            <td>The background image will be repeated as many times as it will fit, but it is not clipped.</td>
        </tr><tr>
            <td><code>round</code></td>
            <td>The background image will stretch or shrink slightly to avoid clipping and to produce no gaps.</td>
        </tr>
		<tr>
            <td><code>no-repeat</code></td>
            <td>The background image will not be repeated.</td>
        </tr>
		<tr>
			<td><code>initial</code></td>
			<td>Sets this property to its default value.</td>
		</tr>
    </table>
</div>
<b>CSS Example</b>

```CSS
body {
    background-image: url("images.png");
    background-repeat: repeat;
}
```
![background-repeat](./background-repeat.png)<br>
<i>You can view the source code<a href="https://github.com/nimritees/webpage_practices/tree/master/cssTricks/background-repeat" target="_blank"> here</a></i>.

## 2. background-blend-mode
