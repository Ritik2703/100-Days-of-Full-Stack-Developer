# 100-Days-of-Full-Stack-Developer
# Hare Krishna
# Radhe Radhe
---------------------------------------------------------------------------------------------------------------------------          
# Day 1 (Intro to HTML)

##  Headings- 
##             https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements
##             https://www.w3schools.com/html/html_headings.asp
##             https://devdocs.io/html/

6 heading tags
  

```
<center>
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
</center> 
```
## Self Closed Tags-
```
<br> -change line
<hr> -  make a line
```
          
## Comment

```
<!-- comment -->

```

# HTML Boilerplate code

`````
<!DOCTYPE html> 
<!-- tells the version of html-->
<html lang="en" dir="ltr">   <!-- now everything is html code-->
  <head>    <!-- whole info of webpage and how to handle it -->
    <meta charset="utf-8">    <!-- gives extra meta(associate data to file)-->
    <title>Ritik's Personal Site</title>    <!-- title of Page-->
  </head>
  <body>
    
  </body>
</html>
`````
------------------------------------------------------------------------------------------------------------------------------------


# HTML Cheatsheet - 
https://docs.emmet.io/cheat-sheet/

# Atom Shortcuts 
https://github.com/nwinkler/atom-keyboard-shortcuts

# Meta data/tag - 
1. https://www.w3schools.com/tags/tag_meta.asp
2. http://www.fileformat.info/info/charset/UTF-8/list.htm
3. https://unicode-table.com/de/sets/
4. https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/

# HTML Attributes -
1.All HTML elements can have attributes
2.The href attribute of <a> specifies the URL of the page the link goes to
3.The src attribute of <img> specifies the path to the image to be displayed
4.The width and height attributes of <img> provide size information for images
5.The alt attribute of <img> provides an alternate text for an image
6.The style attribute is used to add styles to an element, such as color, font, size, and more
7.The lang attribute of the <html> tag declares the language of the Web page
8.The title attribute defines some extra information about an element
  
```
<p title="About csog">csog is a web developer's site.</p>
<img src="csog.jpg" width="250" height="400">
<a href="https://www.csog.com">This is a link</a>
<img src="csog.png" alt="csog Logo">
```

# HTML Paragraphs-
Tag	Description

```
1. <p>	  Defines a paragraph
2. <hr>	Defines a thematic change in the content
3. <br>	Inserts a single line break
4. <pre>	Defines pre-formatted text
```

```
<html>
<body>
<p>Hello World!</p>

</body>
</html>

<h1>London</h1>
<hr>
<p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>

<p>My Bonnie lies<br>over the ocean.</p>

<pre>

  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>

```
# HTML Styles-
1. Use the style attribute for styling HTML elements
2. Use background-color for background color
3. Use color for text colors
4. Use font-family for text fonts
5. Use font-size for text sizes
6. Use text-align for text alignment

```
<p style="color:blue;">This is a paragraph.</p>
<p style="font-family:courier;">This is a paragraph.</p>
<p style="text-align:center;">This is a paragraph.</p>
<p style="font-size:50px;">This is a paragraph.</p>
<html>
<body style="background-color:yellow;">

<h1>This is a heading</h1>

<p>This is a paragraph.</p>

</body>
</html>

<html>
<body style="text-align:center;">

<h1>This is a heading</h1>

<p>This is a paragraph.</p>

</body>
</html>
```
# HTML Formatting-

HTML Text Formatting Elements
Tag	Description
```
<b>	Defines bold text
<em>	Defines emphasized text 
<i>	Defines a part of text in an alternate voice or mood
<small>	Defines smaller text
<strong>	Defines important text
<sub>	Defines subscripted text
<sup>	Defines superscripted text
<ins>	Defines inserted text
<del>	Defines deleted text
<mark>	Defines marked/highlighted text
```

# HTML Quotations-

```
<abbr>	Defines an abbreviation or acronym
<address>	Defines contact information for the author/owner of a document
<bdo>	Defines the text direction
<blockquote>	Defines a section that is quoted from another source
<cite>	Defines the title of a work
<q>	Defines a short inline quotation

<bdo dir="rtl">This text will be written from right to left</bdo>
<p>The <abbr title="World Health Organization"> WHO</ abbr> was founded in 1948.</p>
```

# HTML Colors- https://www.w3schools.com/colors/colors_names.asp

HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

```
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:Tomato;">Tomato</h1>
<h1 style="background-color:Orange;">Orange</h1>
<h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
<h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>
<h1 style="background-color:Gray;">Gray</h1>
<h1 style="background-color:SlateBlue;">SlateBlue</h1>
<h1 style="background-color:Violet;">Violet</h1>
<h1 style="background-color:LightGray;">LightGray</h1>

</body>
</html>

```

```
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```

# HTML CSS-
````
Use the HTML style attribute for inline styling
Use the HTML <style> element to define internal CSS
Use the HTML <link> element to refer to an external CSS file
Use the HTML <head> element to store <style> and <link> elements
Use the CSS color property for text colors
Use the CSS font-family property for text fonts
Use the CSS font-size property for text sizes
Use the CSS border property for borders
Use the CSS padding property for space inside the border
Use the CSS margin property for space outside the border
  ````

# Day 2 (CSS) - https://www.w3schools.com/css/default.asp

# Day 3,4 (BootStrap) - https://www.w3schools.com/bootstrap4/default.asp

# Day 5 (Java Script) - https://www.w3schools.com/js/default.asp

