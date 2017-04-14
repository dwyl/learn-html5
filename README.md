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

## So HTML ain't pretty?
Plain HTML ain't but it can be made awesome looking (CSS, Bootstrap) and clickable (JS).

## Do I need to install anything to write html?
Theoretycally speaking - no,you don't. You can write on anything(even Word)
and save it in a .html extension. But truth is, if you want to make your life easier,
you should install some aditional software - Notepad, Visual Studio Code, gedit/vim/nano, Atom, Sublime, etc.
There are billions of text editors that will help you out but the one you need is probably Notepad++.
> https://notepad-plus-plus.org

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
<blockquote>
The following elements can go inside the head element:

title = what is shown at the tab in your browser
style = here we put rules for styling (in another language called CSS)
link = links
meta =meta information like encoding
script = actions for you page
</blockquote>
Most of the things you will want to add(like sentences, pictures, etc) will be added in the body tag. Now leté explore more about them.

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
Comments in any type of code (including HTML) are not shown in your browser. 
TO BE DONE

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
If you want,test this code. Also, don't forget to name your file with an .html extension.
## Syntax
<ul> 
<li>  Paragraph 
<li>  New line
<li> Horizontal line

# TO DO:
<ul> 
<li> Create full syntax for HTML5
<li> Creat a resources .md file
<li> Add a cheatsheet
<li> Add few sections about styling and scripts
<li> Talk about WWW, Domains, How the internet works, etc 
<li> Differences between HTML and HTML5
<li> Bootstrap
</ul>

# Syntax_ TO DO:
<ul>
<li> paragraphs
<li> headings
<li> links
<li> div and span
<li> classes
<li> lists(ol,ul)
<li> tables
<li> buttons
<li> bold, italic, underlined
<li> blockquotes
<li> comments
<li>images
<li> responsive layouts, bootstrap
<li> forms
<li> POST and GET
<li> footer, header, nav, section, aside, article
<li> Videos

