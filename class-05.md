# Images, Color, Text in *HTML*
## HTML Images 
 **In the beginning, the Web was just text, and it was really quite boring. 
Images and colors make a website much better**

![img tag](http://www.easytolearning.com/webroot/ck_files/files/html-image-tag.png)

>note: images use two attributes to describe the size  *Height* & *Width* in pixels

  ### To add an image:
1. Save images in the right format : Websites mainly use images in jpeg, gif, or png format. If you choose the wrong image format then your image might not look as sharp as it should and can make the web page slower to load. 
2. Save images at the right size :You should save the image at the same width and height it will appear on the website. If the image is smaller than the width or height that you have specified, the image can be distorted and stretched. If the image is larger than the width and height if you have specified, the image will take longer to display on the page. 
3. Use the correct resolution : Computer screens are made up of dots known as pixels. Images used on the web are also made up of tiny dots. Resolution refers to the number of dots perinch, and most computer screens only show web pages at 72 pixels per inch. So saving images at a higher resolution results in images that are larger than necessary and take longer to download.

 **alt** Its value is supposed to be a textual description of the image, for use in situations where the image cannot be seen/displayed or takes a long time to render because of a slow internet connection.

-----
 ## Colors in HTML
 
There is no special HTML color tag, as design is not the main function of HTML. Coloring your website is a part of CSS inline styling. This means you need to use the style attribute in the opening tag you wish to add HTML color to.
You may use the color property to change the color of your text, or background-color to change the color of the background. Both of these properties take color names, RGB, RGBA, HEX, HSL or HSLA values.
* rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)
* hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash \#
sign. For example: #ee3e80

![colors](https://cssworkshop.files.wordpress.com/2015/03/css-declaration.png)

-----
![codes](https://www.researchgate.net/profile/Cecilia-Sik-Lanyi/publication/286188671/figure/tbl1/AS:652964813369346@1532690351113/1-Colour-values.png)

**Contrast**
When picking foreground and background
colors, it is important to ensure that there is
enough contrast for the text to be legible.
**Opacity**
allows you to
specify the opacity of an element
and any of its child elements.
The value is a number between
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15%
opacity).
p.one {
background-color: rgb(0,0,0);
opacity: 0.5;}

------
## TEXTS
**The formatting of your text can have a significant effect on how readable your pages are. As we look through these properties I will also give you some design tips on how to display your type.**

Formatting elements were designed to display special types of text:

* \<b> - Bold text
* \<strong> - Important text
* \<i> - Italic text
* \<em> - Emphasized text
* \<mark> - Marked text
* \<small> - Smaller text
* \<del> - Deleted text
* \<ins> - Inserted text
* \<sub> - Subscript text
* \<sup> - Superscript text

\<b> **Bold** \</b>
\<i> *Italic* \</i>

------
## JPEG vs PNG vs GIF
* JPEG images don’t support transparency and are hence not usable for such cases.
* PNG images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency). Partial transparency makes the edges blend smoothly into the background. PNG8 images (discussed in the “Colours” section below) can support only index transparency whereas PNG24 images can support alpha channel transparency.
* GIF images support transparency by declaring a single colour in the colour palette as transparent (index transparency). Because of absence of partial transparency, the edges (specially rounded or too-detailed edges) get a poor jagged effect. Though this can be solved to some extent using dithering, with improved PNG support, GIF is unsuitable for images with transparent backgrounds.


###### source:
1. [Duckett HTML book](DucketHTML.com)
2. [JPEG vs PNG vs GIF](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d)
