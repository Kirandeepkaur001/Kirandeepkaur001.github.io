# DAY 12 : 

# CSS (Cascading Style Sheet)

## **_What is CSS?_**
CSS stands for Cascading Style Sheets. It is used to style HTML elements, like changing fonts, colors, spacing, layouts, etc.

## **_Types of CSS:_**
There are 3 main types of CSS:

## **_1. Inline CSS:_**
CSS is written inside the HTML element using the style attribute.
## **_Example_**
    <p style="color: red; font-size: 20px;">This is a red paragraph.</p>

## **_2. Internal CSS:_**
CSS is written inside the <style> tag in the HTML document (usually inside the <head>).
## **_Example_**
    <!DOCTYPE html>
    <html>
    <head>
      <style>
        h1 {
          color: blue;
          font-family: Arial;
        }
      </style>
    </head>
    <body>
      <h1>Hello World</h1>
    </body>
    </html>

## **_3. External CSS_**
CSS is written in a separate .css file, and linked using <link> tag.

#### **_HTML (index.html)_**
    <!DOCTYPE html>
    <html>
    <head>
      <link rel="stylesheet" href="style.css">
    </head>
    <body>
      <h1>Hello World</h1>
    </body>
</html>

#### **_CSS (style.css)_**
    h1 {
      color: green;
      text-align: center;
    }
