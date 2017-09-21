# What is HTML

If a website is a house, Hypertext Markup Language comprises of the foundation, walls, floors, and etc. 
It is everything that is needed to build the basics of a web document. When it is accompanied with other front-end languages, such as CSS and JavaScript; the document will come alive.

# HTML Anatomy

HTML has three basic components. The document type deceleration, the head, and the body. Document type deceleration serves to tell browsers what kind of HTML they are opening.
After all, the new kid on the block known as HTML5 is not the only version still in use. The head contains data telling search engines what the document is about, who made it, and dozens of other important information. 
It also tells the browser which scripts or style sheets to pre-load. The document body is everything we see and some of what we do not. Everything you're reading here is part of a Markdown document's body. But, the body can also contain additional scripts or stylesheets that were not needed as part of the pre-load or located elsewhere in the document to decrease load times.

# HTML snippet

Below is what a basic HTML page looks like.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="styles.css">
        <title>Hello, World!</title>
    </head>
    <body>
        <h1>Hello, World!</h1>
        <script src="scripts.js"></script>
    </body>
</html>
```
As mentioned before, we have each of the basic components. We also have additional meta tags. Meta tags tell search engines about the page and tell the browser how to load the page.
The Title tag tells the browser what to display on the Tab section of your browser window. It is also used by search engines when displaying the name of the page.
Give it a try, open a notepad or your IDE and create an HTML document.

1. Open your editor
2. Copy and paste the above code into the editor.
3. Save the document as first.html
4. Open the document via your browser.

Neat, right? Most operating systems and browsers have native support for opening documents containing simple scripting or markup.