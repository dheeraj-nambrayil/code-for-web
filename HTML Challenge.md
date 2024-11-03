# What is HTML?

- HTML stands for Hyper Text Markup Language
- HTML describes the structure of a Web page


# HTML structure

[<b style="color:#00ff00;font-size:20px">Click here to view the structure of HTML documents</b>](index.html)
 <b style="color:#ff00ff;font-size:15px">&lt;!DOCTYPE html&gt; declaration defines that this document is an HTML5 document</b>
<b style="color:#ff00ff;font-size:15px">&lt;html&gt; element is the root element of an HTML page</b>
<b style="color:#ff00ff;font-size:15px">&lt;head&gt; element contains meta information about the HTML page</b>
<b style="color:#ff00ff;font-size:15px">&lt;title&gt; element specifies a title for the HTML page</b>
<b style="color:#ff00ff;font-size:15px">&lt;body&gt; element defines the document's body</b>
<b style="color:#ff00ff;font-size:15px">&lt;h1&gt; element defines a large heading</b>
<b style="color:#ff00ff;font-size:15px">&lt;p&gt; element defines a paragraph</b>

# HTML Element
## Tags
<ul>
<li>Anything in the angle brackets is a tag
<li>There are 2 types of tags : Opening and Closing aka Starting and Ending tags
<li><body>&lt;html&gt;, &lt;body&gt;, &lt;h1&gt; are examples of Opening Tags</body>
<li><body>&lt;/html&gt;, &lt;/body&gt;, &lt;/h1&gt; etc are examples of Closing Tags</body>
</ul>

## Elements
An element is defined by a start tag, some content, and an end tag
<body><h1 style="font-size:20px">&lt;<b style="color:red;font-sie:15px">tagname</b>&gt; Content goes here&lt;<b style="color:red;font-sie:15px">/tagname</b>&gt;</b></body>
The HTML **element** is everything from the start tag to the end tag
<div style="display:flex;text-decorations:none">Examples : &lt;<strong style="color:red">h1</strong>&gt;This is a heading&lt;<strong style="color:red">/h1</strong>&gt;, &lt;<strong style="color:red">p</strong>&gt;This is Paragraph &lt;<strong style="color:red">/p</strong>&gt; etc.</div>

![[images/Table.png.png]]

## Nested HTML Elements

HTML elements can be nested (this means that elements can contain other elements). All HTML documents consist of nested HTML elements. The following example contains four HTML elements (`<html>`, `<body>`, `<h1>` and `<p>`)
### Example

	<!DOCTYPE html>
	<html>
	<body>
	<h1>My First Heading</h1>
	<p>My first paragraph.</p>
	</body>
	</html>

The `<html>` element is the root element and it defines the whole HTML document. It has a start tag `<html>` and an end tag `</html>`. Then, inside the `<html>` element there is a `<body>` element:

	<body>  
	<h1>My First Heading</h1>  
	<p>My first paragraph.</p>  
	</body>

The `<body>` element defines the document's body. It has a start tag `<body>` and an end tag `</body>`. Then, inside the `<body>` element there are two other elements: `<h1>` and `<p>`:

	<h1>My First Heading</h1>  
	<p>My first paragraph.</p>

The `<h1>` element defines a heading. It has a start tag `<h1>` and an end tag `</h1>`:

	<h1>My First Heading</h1>

The `<p>` element defines a paragraph. It has a start tag `<p>` and an end tag `</p>`:

	<p>My first paragraph.</p>

## Empty HTML Elements

HTML elements with no content are called empty elements. The `<br>` tag defines a line break, and is an empty element without a closing tag:
### Example

	<p>This is a <br> paragraph with a line break.</p>

# HTML Attributes
HTML attributes provide additional information about HTML elements. All HTML elements can have **attributes**. Attributes provide **additional information** about elements. Attributes are always specified in **the start tag**. Attributes usually come in name/value pairs like: **name="value"**

## href Attribute

The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:

### Example

	<a href="https://www.w3schools.com">Visit W3Schools</a>

## src Attribute

The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:

### Example

	<img src="Table.png">

There are two ways to specify the URL in the `src` attribute:

**1. Absolute URL** - Links to an external image that is hosted on another website. Example: src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_light_color_272x92dp.png"

**2. Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name.
- If the URL begins without a slash, it will be relative to the current page. 
	- Example: src="Table.png". 
- If the URL begins with a slash, it will be relative to the domain.
	- Example: src="/images/Table.png".

It is almost always best to use relative URLs. They will not break if you change domain.
## The width and height Attributes

The `<img>` tag should also contain the `width` and `height` attributes, which specify the width and height of the image (in pixels):
### Example

	<img src="Table.png" width="500" height="600">

## The alt Attribute

The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the `src` attribute, or if the user uses a screen reader.

### Example

	<img src="Table.jpg" alt="Table on Opening tag and Closing tag">

## The style Attribute

The `style` attribute is used to add styles to an element, such as color, font, size, and more.

### Example

	<p style="color:red;">This is a red paragraph.</p>

## The lang Attribute

You should always include the `lang` attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

The following example specifies English as the language:

	<!DOCTYPE html>  
	<html lang="en">  
	<body>  
	...  
	</body>  
	</html>

Country codes can also be added to the language code in the `lang` attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

The following example specifies English as the language and United States as the country:

	<!DOCTYPE html>  
	<html lang="en-IN">  
	<body>  
	...  
	</body>  
	</html>

## The title Attribute

The `title` attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

### Example

	<p title="I'm a tooltip">This is a paragraph.</p>
## Suggestions on Attributes
- Use Lowercase Attributes
- Quote attribute values either in ' ' or " "
- 
# Structure of an HTML Document

![[Pasted image 20241102115328.png]]


# Learn HTML Using Notepad or Text Edit

Web pages can be created and modified by using professional HTML editors. However, for learning HTML we recommend a simple text editor like Notepad (PC), Text Edit (Mac), Vim, Nano, Xed, Pluma, Kate or any other text editors (Linux). Simple text editor is a good way to learn HTML.

# HTML Documents

All HTML documents must start with a document type declaration: `<!DOCTYPE html>`
The HTML document itself begins with `<html>` and ends with `</html>`
The visible part of the HTML document is between `<body>` and `</body>`
## Example

	<!DOCTYPE html>  
	<html>  
	<body>  
	<h1>My First Heading</h1>  
	<p>My first paragraph.</p>  
	</body>  
	</html>

# The <!DOCTYPE> Declaration

The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly. It must only appear once, at the top of the page (before any HTML tags). The `<!DOCTYPE>` declaration is not case sensitive.

# HTML Headings

HTML headings are titles or subtitles that you want to display on a webpage. HTML headings are defined with the `<h1>` to `<h6>` tags. `<h1>` defines the most important heading. `<h6>` defines the least important heading. 
Examples :

	<h1>Heading 1</h1>  
	<h2>Heading 2</h2>  
	<h3>Heading 3</h3>  
	<h4>Heading 4</h4>  
	<h5>Heading 5</h5>  
	<h6>Heading 6</h6>
<h1 style="font-size:50px;color:#00ff00">Output</h1>
<h1>Heading 1</h1>  
<h2>Heading 2</h2>  
<h3>Heading 3</h3>  
<h4>Heading 4</h4>  
<h5>Heading 5</h5>  
<h6>Heading 6</h6>
Browsers automatically add some white space (a margin) before and after a heading. Search engines use the headings to index the structure and content of your web pages. Users often skim a page by its headings. It is important to use headings to show the document structure.
	`<h1>` headings should be used for main headings, followed by `<h2>` headings, then the less important `<h3>`, and so on.

<b style="font-size:30px">Use HTML headings for <b style="font-size:30px;color:red">headings only</b>.
<b style="font-size:30px;color:#ff00ff">Don't use headings to make text BIG or bold</b></b>

Each HTML heading has a default size. However, you can specify the size for any heading with the `style` attribute, using the CSS `font-size` property:
### Example

	<h1 style="font-size:60px;">Heading 1</h1>

# HTML Paragraphs

HTML paragraphs are defined with the `<p>` tag. A paragraph always starts on a new line, and is usually a block of text.
### Example

	<p>This is a paragraph.</p>  
	<p>This is another paragraph.</p>

# HTML Displays
You cannot be sure how HTML will be displayed. Large or small screens, and resized windows will create different results. With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code. The browser will automatically remove any extra spaces and lines when the page is displayed.
### Example

	<p>  
	This paragraph  
	contains a lot of lines  
	in the source code,  
	but the browser  
	ignores it.  
	</p>  
  
	<p>  
	This paragraph  
	contains         a lot of spaces  
	in the source         code,  
	but the        browser  
	ignores it.  
	</p>

<p>  
This paragraph  
contains a lot of lines  
in the source code,  
but the browser  
ignores it.  
</p>  
  
<p>  
This paragraph  
contains         a lot of spaces  
in the source         code,  
but the        browser  
ignores it.  
</p>


# HTML Horizontal Rules

The `<hr>` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule. The `<hr>` element is used to separate content (or define a change) in an HTML page. The `<hr>` tag is an empty tag, which means that it has no end tag.

### Example

	<h1>This is heading 1</h1>  
	<p>This is some text.</p>  
	<hr>  
	<h2>This is heading 2</h2>  
	<p>This is some other text.</p>  
	<hr>

<h1>This is heading 1</h1>  
	<p>This is some text.</p>  
	<hr>  
	<h2>This is heading 2</h2>  
	<p>This is some other text.</p>  
	<hr>


# HTML Line Breaks

The HTML `<br>` element defines a line break. Use `<br>` if you want a line break (a new line) without starting a new paragraph. The `<br>` tag is an empty tag, which means that it has no end tag.
### Example

	<p>This is<br>a paragraph<br>with line breaks.</p>

<p>This is<br>a paragraph<br>with line breaks.</p>

# The Poem Problem and `<pre>` element

This poem will display on a single line:
### Example

	<p>  
	  My Bonnie lies over the ocean.  
	  
	  My Bonnie lies over the sea.  
	  
	  My Bonnie lies over the ocean.  
	  
	  Oh, bring back my Bonnie to me.  
	</p>

<p>  
  My Bonnie lies over the ocean.  
  
  My Bonnie lies over the sea.  
  
  My Bonnie lies over the ocean.  
  
  Oh, bring back my Bonnie to me.  
</p>
## Pre element
The HTML `<pre>` element defines preformatted text. The text inside a `<pre>` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.

### Example

	<pre>  
	  My Bonnie lies over the ocean.  
	  
	  My Bonnie lies over the sea.  
	  
	  My Bonnie lies over the ocean.  
	  
	  Oh, bring back my Bonnie to me.  
	</pre>

<pre>  
  My Bonnie lies over the ocean.  
  
  My Bonnie lies over the sea.  
  
  My Bonnie lies over the ocean.  
  
  Oh, bring back my Bonnie to me.
  </pre>
  
# HTML Links

HTML links are defined with the `<a>` tag:

### Example

	<a href="https://www.w3schools.com">This is a link</a>

The link's destination is specified in the `href` attribute. Attributes are used to provide additional information about HTML elements.
# HTML Images

HTML images are defined with the `<img>` tag.

The source file (`src`), alternative text (`alt`), `width`, and `height` are provided as attributes:

### Example

<img src="../Images/Table.png'" alt="Table on Tags and Elements" width="104" height="142">



# HTML Styles
The HTML `style` attribute is used to add styles to an element, such as color, font, size, and more. 
### Example

	<p>I am normal</p>
	<p style="color:red;">I am red</p>
	<p style="color:blue;">I am blue</p>
	<p style="font-size:50px;">I am big</p>

<p>I am normal</p>
<p style="color:red;">I am red</p>
<p style="color:blue;">I am blue</p>
<p style="font-size:50px;">I am big</p>

## The HTML Style Attribute

Setting the style of an HTML element, can be done with the `style` attribute. The HTML `style` attribute has the following syntax:

	<_tagname_ style="_property_:_value;_">

The _**property**_ is a CSS property. The _**value**_ is a CSS value.

## Background Color

The CSS `background-color` property defines the background color for an HTML element.

### Example

Set the background color for a page to powderblue:

	<body style="background-color:powderblue;">  
	  
	<h1>This is a heading</h1>  
	<p>This is a paragraph.</p>  
	  
	</body>

<body style="background-color:powderblue;">  
  
<h1>This is a heading</h1>  
<p>This is a paragraph.</p>  
  
</body>

### Example

Set background color for two different elements:
	
	<body>  
	  
	<h1 style="background-color:powderblue;">This is a heading</h1>  
	<p style="background-color:tomato;">This is a paragraph.</p>  
	  
	</body>


<body>  
  
<h1 style="background-color:powderblue;">This is a heading</h1>  
<p style="background-color:tomato;">This is a paragraph.</p>  
  
</body>

## Text Color

The CSS `color` property defines the text color for an HTML element:

### Example

	<h1 style="color:blue;">This is a heading</h1>  
	<p style="color:red;">This is a paragraph.</p>

<h1 style="color:blue;">This is a heading</h1>  
<p style="color:red;">This is a paragraph.</p>

## Fonts

The CSS `font-family` property defines the font to be used for an HTML element:

### Example

	<h1 style="font-family:verdana;">This is a heading</h1>  
	<p style="font-family:courier;">This is a paragraph.</p>

<h1 style="font-family:verdana;">This is a heading</h1>  
<p style="font-family:courier;">This is a paragraph.</p>


## Text Size

The CSS `font-size` property defines the text size for an HTML element:

### Example

	<h1 style="font-size:300%;">This is a heading</h1>  
	<p style="font-size:160%;">This is a paragraph.</p>

<h1 style="font-size:300%;">This is a heading</h1>  
<p style="font-size:160%;">This is a paragraph.</p>


## Text Alignment

The CSS `text-align` property defines the horizontal text alignment for an HTML element:

### Example

	<h1 style="text-align:center;">Centered Heading</h1>  
	<p style="text-align:center;">Centered paragraph.</p>

<h1 style="text-align:center;">Centered Heading</h1>  
<p style="text-align:center;">Centered paragraph.</p>


# HTML Text Formatting

HTML contains several elements for defining text with a special meaning.

	<p><b>This text is bold</b></p>
	<p><i>This text is italic</i></p>
	<p>This is<sub> subscript</sub> and <sup>superscript</sup></p>

<p><b>This text is bold</b></p>
<p><i>This text is italic</i></p>
<p>This is<sub> subscript</sub> and <sup>superscript</sup></p>
## HTML Formatting Elements

Formatting elements were designed to display special types of text:

- `<b>` - Bold text
- `<strong>` - Important text
- `<i>` - Italic text
- `<em>` - Emphasized text
- `<mark>` - Marked text
- `<small>` - Smaller text
- `<del>` - Deleted text
- `<ins>` - Inserted text
- `<sub>` - Subscript text
- `<sup>` - Superscript text

## HTML `<b>` and `<strong>` Elements

### `<b>`
The HTML `<b>` element defines bold text, without any extra importance.

#### Example

	<b>This text is bold</b>

<b>This text is bold</b>


### `<strong>`
The HTML `<strong>` element defines text with strong importance. The content inside is typically displayed in bold.

#### Example

	<strong>This text is important!</strong>

<strong>This text is important!</strong>

## HTML `<i>` and `<em>` Elements
### `<i>`
The HTML `<i>` element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic. The `<i>` tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.

#### Example

	<i>This text is italic</i>

<i>This text is italic</i>

### `<em>`
The HTML `<em>` element defines emphasized text. The content inside is typically displayed in italic. A screen reader will pronounce the words in `<em>` with an emphasis, using verbal stress.
#### Example

	<em>This text is emphasized</em>

<em>This text is emphasized</em>

## HTML `<small>` Element

The HTML `<small>` element defines smaller text:

### Example

	<small>This is some smaller text.</small>  

<small>This is some smaller text.</small>  
## HTML `<mark>` Element

The HTML `<mark>` element defines text that should be marked or highlighted:

### Example

	<p>Do not forget to buy <mark>milk</mark> today.</p>  

<p>Do not forget to buy <mark>milk</mark> today.</p>  

## HTML `<del>` Element

The HTML `<del>` element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:

### Example

	<p>My favorite color is <del>blue</del> red.</p>  

<p>My favorite color is <del>blue</del> red.</p>  

## HTML `<ins>` Element

The HTML `<ins>` element defines a text that has been inserted into a document. Browsers will usually underline inserted text:

### Example

	<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>  

<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>  

## HTML `<sub>` Element

The HTML `<sub>` element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:
### Example

	<p>This is <sub>subscripted</sub> text.</p>  

<p>This is <sub>subscripted</sub> text.</p>  



## HTML `<sup>` Element

The HTML `<sup>` element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW <sup>[1]</sup>:

### Example

	<p>This is <sup>superscripted</sup> text.</p>

<p>This is <sup>superscripted</sup> text.</p>
# HTML Quotation and Citation Elements

### Example

<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>

## HTML `<blockquote>` for Quotations

The HTML `<blockquote>` element defines a section that is quoted from another source. Browsers usually indent `<blockquote>` elements.

### Example

	<p>Here is a quote from WWF's website:</p>  
	<blockquote cite="http://www.worldwildlife.org/who/index.html">  
	For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.  
	</blockquote>

<p>Here is a quote from WWF's website:</p>

<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>
## HTML `<q>` for Short Quotations

The HTML `<q>` tag defines a short quotation. Browsers normally insert quotation marks around the quotation.

### Example

	<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>

<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
## HTML `<abbr>` for Abbreviations

The HTML `<abbr>` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM". Marking abbreviations can give useful information to browsers, translation systems and search-engines. Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element. 

### Example

	<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
## HTML `<address>` for Contact Information

The HTML `<address>` tag defines the contact information for the author/owner of a document or an article. The contact information can be an email address, URL, physical address, phone number, social media handle, etc. The text in the `<address>` element usually renders in _italic,_ and browsers will always add a line break before and after the `<address>` element.

### Example

	<address>  
	Written by John Doe.<br>  
	Visit us at:<br>  
	Example.com<br>  
	Box 564, Disneyland<br>  
	USA  
	</address>

<address>  
Written by John Doe.<br>  
Visit us at:<br>  
Example.com<br>  
Box 564, Disneyland<br>  
USA  
</address>

## HTML `<cite>` for Work Title

The HTML `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.). A person's name is not the title of a work. The text in the `<cite>` element usually renders in _italic_.

### Example

	<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

## HTML `<bdo>` for Bi-Directional Override

BDO stands for Bi-Directional Override. The HTML `<bdo>` tag is used to override the current text direction.

### Example

	<bdo dir="rtl">This text will be written from right to left</bdo>

<bdo dir="rtl">This text will be written from right to left</bdo>


# HTML Comments

HTML comments are not displayed in the browser, but they can help document your HTML source code.
## HTML Comment Tag

You can add comments to your HTML source by using the following syntax:
<!-- Write your comments here -->

Notice that there is an exclamation point (!) in the start tag, but not in the end tag. Comments are not displayed by the browser, but they can help document your HTML source code.
## Add Comments

With comments you can place notifications and reminders in your HTML code. Comments can be used to hide content. This can be helpful if you hide content temporarily. You can also hide more than one line. Everything between the `<!--` and the `-->` will be hidden from the display. Comments are also great for debugging HTML, because you can comment out HTML lines of code, one at a time, to search for errors. Comments can be used to hide parts in the middle of the HTML code.

### Example
<!-- This is a comment -->  
  
<p>This is a paragraph.</p>  
  
<!-- Remember to add more information here -->



### Example
<p>This is a paragraph.</p>  
  
<!-- <p>This is another paragraph </p> -->  
  
<p>This is a paragraph too.</p>

### Example
<p>This is a paragraph.</p>  
<!--  
<p>Look at this cool image:</p>  
<img border="0" src="pic_trulli.jpg" alt="Trulli">  
-->  
<p>This is a paragraph too.</p>
### Example
Hide a part of a paragraph:

<p>This <!-- great text --> is a paragraph.</p>
# HTML Colors

HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
## Color Names

In HTML, a color can be specified by using a color name:
- Tomato
- Orange
- DodgerBlue
- MediumSeaGreen
- Gray
- SlateBlue
- Violet
- LightGray
## Background Color

You can set the background color for HTML elements:
### Example

	<h1 style="background-color:DodgerBlue;">Hello World</h1>  
	<p style="background-color:Tomato;">Lorem ipsum...</p>

<h1 style="background-color:DodgerBlue;">Hello World</h1>  
<p style="background-color:Tomato;">Lorem ipsum...</p>
## Text Color

### Example

	<h1 style="color:Tomato;">Hello World</h1>  
	<p style="color:DodgerBlue;">Lorem ipsum...</p>  
	<p style="color:MediumSeaGreen;">Ut wisi enim...</p>

<h1 style="color:Tomato;">Hello World</h1>  
<p style="color:DodgerBlue;">Lorem ipsum...</p>  
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>

## Border Color

You can set the color of borders:
### Example

	<h1 style="border:2px solid Tomato;">Hello World</h1>  
	<h1 style="border:2px solid DodgerBlue;">Hello World</h1>  
	<h1 style="border:2px solid Violet;">Hello World</h1>

<h1 style="border:2px solid Tomato;">Hello World</h1>  
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>  
<h1 style="border:2px solid Violet;">Hello World</h1>
## Color Values

In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

The following three `<div>` elements have their background color set with RGB, HEX, and HSL values: `rgb(255, 99, 71), #ff6347, hsl(9, 100%, 64%)`

The following two `<div>` elements have their background color set with RGBA and HSLA values, which add an Alpha channel to the color (here we have 50% transparency): `rgba(255, 99, 71, 0.5), hsla(9, 100%, 64%, 0.5)`
### Example

	<h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>  
	<h1 style="background-color:#ff6347;">#ff6347</h1>  
	<h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>    
	<h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>  
	<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>

<h1 style="background-color:rgb(255, 99, 71);text-align:center">rgb(255, 99, 71)</h1>  
<h1 style="background-color:#ff6347;text-align:center">#ff6347</h1>  
<h1 style="background-color:hsl(9, 100%, 64%);text-align:center">hsl(9, 100%, 64%)</h1>    
<h1 style="background-color:rgba(255, 99, 71, 0.5);text-align:center">rgba(255, 99, 71, 0.5)</h1>  
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);text-align:center">hsla(9, 100%, 64%, 0.5)</h1>

