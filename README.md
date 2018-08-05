# Learn HTML5
Learn how to use HTML5 (from scratch) to build websites/web applications! No previous knowledge needed.

## Some history
In 1989, Tim Berners-Lee(working at CERN then), wrote a memo proposing an Internet-based hypertext system where researchers can share documents. The browser and server software for this was created in the late 90's and later became known as the World Wide Web. The WWW was functioning using a language that Berners-Lee wrote - HTML.

## What is HTML?
HTML (short for **H**yper**T**ext **M**arkup **L**anguage) is basically
everything you see on the web everyday - every website uses HTML
(including GitHub, Google, Facebook, your aunt's blog, etc).
HTML is just the structure of the page - the texts, images,
buttons **but** it doesn't include the beautifiers for your page(CSS, BootStrap)
although they can be inserted into the html file itself.

## So HTML isn't pretty?
Plain HTML isn't but it can be made awesome looking using styles and libraries(CSS, Bootstrap, etc) and clickable (JavaScript).

## Do I need to install anything to write html?
Theoretically speaking - no, you don't, because you probably already have everything needed.
You can write on anything(even Word) and save it in a .html extension.
But truth is, if you want to make your life easier,
you should install some aditional software - Notepad, Visual Studio Code, gedit/vim/nano, Atom, Sublime, etc.
There are billions of text editors that will help you out but the one you need is probably Notepad++.
> https://notepad-plus-plus.org <br>
> https://github.com/dwyl/dev-setup

## What resources do I need?
Most of the knowledge you'll need, will be in this guide. But in the IT world things are changing pretty fast. So make sure you educate yourself on new innovations, best practices and technologies. Make sure to check out our resources.md file where you will find some interesting guides, books and even more additional information.

## The basics
<ul>
    <li> The file you create should end with .html </li>
    <li> To play(TO DO: find a more suitable verb) the file you just open it in a web browser (Internet Explorer, Firefox, Chrome, Safari, Opera) </li>
    <li> HTML doesn't include styling of the page(that's what CSS is for) </li>
</ul>

Okay, so we write html in a text editor. Then how does our PC know it's a HTML file and not a poem or essay we've written?
Easy! HTML has it's own syntax( it's very close to the English language, don't worry) and it's own extension - **_.html_**.

## HTML head and body

Every html starts with the tag
``` html
<!DOCTYPE html>
```
This way the browser recognizes that this is a valid .html file.
You're probably wondering what a tag is.    <br>
A tag is

``` html
<something here inside>
```

it consists of an opening tag and usually (not every tag has one) a closing tag:

``` html
</something that was in the opening tag>
```

Eveything that's between the opening and the closing tag is affected by the action this tag does. The

``` html
<!DOCTYPE html>
```

doesn't have a closing tag and neither does

``` html
<br>
```
Br is the tag for new line.  

After that our html has

``` html
<html> tag
```

The html tag has a closing tag:

``` html
</html>
```

In between the html tags, our code looks just like a human - it starts with

``` html
<head> some code here </head>
```

and after the head we have

``` html
<body> some code here </body>
```

 Between the head tags we place the head elements.

### The following elements go inside the head element:
<blockquote>
title = what is shown at the tab in your browser <br>
style = here we put rules for styling (in another language called CSS) <br>
link = links <br>
meta =meta information like encoding <br>
script = actions for you page <br>
</blockquote>

Most of the things you will want to add (like sentences, pictures, etc)
will be added in the body tag. Now lets learn more about them.

## Paragraphs
The easiest thing you can do in HTML is write a sentence.
To do this you need to know one of the very basic and easy to use tags - the

``` html
<p>
```

To write a sentence(or paragraph, word, number, etc), we simply put what we want to be shown
on the screen between an opening and a closing tag.

``` html
<p> Your text goes here </p>
```
 The paragraph tag should be used in the body.

<b> Extra knowledge: </b> HTML doesn't add new lines
when you press Enter in your editor. To add a new line, we use the

``` html
<br>
```

tag. **N.B! The br tag has only an opening tag!! (this kind of tags are known as self-closing)** <br>
You can also write

``` html
<hr>
```

which draws a horizontal line across your screen. It also doesn't have a closing tag
and is usually used to visually show the user that
this are 2 different sections of the page.

## HTML Comments
Comments in any type of code (including HTML) are not shown in your browser.
Usually they are used for writing some info about the code or
they contain some code itself (that code usually doesn't work).
They are also great for Debugging (don't worry, you'll learn later what debugging is).
Comments are written this way:

``` html
<!-- Write your comments here -->

<!-- This comment
is also legit -->
```
Note how the comments looks grayish. That's because the editor doesn't truly read them.
If you create a blank html file (everything is in comments), the browser will open it but there won't be any content.

## So, you're probably wondering how all this knowledge goes together. Let's see

``` html
<!DOCTYPE html>
<html>
        <head>
                <title> My first webpage! </title>
        </head>

        <body>
                <p> Hello world! <br> This will be shown in a new line </p>
        </body>

</html>
```
If you want, test this code. Also, don't forget to name your file with an .html extension.
When you're ready move on with this guide.

## Quotes

``` html
<q> Use q for short quotes </q>
<blockquote>
            The blockquote tag should be used when we want to talk
            about some long quote that is quoted from another source.
</blockquote>

<blockquote cite="link to where you took the quote from">
                your very long
                and interesting
                probably
                quote.
</blockquote>
```

That's pretty straight-forward.No need for explaining.

## Headings
Okay, so we have paragraphs but the text we usually write and read
isn't only sentences with the same formatting.We have some sentences that are bigger and darker, some that
are really small, etc. How can we do this in HTML?
There is one easy way - CSS formatting, but for now we'll be using simple html tags and we'll learn about headings.

``` html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```

Headings are just like paragraphs **BUT** they have different font sizes. h1 is the biggest heading and h6 is the smallest.
Search engines use the headings to index the structure and content of your web pages and users skim your pages by its headings. Also, by using headings the User Experience is better than if we only use paragraphs.

## Simple text formatting tags
``` html
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Small text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
```

The tags that you can see here format the text. They have closing tags!!! For example

``` html
<!DOCTYPE html>
<html>
        <head>
                <title> My first webpage! </title>
        </head>

        <body>
                <h1> This will be the biggest header </h1>
                <p> Hello world! <br> <b>This will be bold and on new line </b>
                <br> <i> This will be italic and on new line </i>
                </p>
                <h6> This will be a very small heading </h6>
        </body>

</html>
```
Try out this example for yourself and experiment a little. And remember - everything between the opening and the closing tag is affected so don't forget to close your tags.

## Images
Up until now, we've been using only text. How about we add some pictures? <br>
In HTML pictures are added using:

``` html
<img src = "a_link_to_your_image"/>
```
Note how the tag is closed - the tag is both an opening and a closing tag.
TO DO: Talk about relative/absolute links

But what should happen when our image doen't load?
Or the device the user is using displays only text?
We add an alt attribute. It is a good practice to always have the alt attribute.

``` html
<img src = "a_link_to_your_image" alt="What your image is about"/>
```

## Links
Now let's learn about links. For exammple, you want when a user clicks on a text, to open your other site.

``` html
<a href = "link_address_here"> The text the user should click here </a>
```

But have you noticed how some links open in the same tab and others for example open in a new tab? This is done with **the target attribute**.
The target attribute specifies where to open the linked document and it can have one of the following values:
<blockquote>
_blank - Opens the linked document in a new window or tab <br>
_self - Opens the linked document in the same window/tab as it was clicked (this is default) <br>
_parent - Opens the linked document in the parent frame <br>
_top - Opens the linked document in the full body of the window  <br>
framename - Opens the linked document in a named frame <br>
</blockquote>

That's pretty much all about links. Not that hard, right?

## Lists
Lets's say you want to go shopping. Do you write long paragraphs about what you want to buy?
Probably not. You use lists. And HTML has lists too.
In HTML, just like in the real world, our lists can be either ordered or unordered.

### ordered lists

``` html
<body>
        <ol>   <!-- Everything between the opening and the closing ol list is taken as a list item -->
            <li> list item 1 </li>  <!-- what is between the opening and closing li is considered a SINGLE list item -->
            <li> list item 2 </li>
            <li> list item N </li>
        </ol>
</body>

```
By default this list is shown with arabic numbers.
We can change this with the type property (that's CSS and we'll talk soon about CSS).

### unordered lists

``` html
<body>
        <ul>  
            <li> list item 1 </li>  
            <li> list item 2 </li>
            <li> list item N </li>
        </ul>
</body>

```
By default, the list item here are shown with circles in front. If we want to change that,
we use the CSS **list-style-type**, which we'll talk about later.

## Tables
To represent data, we sometimes use tables (Google Spreadsheets, Excel, etc).
HTML has tables too and they are quite easy to use.

``` html
<table>
  <tr>
    <th>table row 1 first square</th>
    <th>table row 1 second square</th>
  </tr>
  <tr>
    <td>table row 2 first square</td>
    <td>table row 2 second square</td>
    <td>50</td>
  </tr>
  <tr>
    <td>table row 2 first square</td>
    <td>table row 2 second square</td>
  </tr>
</table>
```

An HTML table is defined with the table tag.
Each table row is defined with the tr tag. A table header is defined with the <th> tag.
By default, table headings are bold and centered. A table data/cell is defined with the td tag.

## Block and Inline Element´s
For us to unsderstand the div and span element´s we must know this:
Every HTML element has a default display value depending on what type of element it is.
The default display value for most elements is _block_ or _inline_.

## Block-level Element
A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).
```html
<p>The paragraph is a block-level element.<p>
```
Examples of block-level elements:
div
h1 - h6
p
form

## Inline Element
An inline element occupies only the space bounded by the tags that define the inline element.
Generally, inline elements may contain only data and other inline elements.
The following example demonstrates the inline element's influence:
```html
<p>This <span>span</span> is an inline element</p>
```

## Div Element
The div element belongs to the block-level group, often used as a container for other HTML elements.
The div element has no required attributes, but both style and class are common.
When used together with CSS, the div element can be used to style blocks of content,
as we can see in the example below:

``` html
<div style="background-color:black;color:white;padding:20px;">
  <h2>Lisbon</h2>
  <p>Lisbon is the capital city of Portugal.
  26.7% of the total population of Portugal lives in the Lisbon Metropolitan Area.</p>  
</div>
```

## Span Element
The span element is a generic inline container for phrasing content, which does not inherently represent anything.
It can be used to group elements for styling purposes (using the class or id attributes),
or because they share attribute values, such as lang.
The span is very much like a div element, but div is a block-level element whereas a span is an inline element.

```html
<h1>My super <span style="color:red">Important</span> Heading</h1>
```

## Classes
Using the html class attribute makes it possible to define equal styles,
for elements with the same class name.

```html
<!DOCTYPE html>
<html>
<head>
<style>
div.cities {
    background-color: black;
    color: white;
    margin: 20px 0 20px 0;
    padding: 20px;
}
</style>
</head>
<body>

<div class="cities">
<h2>London</h2>
<p>London is the capital of England.</p>
</div>

<div class="cities">
<h2>Kingston</h2>
<p>Kingston is the capital city of Jamaica.</p>
</div>

<div class="cities">
<h2>Tokyo</h2>
<p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area,
and the most populous metropolitan area in the world.</p>
</div>

</body>
</html>
```
The html class attribute can also be used for inline elements:

```html
<!DOCTYPE html>
<html>
<head>
<style>
span.note {
    font-size: 110%;
    color: blue;
}
</style>
</head>
<body>

<h1>My Ultra <span class="note">Important</span> Heading</h1>
<p>This is some random but <span class="note">important</span> text.</p>

</body>
</html>
```

## Buttons
The button tag defines a clickable button.
```html
<button type="button">Click Please</button>
```
These buttons work and behave in exactly the same way as our counterparts above.
In addition to submitting the form, you can make them disabled, add an accesskey or even specify a tabindex.
The coolest thing about the <button> tag is that you can put useful HTML elements inside them, like images:
```html
<button type="submit"><img src="" alt="" /> Submit</button>
```
"Buttons created with the  **BUTTON** element function just like buttons created with the **INPUT** element,
but they offer richer rendering possibilities: the **BUTTON** tag may have content.
For example:
a  **BUTTON** element that contains an image functions like and may resemble an **INPUT** element whose type is set to “image”,
but the  **BUTTON** element type allows content." W3
```html
<div class="buttons">
    <button type="submit" class="positive">
        <img src="/images/icons/tick.png" alt=""/>
        Save
    </button>    <a href="/password/reset/">
        <img src="/images/icons/textfield_key.png" alt=""/>
        Change Password
    </a>    <a href="#" class="negative">
        <img src="/images/icons/cross.png" alt=""/>
        Cancel
    </a>
</div>
```
*Tip*: Always specify the type attribute for a button element.
Different browsers use different default types for the button element.

## Styles and Sizes (With Bootstrap)
Great Work!
As we know, this is where we would start using only CSS to style and size our buttons..? No!
We are introducing you to Bootstrap (the most popular HTML, CSS, and JavaScript framework for developing responsive,
mobile-first web sites) because it´s an easier way to get the job done!

### Do you prefer larger or smaller buttons?
Add .btn-lg (large), .btn-md(medium), .btn-sm(small), or .btn-xs(extra-small) for additional sizes.

```html
<button type="button" class="btn btn-primary btn-lg">Large</button>
<button type="button" class="btn btn-primary btn-md">Medium</button>
<button type="button" class="btn btn-primary btn-sm">Small</button>
<button type="button" class="btn btn-primary btn-xs">XSmall</button>
```
Create block level buttons — those that span the full width of a parent—by adding *.btn-block*:

```html
<button type="button" class="btn btn-primary btn-lg btn-block">Block level button</button>
```

After you decide the size of your buttons it´s time to style them!
Bootstrap provides different styles of buttons:

+ Basic
+ Default
+ Primary
+ Success
+ Info
+ Warning
+ Danger
+ Link

```html
<!-- Provides extra visual weight and identifies the primary action in a set of buttons -->
<button type="button" class="btn btn-primary">Primary</button>
<!-- Secondary, outline button -->
<button type="button" class="btn btn-secondary">Secondary</button>
<!-- Indicates a successful or positive action -->
<button type="button" class="btn btn-success">Success</button>
<!-- Contextual button for informational alert messages -->
<button type="button" class="btn btn-info">Info</button>
<!-- Indicates caution should be taken with this action -->
<button type="button" class="btn btn-warning">Warning</button>
<!-- Indicates a dangerous or potentially negative action -->
<button type="button" class="btn btn-danger">Danger</button>
<!-- Deemphasize a button by making it look like a link while maintaining button behavior -->
<button type="button" class="btn btn-link">Link</button>
```
### Outline buttons
Replace the default modifier classes with the *.btn-outline-* ones to remove all background images and colors on any button.
```html
<button type="button" class="btn btn-outline-primary">Primary</button>
<button type="button" class="btn btn-outline-secondary">Secondary</button>
<button type="button" class="btn btn-outline-success">Success</button>
<button type="button" class="btn btn-outline-info">Info</button>
<button type="button" class="btn btn-outline-warning">Warning</button>
<button type="button" class="btn btn-outline-danger">Danger</button>
```

###  Great resources to learn HTML5

  https://developer.mozilla.org/en-US/docs/Web/HTML/Element
  
