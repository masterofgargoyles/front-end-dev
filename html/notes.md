start tag <html> and an end tag </html>.

The <body> element defines the document's body.


The <br> tag defines a line break, and is an empty element without a closing tag:
<p>This is a <br> paragraph with a line break.</p>


The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:
<a href="https://www.w3schools.com">Visit W3Schools</a>


<img src="img_girl.jpg">


The title attribute defines some extra information about an element.
<p title="I'm a tooltip">This is a paragraph.</p>

<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a> --- Recomended with double quotes in href

HTML headings are defined with the <h1> to <h6> tags.
<h1> defines the most important heading. <h6> defines the least important heading.


Each HTML heading has a default size. However, you can specify the size for any heading with the style attribute, using the CSS font-size property:
<h1 style="font-size:60px;">Heading 1</h1>


The HTML <pre> element defines preformatted text.
The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:
<pre>
  My Bonnie lies over the ocean.
  My Bonnie lies over the sea.
  My Bonnie lies over the ocean.
  Oh, bring back my Bonnie to me.
</pre>


The HTML <mark> element defines text that should be marked or highlighted:
<p>Do not forget to buy <mark>milk</mark> today.</p>


The HTML <del> element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:
<p>My favorite color is <del>blue</del> red.</p>


The HTML <sub> element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:
<p>This is <sub>subscripted</sub> text.</p>


The HTML <sup> element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:
<p>This is <sup>superscripted</sup> text.</p>


Use target="_blank" to open the linked document in a new browser window or tab:
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>


Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email):
<a href="mailto:someone@example.com">Send email</a>


To add a favicon to your website, either save your favicon image to the root directory of your webserver, or create a folder in the root directory called images, and save your favicon image in this folder. A common name for a favicon image is "favicon.ico".
<!DOCTYPE html>
<html>
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>


You can add a caption that serves as a heading for the entire table.
Monthly savings
Month	|| Savings
January	|| $100
February||	$50
To add a caption to a table, use the <caption> tag


<div>	Defines a section in a document (block-level)
<span>	Defines a section in a document (inline)


The HTML <noscript> tag defines an alternate content to be displayed to users that have disabled scripts in their browser or have a browser that doesn't support scripts:
<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>
<noscript>Sorry, your browser does not support JavaScript!</noscript>


To create a responsive website, add the following <meta> tag to all your web pages:
<meta name="viewport" content="width=device-width, initial-scale=1.0">


The <kbd> element defines keyboard input
The <samp> element defines sample output from a computer program
The <code> element defines a piece of computer code
The <var> element defines a variable in programming or in a mathematical expression
The <pre> element defines preformatted text


The action attribute defines the action to be performed when the form is submitted.
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>


