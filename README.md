## HTML Time. Let's Go.

## HTML Time. Let's Go.
### Editors
* Notepad/TextEdit 
* [Visual Studio Code]
* [Sublime Text]
* [CodePen Projects]
* [Glitch]
* [Notepad++]

### HTML Tag Structure
```html
<!doctype html>
<html>
    <head>
		<title>
			My Website
		</title>
	</head>
	<body>
		Hello, World!	
	</body>
</html>
```

 * [HTML Dog Tag List](https://www.htmldog.com/references/html/tags/)
  * [W3Schools Tag List](https://www.w3schools.com/tags/default.asp)
 * [Quackit HTML Tag List](https://www.quackit.com/html/tags/)

tags can have multiple attributes
<tag attribute="value1" attribute2="value2">Content of tag</tag>`

Image tag 
<img src="https://i.imgur.com/B9q0A.gif" />

adding attribute to the image
<img src="https://i.imgur.com/B9q0A.gif" alt="I could have danced all night" />

line breaks 
<hr> and <br>
hr - horizontal rule
<br> is a simple line break, all it does is split your paragraph up

two types of color
REG and HEX
RGB stands for Red, Green, and Blue
You can have the values 0 to 255
style="color: rgb(255,0,0)"

HEX colors is very similar. It consists of the hashtag sign #, and then 6 hexadecimal digits, which are 0123456789ABCDEF

style="color: #FF0000"


tables
<table>, <tr>, <th>, and <td>


Width and Height
There are two options you can use, the style attribute and the width and height attributes

<img src="https://i.imgur.com/4ihC2Yb.gif" />
<img src="https://i.imgur.com/4ihC2Yb.gif" width="600" height="800" />


style="property: value"

<img src="https://i.imgur.com/4ihC2Yb.gif" style="width: 600px; height: 800px" />

Borders

<img src="https://i.imgur.com/4ihC2Yb.gif" />

border="5"

<img src="https://i.imgur.com/4ihC2Yb.gif" style="border:5px solid black" />

solid , dotted, dashed, or double

<img src="https://i.imgur.com/4ihC2Yb.gif" style="border:5px dotted #ffcc00" />

<img src="https://i.imgur.com/4ihC2Yb.gif" style="border:10px ridge rgb(77, 145, 99); width: 300px" />

<img src="https://i.imgur.com/4ihC2Yb.gif" style="border:8px outset red" />	

<img src="https://i.imgur.com/4ihC2Yb.gif" style="border:3px double #333a21; height: 30px" />

Text Styles
<p style="text-align: center; font-weight: bold">This text is magnificent.</p>

text-align lets you align your text either center, left, or right
font-weight edits the weight in your text- values can be bold or normal,bolder,lighter 

<p style="font-family: Arial; font-style: italic">This text is magnificent.</p>

font-style, it can be normal, oblique, and italic

The <head> Tag
you can add <meta> tag inside head tag
metadata - denotes information of itself
  <meta> tag metadata about the HTML document.

<meta name="description" content="The best cooking website in the entire universe.  You're welcome.">

<meta http-equiv="refresh" content="30">

CSS
CSS is magical, and now you're gonna learn it.

its cascading style sheets
style attribute
<style> - to hold css and css defines style 

body { } this is a selector
The selector tells us what tag you're about to style.

Each portion of code selector { code } in CSS is called a declaration

selector { property: value; property: value; }


Classes and IDs and other Segregation
class
A class is actually an HTML attribute that you can name whatever you want.When you add a class, the user doesn't see it.
But, you can style specific classes to do what you want, instead of having all <p> tags be the same.

IDs
The only real difference between classes and IDs is that you can only have one of each ID.

<p id="special">This is so special that I want it uniquely styled forever.</p>

Id syntax
#special {

}

You can only use an ID once. IDs are more helpful when you're controlling the element with JavaScript, not styling, but that's something for another day.

Other Segregation

Let's say that you want to separate individual text in your paragraphs or sections on your page. Let's introduce 2 new tags

The <span> tag
he <span> tag is pretty invisible unless you style it. It's used to group inline-elements (so like a word in a paragraph), and it doesn't actually do anything unless you style or manipulate it with something else.

The <div> tag
Floating: With CSS float, a given element can be pushed to the left or right, allowing other elements to wrap around it.
An element with float affecting it will move as far to the left or right as it can.
Usually this means all the way to the left or right of the containing element.
sometimes, float just doesn't stop.
It has the potential to mess up your layouts and have things move around other things, and really just give you a headache

With the clear property! On the element(s) after any floated elements, make sure that they have clear: both; on them (we say both because it turns off both left and right floating).


float: left; or float: right
clear property

Positioning
absolute, relative, and fixed

In absolute positioning, the selected element will be placed in an exact location on the page, and moves with the page. So, in our example, the header could be placed at the top of the page and the footer at the bottom, but when you scroll, they will move with the page and they won't stay where they are supposed to. Some people like this, some don't. In our case, we won't use this.


In relative positioning, the selected element will be placed relative (fancy that) to its default position. 

fixed positioning is just like absolute positioning, except that once an element is placed in an exact location on the page, it is stuck there. A similar example is like a watermark on a video. It stays the same there, no matter what the content is.

top, bottom, left, and right to place it.

if you want header to be on top
position: absolute; and top: 0px;

if you have image 
position: relative; and left: 6px 

position: fixed; and right: 50px; and bottom: 50px.



margin is the space outside the content's border.


Padding is the space inside the content's border.



margin: 5px 10px 15px 0px;
top margin is 5px
right margin is 10px
bottom margin is 15px
left margin is 0px


margin: 15px 0px 5px;
top margin is 15px
right and left margins are 0px
bottom margin is 5px

margin: 5px 10px;
top and bottom margins are 5px
right and left margins are 10px

margin: 15px;
all four margins are 15px

padding: 5px 10px 15px 0px;

The <link> tag
<link rel="stylesheet" type="text/css" href="style.css">

HTML Comments
<!-- This is an HTML comment! -->

CSS comments
/* This is a comment in CSS! */


<button type="button">Click Me!</button>













