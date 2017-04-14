# Learn HTML5
Learn how to use HTML5 (from scratch) to build websites/web applications!

## Some history
In 1989,Tim Berners-Lee(working at CERN then) wrote a memo proposing an Internet-based hypertext systemwhere researchers can share documents. The browser and server software for this was created in the late 90's.

## What is HTML?
HTML (short for **H**yper**T**ext **M**arkup **L**anguage) is basically 
everything you see on the web everyday - every website uses HTML
(including GitHub, Google, Facebook, your aunt's blog, etc).
HTML is just the structure of the page - the texts, images, 
buttons **but** it doesn't include the beautifiers for your page(CSS, BootStrap).

## So HTML isn't pretty?
Plain HTML isn't but it can be made awesome looking (CSS, Bootstrap, etc) and clickable (JavaScript).

## Do I need to install anything to write html?
Theoretycally speaking - no,you don't. You can write on anything(even Word)
and save it in a .html extension. But truth is, if you want to make your life easier,
you should install some aditional software - Notepad, Visual Studio Code, gedit/vim/nano, Atom, Sublime, etc.
There are billions of text editors that will help you out but the one you need is probably Notepad++.
> https://notepad-plus-plus.org

## What resources do I need?
Most of the knowledge you'll need, will be in this guide. But in the IT world things are changing pretty fast. So make sure you educate yourself on new innovations, best practices and technologies. Make sure to check out our resources.md file where you will find some interesting guides, books and even more additional information.

## The basics 
<ul> 
    <li> The file you create should end with .html </li>
    <li> To play(TO DO: find a more suitable verb) the file you just open it in a web browser (Internet Explorer, Firefox, Chrome, Safari, Opera) </li>
    <li> HTML doesn't include styling of the page(that's what CSS is for) </li>
</ul>

So we write html in a text editor. Than how does our PC know it's a HTML file and not a poem or essaywe've written? Easy! HTML has it's own syntax( it's close to the English language, don't worry) and it's own extension - **_.html_**

## HTML head and body

Every html starts with the tag **<**__!DOCTYPE html>__ . This way the browser recognizes that this is a valid .html file.
You're probably wondering what a tag is.
<blockquote>A tag is 

```` html
<something>
````

it consists of an opening tag and usually (not every tag has one) a closing tag 

```` html 
</something>
````

Eveything that's between the opening and the closing tag is affected by the action this tag does. The 

```` html 
<!DOCTYPE html>
````

doesn't have a closing tag and neither does 

```` html 
<br>
````
 the tag for new line.  </blockquote>

After that our html has 

```` html 
<html> tag
````

The html tag has a closing tag:

```` html 
</html>
````

In between the html tags, our code looks just like a human - it starts with

```` html 
<head> some code here </head>
````

and after the head we have

```` html 
<body> some code here </body>
````

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
The easiest thing you can do in HTML is write a sentence. To do this you need to know one of the very basic and easy to use tags - the

```` html 
<p>
````

To write a sentence(or paragraph, word, number, etc), we simply put what we want to be shown on the screen between an opening and a closing tag.

```` html 
<p> Your text goes here </p>
````
 The paragraph tag should be used in the body. 

<b> Extra knowledge: </b> HTML doesn't add new lines when you press Enter in your editor. To add a new line, we use the 

```` html 
<br>
````

tag. N.B!The br tag has only an opening tag!! 
You can also write

```` html 
<hr>
````

which draws a horizontal line across your screen. It also doesn't have a closing tag.

## HTML Comments
Comments in any type of code (including HTML) are not shown in your browser. Usually they are used for writing some info about the code or they contain code itself (that code usually doesn't work). They are also great for Debugging (don't worry, you'll learn later what debugging is). Comments are written this way:

```` html
<!-- Write your comments here -->

<!-- This comment
is also legit -->
````
Note how the comments looks grayish. That's because the editor doesn't truly read them. If you create a blank html file (everything is in comments), the browser will open it but there won't be any content.

## So, you're probably wondering how all this knowledge goes together. Let's see

```` html 
<!DOCTYPE html>
<html>
        <head>
                <title> My first webpage! </title>
        </head>
        
        <body>
                <p> Hello world! <br> This will be shown in a new line </p>
        </body>

</html>
````
If you want, test this code. Also, don't forget to name your file with an .html extension.
When you're ready move on with this guide.

## Quotes
```` html
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
```` 
That's pretty straight-forward.

## Headings
Okay, so we have paragraphs but text isn't only sentences with same formatting. How can we change it? 
There is one easy way - CSS formatting, but for now we'll be using simple html tags and we'll learn about headings.

```` html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
````
Headings are just like paragraphs **BUT** they have different font sizes. h1 is the biggest heading and h6 is the smallest.
Search engines use the headings to index the structure and content of your web pages and users skim your pages by its headings. Also, by using headings the User Experience is better than if we only use paragraphs.

## Simple text formatting tags
```` html
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
````

The tags that you can see here format the text. They have closing tags!!! For example

```` html 
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
```` 
Try out this example for yourself and experiment a little. 

## Images
Up until now, we've been using only text. How about we add some pictures? <br>
In HTML pictures are added using:

```` html
<img src = "a_link_to_your_image"/> 
````
Note how the tag is closed - the tag is both an opening and a closing tag.
TO DO: Talk about relative/absolute links

But what should happen when our image doen't load? Or the device the user is using displays only text? We add an alt. It is a good practice to always have the alt attribute.

```` html
<img src = "a_link_to_your_image" alt="What your image is about"/> 
````

## Links
Now let's learn about links. For exammple, you want when a user clicks on a text, to open your other site.

```` html
<a href = "link_address_here"> The text the user should click here </a>
````

But have you noticed how some links open in the same tab and others for example open in a new tab. This is done with **the target attribute**.
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

In HTML, just like in the real world, our lists can be ordered or unordered.

### ordered list

```` html
<body>
        <ol>   <!-- Everything between the opening and the closing ol list is taken as a list item -->
            <li> list item 1 </li>  <!-- what is between the opening and closing li is considered a SINGLE list item -->
            <li> list item 2 </li>
            <li> list item N </li>
        </ol>
</body>

````
By default this list is shown with arabic numbers. 
We can change this with the type property (that's CSS and we'll talk soon about CSS).

### unordered list

```` html
<body>
        <ul>  
            <li> list item 1 </li>  
            <li> list item 2 </li>
            <li> list item N </li>
        </ul>
</body>

````
By default, the list item here are shown with circles in front. If we want to change that,we use the CSS list-style-type,which we'll talk about later.
        
