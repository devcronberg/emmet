# Basic Emmet abbreviations

See the full list at https://docs.emmet.io/cheat-sheet/

## HTML


```html
nav>ul>li
<nav>
    <ul>
        <li></li>
    </ul>
</nav>

div+p+bq
<div></div>
<p></p>
<blockquote></blockquote>

ul>li*5
<ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul>

ul>li.item$*5
<ul>
    <li class="item1"></li>
    <li class="item2"></li>
    <li class="item3"></li>
    <li class="item4"></li>
    <li class="item5"></li>
</ul>

h$[title=item$]{Header $}*3
<h1 title="item1">Header 1</h1>
<h2 title="item2">Header 2</h2>
<h3 title="item3">Header 3</h3>

ul>li.item$$$*5
<ul>
    <li class="item001"></li>
    <li class="item002"></li>
    <li class="item003"></li>
    <li class="item004"></li>
    <li class="item005"></li>
</ul>

#header
<div id="header"></div>

.title
<div class="title"></div>

form#search.wide
<form id="search" class="wide"></form>

p.class1.class2.class3
<p class="class1 class2 class3"></p>

p[title="Hello world"]
<p title="Hello world"></p>

td[rowspan=2 colspan=3 title]
<td rowspan="2" colspan="3" title=""></td>

[a='value1' b="value2"]
<div a="value1" b="value2"></div>

a{Click me}
<a href="">Click me</a>

p>{Click }+a{here}+{ to continue}
<p>Click <a href="">here</a> to continue</p>

a:link
<a href="http://"></a>

link:css
<link rel="stylesheet" href="style.css" />
```
