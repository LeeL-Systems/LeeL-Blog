---
layout: post
published: true
resource_folder: 'post'
type: 'Blog'
subject: 'Markdown Tutorial'
title: 'Markdown Tutorial'
category: 'LeeL Blog'
image: 'post_blog.jpg'
author: 'Rogerio dos Santos'
---



Markdown
===================


Markdown is a format syntax language way easier to use maintain than HTML when creating or editing your posts.  
Oposite of HTML, Markdown does relies in tags for formatting your text. Steady, Markdown uses syntax rules that fits naturally on your text as a result you focus on the content you are writing and not the language specific tags that you should use. 


Inside a Markdown, you can still use HTML if you will, giving you the freedom to decide witch way to format your post you want to apply.  




For more info about Markdown itself click [Markdown](http://daringfireball.net/projects/markdown "Markdown web site")


Links
-----


To use text for the link, write it [like this](http://someurl).


<script src="https://gist.github.com/RogerioDosSantos/b901367e78da663fb0c0.js"></script>




You can add a *title* (which shows up under the cursor) [like this](http://someurl "this title shows up when you hover").


<script src="https://gist.github.com/RogerioDosSantos/1d47d91c6f6a97db66f0.js"></script>




Reference Links
---------------


You can also put the [link URL][1] below the current paragraph like [this][2].


   [1]: http://leel-systems.github.io/LeeL-Blog
   [2]: http://leel-systems.github.io/LeeL-Blog "A link url with a funk title"




<script src="https://gist.github.com/RogerioDosSantos/6f21e6f9dfd58959cf40.js"></script>




Here the text "link URL" gets linked to "http://url", and the lines showing 
"[1]: http://url" won't show anything.




Or you can use a [shortcut][] reference, which links the text "shortcut" 
to the link named "[shortcut]" on the next paragraph.


   [shortcut]: http://leel-systems.github.io/LeeL-Blog


<script src="https://gist.github.com/RogerioDosSantos/789a2b9b11c717aee445.js"></script>
   


Text
----


Use * or _ to emphasize things:


*this is in italic*  and _so is this_


**this is in bold**  and __so is this__


***this is bold and italic***  and ___so is this___




<script src="https://gist.github.com/RogerioDosSantos/9cd9c06d8cd2da5e6a07.js"></script>




Just write paragraphs like in a text file and they will display how you would expect.  A blank line separates paragraphs.


So this is a new paragraph. But any text on adjacent lines will all end up in the same paragraph.




Blockquotes
----------


> Use the > character in front of a line, *just like in email*.
> Use it if you're quoting a person, a song or whatever.
> You can use *italic* or lists inside them also.
And just like with other paragraphs,
all of these lines are still
part of the blockquote, even without the > character in front.  


To end the blockquote, just put a blank line before the following paragraph.


<script src="https://gist.github.com/RogerioDosSantos/35e67a039672ae1d604c.js"></script>


Preformatted Text
----------------


If you want some text to show up exactly as you write it, without Markdown
doing anything to it, just indent every line by at least 4 spaces (or 1 tab).


    This line won't *have any markdown* formatting applied.
    You can even write <b>HTML</b> and it will show up as text.
    This is great for showing program source code, or HTML or even Markdown.
    <b>this won't show up as HTML</b> but exactly <i>as you see it in
    this text file</i>.


(In a normal paragraph, <b>this will show up in bold</b> just like normal HTML.)


<script src="https://gist.github.com/RogerioDosSantos/bac54017174cd70d83f9.js"></script>
    
   Remember, you have to indent by *at least 4 spaces* to do it.  This paragraph won't be preformatted because has only 3 idents.
   
<script src="https://gist.github.com/RogerioDosSantos/a00a2d4399d8b370748b.js"></script>


And if you use [reference][] links, make sure the links are indented 
by *fewer than* 4 spaces.
   
    [reference]: http://leel-systems.github.io/LeeL-Blog


(Woops, that link didn't work, see? It just got displayed as preformatted text.)  


As a shortcut you can use backquotes to do the same thing while inside
a normal paragraph. `This won't be *italic* or **bold** at all.`


<script src="https://gist.github.com/RogerioDosSantos/da9c3ccf5a8c316b7589.js"></script>


Lists
--------


* an asterisk starts an unordered list
* and this is another item in the list
+ or you can also use the + character
- or the - character


<script src="https://gist.github.com/RogerioDosSantos/f64cd3ccd4a9ecc8cf66.js"></script>


To start an ordered list, write this:


1. this starts a list *with* numbers
+  this will show as number "2"
*  this will show as number "3"
9. any number, +, -, or * will keep the list going.
    * just indent by 4 spaces (or tab) to make a sub-list
        1. keep indenting for more sub lists
    * here i'm back to the second level
        


<script src="https://gist.github.com/RogerioDosSantos/c805fca583282d610e91.js"></script>




Headers
---------


This is a huge header
==================


this is a smaller header
------------------


Just put 1 or more dashes or equals signs (--- or ===) below the title.


You might use the huge header at the very top of your text for a title or
something (except weblog posts usually already have a title), and use the
smaller header for subtitles or sections.




<script src="https://gist.github.com/RogerioDosSantos/0a92683c947a885d7351.js"></script>


Horizontal Rule
---------------


just put three or more *'s or -'s on a line:


----------------


or you can use single spaces between then, like this:


* * *


or 


- - - - - - - 


Make sure you have a blank line above the dashes, though, or else:


you will get a header
--- 




<script src="https://gist.github.com/RogerioDosSantos/7dbd876cf79222bd0d73.js"></script>


Images
-----------


To include an image, just put a "!" in front of a text link:


![Blog Post Network](http://leel-systems.github.io/LeeL-Blog/resources/page/Post/post_network.jpg "Blog Post Network")


The "alternate text" will show up if the browser can't load the image.


You can also use a title if you want, like this:


![Blog Post Image](http://leel-systems.github.io/LeeL-Blog/resources/page/Post/post_blog.jpg "Blog Post Image")




<script src="https://gist.github.com/RogerioDosSantos/bdf2f8306c7e32b3c430.js"></script>




Escapes
---------


What if you want to just show asterisks, not italics?


* this shows up in italics: *a happy day*
* this shows the asterisks: \*a happy day\*


The backslashes will disappear and leave the asterisks.


You can do the same with any of the characters that have a special meaning
for Markdown.






<script src="https://gist.github.com/RogerioDosSantos/48b9ee1a00e54764c854.js"></script>


More Headers
----------


More ways of doing headers:


#this is a huge header#
##this is a smaller header##
###this is even smaller###
####more small####
#####even smaller#####
######smallest still: `<h6>` header


You can use up to 6 `#` characters at the beginning of the line.  
(You can optionally put them on the end, too, and they will disappear.)




<script src="https://gist.github.com/RogerioDosSantos/e277d25846e1c57b1dfc.js"></script>




HTML crap
-------------


Don't worry about special HTML characters. I can write an ampersand & a 
less-than sign, and they show up as I intend them to:  3 < 4.


(You can still write `&amp;` (& character) and `&lt;` (<) or `&gt;` (>) if you want.  or ignore what I just said.)






<script src="https://gist.github.com/RogerioDosSantos/7a2058ab8c2bb0ddcf43.js"></script>




Thanks
---------


Thanks to John Gruber and Aaron Swartz for creating Markdown.


Thanks to Greg Schueler for writing this text.




