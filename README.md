
## Hi there, today we are making a personal info panel :>

**What is a personal info panel?** <br>
An personal info panel is a small space/dashboard for yourself or others to see personal details about you in a quick glance.
It is a beginner level web-dev project and this is a guide to help you with it :>

**prerequisites**
- HTML Basics (coverered in this guide)
- SS (covered in this guide)
- JS (also covered in this guide)
- A code editor (im using VSCODE) + Hacaktime installed [hackatime](hackatime.hackclub.com)
- Github repo 
- A deploying site (vercel, github pages etc)

*Let's start with the basic structure of a webpage, and it is made using HTML*
<BR>

**HTML** stands for Hyper Text Markup Language, it's basically the structure of a webpage and defines a browser what things are on the page such as links, buttons, images, videos etc. <br>
**CSS** stands for Cascading Style Sheets, it is used to format and design the structure, think of adding colors, different fonts, design styles etc <br>

**JS** is javascript and is responsible for adding interactivity in a webpage, for example, updating texts, fetching info from APIs 

in short:
- **HTMl** : structure 
- **CSS** : style
- *JSS** : behavior/style 

lets go over each one slowly!

# HTML
this is a basic code of a HTML:
``` <html>
<head>
    <title> TITLE </title>
</head>
<body>
body of the page
</body>
</html> 
```

We use **</>** to create "tags" in html, what are tags you ask?
Tags are instructions given to a web browser to act a specific way, it could be adding links, creating images etc
Most tags inside HTML are in pairs i.e. they have a opening **<>** and a closing 'slash' attached to it **</>**, it is added to tell the browser where that element ends. <br>
Some examples would be;
```<html> ...... </html>
<body> ...... </body>
<p> ..... </p>
```

But all the tags are not built that way, some tags such as `<br>, <hr>` etc do not have a closing tag because they dont have any content inside them. For example, `<br>` tag is used to break lines in HTML while writing, it doesnt has any content inside the tag, its only work is to break a line and start fresh from a new line. <br>

Phew! That's a lot of info, but what about how are these tags used? Yess! Let's go over the basic tags slowly :>
- `<html>....</html>` : It is the root tag of HTML, an html document should always begin with `<html>` tag and end with `</html>`
- `<head>...</head>`: It is used for storing info which isn't directly visible on the webpage, such as `<title>` tag or linking to css page (we'll get to it!) etc
- `<title>...</title>`: Title is the text which appears on a browser tab
- `<body>...</body>`: The main visible content visible on the webpage goes here

Other tags include: <br>
- `<img`>`: For adding images in the webpage 
- `<a>...</a>`: for adding links 
- `<h1> to <h6> tags`: for different sizes of text appearing
- `<p>...</p>`: for adding paragraphs

Woah, that was a lot of info! 
Lets get to coding now and get some work done in setting up in our structure for our personal info page! 

When you open any editor, im using VS code here, an html file is saved with .html and "index.html" is the default name servers look for while opening the site.
For VS Code, you can press `!` and you will see something like this appear in your file:
![image 1](images/image1.png)

You can change the title to your liking, im keeping "infor" T^T

**tip**: If you're using VS CODE, I really recommend downloading an extension called "Live server" by Ritwick Dey, so you can see the work you're doing locally and change accordingly. <br>
After changing the title, you should be able to see this:
![image 2](images/image2.png)

Now, you can start entering some details about yourself, it can be just random stuff, you can always update it later! <br>
I've added this, a small intro:
![image 3](images/image3.png)

You'd see the content like this in your browser:
![image4](images/image4.png)

There, you have a something on your site now but it doesn't look too well because it is not styled yet, lets add a few tags and see further. <br>
I'm adding a `<br>` tag at the end of all lines. And it looks much better now! 
![image5](images/image5.png)
