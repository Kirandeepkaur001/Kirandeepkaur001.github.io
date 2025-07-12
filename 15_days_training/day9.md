# DAY 9 :

### Introduction to HTML:
HTML stands for HyperText Markup Language.
It is the basic building block of all websites. You use HTML to tell a web browser what to show on a web page.

### What Does HTML Do?
HTML is used to:
* Show text, images, videos, links, and buttons on a web page.
* Create structure of the page like headings, paragraphs, and lists.
* Add forms (like login, search box, etc.).

### Example of a Simple HTML Page:
      <!DOCTYPE html>
      <html>
        <head>
          <title>My First Web Page</title>
        </head>
        <body>
          <h1>Hello, World!</h1>
          <p>This is my first webpage using HTML.</p>
        </body>
      </html>

![image](https://github.com/user-attachments/assets/c21d2bf1-d125-4af3-80eb-6e027dfc40c4)

### Explanation:

* <!DOCTYPE html> → Tells the browser this is an HTML5 document.
* <html> → The main container of the page.
* <head> → Contains page info (like the title).
* <title> → The title you see on the browser tab.
* <body> → What you actually see on the web page.
* <h1> → A big heading.
* <p> → A paragraph.

### How browser renders HTML:
Rendering means how the browser reads HTML and displays it as a web page on your screen.

### **_1. You Open a Web Page_**
* You type a website address (like www.google.com) in your browser.
* The browser sends a request to the server and gets the HTML code of that page.

### **_2. Browser Reads HTML Line by Line_**
* The browser reads the HTML code from top to bottom.
* It sees tags like `<html>`, `<head>`, `<body>`, `<h1>`, `<p>`, etc.

### **_3. Builds the Structure (DOM Tree)_**
* The browser makes a structure of the page in its memory called the DOM (Document Object Model).
* Think of it like building a family tree of all HTML elements.

### **_4. Applies CSS (Styles)_**
* If there is any CSS (color, size, font, etc.), the browser applies it to the right elements.

### **_5. Runs JavaScript (if any)_**
* If the page has JavaScript (for buttons, animations, etc.), the browser executes it.

### **_6. Shows the Page_**
* After reading and processing everything, the browser draws the final web page on your screen.


