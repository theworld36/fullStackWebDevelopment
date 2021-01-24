# Follow the instructions below to complete the installation process for all of the required tools.


## Git Bash and Terminal 

## Windows Videos

https://youtu.be/srO_vvBohkI/

https://youtu.be/1SzB7IjpN9M/

## Mac Videos

https://youtu.be/XsbLlPtid9s/
	
https://youtu.be/5I1rlq7qkps/

## VS Code

1. Go to the setup page on the VS Code website: https://code.visualstudio.com/download. 

2. Open and run the installer file.
	
3. Once installed, open VS Code and press alt+shift+p (Windows) or cmd+shift+p (Mac). Then press enter. This will allow you to use the "code" command in Git Bash or Terminal to open the contents of the current directory in VS Code. Simply navigate to the intended directory and type " code . ". 

## Hello, HTML

HTML (hypertext markup language) is one of the three cornerstone languages used on every webpage in existence. While the syntax might seem daunting at first, by the end of the course, you will find it simple, straightforward, and completely painless.

HTML handles the basic markup of a page. This means that HTML is responsible for the simplest aspects of a website, including the following:

What text elements are on the page?
What images are on the page?
In what order will the elements appear?
Which text elements are the primary headings? Which are the secondary headings?

Start Coding!

The best way to learn coding concepts is to actually code. So let's roll up our sleeves and get started!

1. Open Git Bash/Terminal.

2. Create a new directory with: mkdir firstHtml

3. Navigate into firstHtml (cd firstHtml) and touch in file with: touch index.html

4. Now, enter: code .  (and enter)

This opens index.html in VS Code Editor.

5. Copy and paste the below code directly into the editor.

        <!DOCTYPE html>
        <html lang="en">
        <head>
        <meta charset="UTF-8" />

        <title>Hello World!</title>
        </head>

        <body>
        <h1>Panda Fan Site!</h1>

        <p>
        I LOVE PANDAS!!! I LOVE PANDAS!!! I LOVE PANDAS!!! I LOVE PANDAS!!! I LOVE
        PANDAS!!!
        </p>

        <h2>Reasons I like Pandas</h2>

        <ul>
        <li>They are fuzzy</li>

        <li>They are cute</li>
        <li></li>

        <li>They are adorable</li>
        <li></li>
        </ul>

         <img
          src="http://images4.fanpop.com/image/photos/17800000/Cute-Panda-Cubs-Together-pandas-17838800-450-324.jpg"
          alt="Cute Pandas"
        />

        <br />

        <a href="http://www.pandafix.com/">PandaFix.com</a>
        </body>
        </html>

6. Press ctrl + s to save your project.

7. Press ctrl + b to start your program.

Rejoice! You just created your first HTML file.


Here are a few tags that you'll come across frequently:

    <title>: Aptly named, this tag defines the title of the website as shown on the webpage's tab.

    <head>, <body>: These tags help define the structure of the overall webpage. In essence, head contains invisible matter that the browser uses to render the page correctly, whereas the body tag represents the actual content shown to the user.

    <h1>, <h2>, <h3>, <h4>, <h5>, <h6>: These tags represent the level of heading a given text block represents. Headings are exactly what they sound like; they are larger or more prominent elements of text on a page. They can be likened to topic sentences on a paper.

    <p>: This tag represents paragraphs or blocks of text. You'll use this tag extensively to wrap most of the text on your webpages.

    <strong>, <em>: These tags are used respectively to bold or italicize a given text element.

    <br>: This tag is used to create a line of empty space between two blocks of content.

    <img>: This tag is used to display images on a page. 

    <a>: This tag (which stands for anchor) is used to create links to the same webpage or to other webpages. 

    <ul>, <ol>, <li>: These tags represent unordered lists, ordered lists, and list items. In essence, these HTML elements represent bulleted lists of symbols or numbers.

(Optional) More HTML readings:

	http://www.htmlgoodies.com/primers/html/article.php/3478131/ 
	http://www.w3schools.com/html/html_intro.asp/
	https://www.codecademy.com/learn/learn-html/
	https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/
	https://developer.mozilla.org/en-US/docs/Web/HTML/Element/




## Intro to CSS (Cascading Style Sheets)

CSS  is a style sheet language used for describing the presentation of a webpage.If HTML is the skeleton of a webpage, then CSS is its fat, skin, and pinstripe suit. Whereas HTML is strictly concerned with the markup of webpages, CSS is focused on colors, aesthetics, and visual layout. It works by hooking onto specific elements of an HTML page and formatting them using any number of options (called styles).

Add CSS to your firstHtml:

1. Navigate to the firstHtml directory.

2. Touch in file: style.css

3. Enter VS Code with code .

4. To link your html file with your css file add the following code in the head tag: 

        <link rel="stylesheet" href="style.css"> 

5. In the body of your html file, create "class" values in your unordered list like so:

         <ul>
          <li>They are fuzzy</li>

          <li>They are cute</li>
      
          <li>They are adorable</li>
      
          <li class="hairy">They are hairy</li>

          <li class="bamboo">They eat bamboo</li>
          </ul>


Classes (along with IDs) offer us a method to style specific or multiple HTML elements using the same CSS. We'll talk a lot about classes and IDs during the program, but it's helpful to have some exposure in advance.

6. Now open your style.css file in VS Code and copy/paste the below code directly into your editor.

		body {background-color: rgb(211, 64, 64);}

		h1 {color: white;
    		text-decoration: underline;}

		h2, p {color: yellow;}

  		p, li {font-size: 24px;
    		font-family: cursive;}

 	 	.hairy {color: blue;}

  		.bamboo {color: green;}

7. Press ctrl + b to start the program and notice the differences. This is just a basic implementation to help understand the structure of CSS as it will be fleshed out in the future.

(Optional) CSS Readings:

	http://www.w3schools.com/css/css_intro.asp/
	https://www.youtube.com/watch?v=dAUncsVxdvo/
	https://www.codeschool.com/courses/css-cross-country/



## JavaScript 

JavaScript (or JS) is a high-level, dynamic programming language that underpins the web. JavaScript, along with HTML and CSS, is one of the core technologies that make our web experience what it is.

Like C++, Java, Ruby, and Python, JavaScript is written with all the fixings expected of a complete programming language. In it, you will find variables, conditionals, loops, functions, and so much more. We'll be using JavaScript extensively to create the logic that defines the behavior of our web applications.

## How to JavaScript

While the full power of JavaScript is beyond the scope of this prework, let's get a small taste of what's possible.

1. Navigate back to your firstHtml directory.

2. Touch in file: javascript.js

3. Enter VS Code with code .

4. Copy and paste the following code into the <body> of your index.html file:

        <div id="box" style="height:150px; width:150px; background-color:orange; margin:25px"></div> 

This will create an object "box" with dimensions, color, etc..

5. Next copy and paste the following code after the <div> object to create button objects that can be acted upon by clicking:

        <button id="button1">Shrink</button>
        <button id="button2">Grow</button>
        <button id="button3">Reset</button>

6. Now copy and paste the following after the previous code to link your index.html file to your javascript.js file:

         <script type="text/javascript" src="javascript.js"></script>

We have now prepared the html file for interaction with javascript.

7. Navigate to your javascript.js file in vs code and copy/paste the following in it:

		document.getElementById("button1").addEventListener("click", function(){
		document.getElementById("box").style.height = "25px";});

		document.getElementById("button2").addEventListener("click", function(){
		document.getElementById("box").style.height = "250px";});

		document.getElementById("button3").addEventListener("click", function(){
		document.getElementById("box").style.height = "150px";});

8. Run the program and see what happens!

Again, this is just a basic implementation of Javascript to get you prepared for the rest of the material. 

(Optional) Javascript readings:  

	http://www.w3schools.com/js/js_intro.asp/
	https://www.codecademy.com/learn/javascript/
	https://www.codeschool.com/learn/javascript/

## The Rest

In each parte you can find example programs with instuctutions for various web development tools. 
