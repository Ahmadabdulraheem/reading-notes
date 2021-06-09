# HTML Links, JS Functions, and Intro to CSS Layout

### *LINKS AND LAYOUT*
**Links**
>Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.
Writing Links:
  * Links are created using the \<a> element. Users can click on anything between the opening \<a> tag and the closing \</a> tag. You specify which page you want to link to using the href attribute.

  * When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.
 \<a href="index.html">Home\</a>.
 
 **Directory Structure**
 On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder.
 * The diagram on the right shows the directory structure for a fictional entertainment listings website called ExampleArts. The top-level folder is known as the root folder. (In this example, the root folder is called examplearts.) The root folder contains all of the other files and folders for a website.

![Structure](https://stuyhsdesign.files.wordpress.com/2015/09/directory-structure1.png)
 
 **Building Blocks** 
 >CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
* Building Blocks CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
* *Containing Elements*; If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
* *Controlling the Position of Elements* CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.


-----
### *Functions, Methods, and Objects*
>Browsers require very detailed instructions about what we want them to do. Therefore, complex scripts can run to hundreds (even thousands) of lines. Programmers use functions, methods, and objects to organize their code.

*WHAT IS A FUNCTION?*
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements).
  *function name() {  }*
and in order to call it : *name();*

* **VARIABLE SCOPE** The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope.

-----
sources:
* [Duckett HTML](https://wtf.tw/ref/duckett.pdf)
* [Duckett JS ](https://www.goodreads.com/book/show/16219704-javascript-and-jquery)
