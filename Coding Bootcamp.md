Autor: Ania kubow.
Date: 26-06-2025.
```cardlink
url: https://youtu.be/cndko2lx-_Y?si=sMvTa3HFrxCIZ_cy
title: "Free 12 hour YouTube Coding Bootcamp 2025!"
description: "🚀 To take the full 470 video course visit here: https://www.codewithania.com. This 12hr video is free - and will always be free!00:00 Introduction02:06 What..."
host: youtu.be
favicon: https://www.youtube.com/s/desktop/daa21ba0/img/logos/favicon_32x32.png
image: https://i.ytimg.com/vi/cndko2lx-_Y/maxresdefault.jpg
```

---
# Tips:
- Always keep the folder names ==lower case== as most computers are case sensitive. - Good practice.
- Also be careful while using spaces in the file names as some computers or editors might mistake it for being two file names. - A good practice is to follow hyphen or a dash(-) while naming a folder.
- use .html extension to make sure the code editor recognizes the language.
- **SEO** - stands for search engine optimization. ==It is the practice of improving the website's visibility in the search engine results.==
- Tip for clean code is to ==Formatting lines== -> when using a paragraph element break the long-ass paragraph into short chunks so it fits the editor and can be visible while coding rather than long-ass line.
# Intro to HTML:
- The language that started the web and web-development.
- HTML - Hyper-Text Markup Language. HTML-5
- Describes the structure of web pages.![[html.png]]
- By using HTML we are annotating a document that is syntactically different to the existing text.
---
**EXPLAINED:**
- remember HTML uses ==annotations== such as h1, a, img... This is like when we have regular text and we add extra information such as h1 to make it as a heading and in the above example the teacher ==rounds off== the text and writes an improvement - similarly we highlight a text in html using tags and due to this reason it is called a Markup Language!
---
## HTML Syntax:
- Syntax is a fancy word for the **structure of statements** in a computer language.![[html-elements.png]]
- There are over 142 elements in HTML.
- these elements uses tags that are placed in the beginning and end of the text to tell the browser a action is about to happen! 
```Html
<p> I am a paragraph! fuck this shit </p> 
```
- In the above example the 'p' tag needs to have a ending tag telling the browser that an action is going to be completed. - Anything after this cannot be applied for styling or be a paragraph.
- All together this is called a Paragraph element🪂
- An interesting element is a Heading element: h1-h6 - Each represent a level of section.
- Giving texts as a tags it gives **Semantic Meaning** to the browser - The browser will read certain text as more ==important== than the rest based on the tags we give!
	- In this case the 'h1' tag will be treated as the most important tag on the browser page.
- Most elements have opening and closing tags while some elements do not need both - a good example is a 'img' element
```Html
<img src = "dog-treats.png" alt = "Dog snacks">
```
- We use image element to embed images onto our pages. Image elements do this via a ==specific attribute called 'src' - source==. That defines the path to the img file. Also using an ==alternative attribute== to give a description of what the image is.
- **Comments** are used to document a code and this will not be visible on the browser. <!-- This is a comment --> <- this is a comment.
---
**SYNTAX EXPLANATION:**
- here '!Doctype html' inside< >tag is used to tell the browser that this is the latest version of html. - for correct renders
- 'html' opening and closing is the root of the document as everything will be written in between.
	- we can also set primary language for our document using ==lang== inside of the html tag stating the required language such as ==en==. lang="en" or lang="jp" - Japanese.
- The 'head' tag is used to store data and information that is not visible in the browser. The head tag stores ==meta data - A set of data that gives information about other data==. Such as Author, Date, file data etc.
- In the 'head' tag -> we have a 'meta tag' with charset set to 'UTF-8'. - The ==charset attribute specifies the character encoding for the Html document== - Not too important simply says "it will cover most of the characters, symbols and emojis etc."
- Next we have ==title tag== this is used inside the head element to name our html document. - opening and closing tag! - shows in search results and tab of the browser.
- ==body tag== is where all the visible part of the browser is stored as code.
---
### Headings:
- There are 6 heading h1 being the largest and h6 being the smallest. Plus they have opening and closing tag.![[headings.png]]
- **CSS** allows us to change the ==font size== of these headings to however our liking. Also color and weight etc.
### Paragraph:
- Paragraph elements represents a paragraph of text. We can write multiple lines in the paragraph but it will not affect how it will look in the browser.
---
### Project-1:
![[project-1.png]]
```Html
<!Doctype html>
<html lang="en">
	<head>
		<meta charset = "UTF-8">
		<title>Fuck this shit!</title>
	</head>
	<body>
	<!-- This is just me messing around. The syntax and elements are corect
	dont focus more on the insider content. You just gonna ignore anyway -->
	<h1>Simple Macaroni and Cheese</h1>
	<p>
		This is a fucking text and the the thing in paragrph tag is
		i can break the line and the whole text will be in a single
		line until i use a fucking <br> to break the line.
	</p>
	<h2>Ingredients for Macaroni and Cheese</h2>
	</body>
<html>
```
---
### Indentation and Spacing:
- Indentation should be consistent throughout the code. We can either use 4 spaces or a 2 spaces.
```Html
<h1>My main heading!</h1>

<article>
	<h2>This is 4 spacing or a Tab<h2>
  <p>This is a 2 spacing but is considered a indent</p>
</article>
```
- Be consistent with a 4 spacing or 2 spacing don't fucking mix shit.
### Lists:
- List elements are made up of at least two elements - A wrapping element and the individual list item elements inside.
	- ul - unordered list -> li - list.
	- ol - ordered list -> li - list.
- ul - Order doesn't matter. - ==dot list==.
- ol - Order matters. - 1,2,3... list. ==Hierarchy of steps==.
- The ==li element== can contain text for now but it can also contain links so we can make a navbar in websites!
```Html
<ul>
	<li>This is one</li>
	<li>This is Two</li>
	<li>This is Three</li>
</ul>
<ol>
	<li>This is one</li>
	<li>This is Two</li>
	<li>This is Three</li>
</ol>
```
---
### Links:
- Links are great we can link to other parts of our webpage, External pages, places on our page, open up a prompt to email and much more.
- Anchor - 'a' acts as a anchor chain that links to any other site or page etc.
```Html
<a href="https://www.google.com/">Google</a>
<a href="mailto:rafaathahmed20@gmail.com">Email me</a>
<a href="tel:8688873323">Call me</a>
<a href="#other-recipes">Other recipes</a>
<!-- Link to sections inside the page -->
<h1 id = "other-recipes">Other recipes</h1>
```
- Here 'mailto' and 'tel' are referred to link prompt.
- We use a # to link the page to a 'id' attribute.
---
### Linking pages:
- By following path we can link pages:![[linkning-pages.png]]
- If we need to link a certain page from the index we need to define a path in the href="pages/about-me.html" <- here i have linked the page using a / slash to move forward.
- The / is a doorway in and out a folder.
- To come back to the default page we need to link back in the 'about-me' pages as -> href="../index.html" This is a way to go out of the folder so that the index file is visible.
- ![[path-forward.png]]![[Pasted image 20250626082211.png]]
---
### Images:
- The image element represents an image with alternative text for the visually impaired. - self-closing tag
- We can either connect the image by writing a path in our local folder or embed from a online source via URL address that is posted online - beware that if the owner decides to remove the image the link will be broken and img will not be displayed.
---
### Tables:
- Tables are complex and involves a lot of nested elements.