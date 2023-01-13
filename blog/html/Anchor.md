## HTML Anchor


The HTML anchor tag defines a hyperlink that links one page to another page. It can create hyperlink to other web page as well as files, location, or any URL. The "href" attribute is the most important attribute of the HTML a tag. and which links to destination page or URL.



href attribute of HTML anchor tag

The href attribute is used to define the address of the file to be linked. In other words, it points out the destination page.

The syntax of HTML anchor tag is given below.

``` html
<a href="..........."> 
    Link Text 
</a>
```

```html
<a href="https://www.nasa.gov/">
    Click for Second Page
</a>
```
		
output:

***

<a href="https://www.nasa.gov/">Click for Second Page</a>

<br />

Specify a location for Link using target attribute

If we want to open that link to another page then we can use target attribute of <a> tag. With the help

```html
<!DOCTYPE html>  
<html>  
    <head>  
        <title></title>  
    </head>  
    <body>  
        <p>Click on <a href="https://www.nasa.gov/" target="_blank"> this-link </a>to go on home page of NASA.</p>
    </body>  
</html>
```
		
output:


<p>Click on <a href="https://www.nasa.gov/" target="_blank"> this-link </a>to go on home page of NASA.</p>



<br />

The target attribute can only use with href attribute in anchor tag.

If we will not use target attribute then link will open in same page.



Appearance of HTML anchor tag
An unvisited link is displayed underlined and blue.
A visited link displayed underlined and purple.
An active link is underlined and red.
