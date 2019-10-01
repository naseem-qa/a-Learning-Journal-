# JavaScript is written in plain text, just like HTML and CSS, so you do not
need any new tools to write a script. This example adds a greeting into an
HTML page. The greeting changes depending on the time of day.
1. Create a folder to put the
example in called cOl, then start
up your favorite code editor, and
enter the text to the right.
A JavaScript fi le is just a
text file (like HTML and CSS
files are) but it has a . j s file
extension, so save this file with
the name add-content . j s
1. Get the CSS and images for
this example from the website
that accompanies the book:
www.javascriptbook. com
To keep the files organized, in
the same way that CSS files
often live in a folder ca lled
styles or css, your JavaScript
files can live in a folder called
scripts,javascript,orjs.
In this case, save your file in a
folder called j s
9 In your code editor, enter the
HTML shown on the left. Save
this file with the name
add-content.html
The HTML <script> element is
used to load the JavaScript file
into the page. It has an attribute
called src, whose value is the
path to the script you created.
This tells the browser to find and
load the script file (just like the
src attribute on an <img> tag).
1. Open the HTML file in your
browser. You should see that the
JavaScript has added a greeting
(in this case, Good Afternoon!) to
the page. (These greetings are
coming from the JavaScript file;
they are not in the HTML file.)
Please note: Internet Explorer
sometimes prevents JavaScript
running when you open a page
stored on your hard drive. If this
affects you, please try Chrome,
Firefox, Opera, or Safari instead.
f) Once you have tried the
example in your browser, view
the source code for the page.
(This option is usually under the
View, Tools or Develop menu of
the browser.)
Show Page Source '\:XU
1. The source of the web page
does not actually show the new
element that has been added
into the page; it just shows the
link to the JavaScript file.
As you move through the book,
you will see most of the scripts
are added just before the closing
</body> tag (this is often
considered a better place to
put your scripts).
2. Final ly, try opening the
HTML file, removing the src
attribute from the opening
<script> tag, and adding the
new code shown on the left
between the opening <script>
tag and the closing </script>
tag. The s re attribute is no
longer needed because the
JavaScript is in the HTML page.
1. Open the HTML file in your
web browser and the welcome
greeting is written into the page