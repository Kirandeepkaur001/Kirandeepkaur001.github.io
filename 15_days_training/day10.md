# DAY 10 :

# HTML tags, elements and lists

## **_What is an HTML Tag?_**
* A tag is the keyword used to create elements in HTML.
* Tags are written in angle brackets < >.
* Most HTML tags have an opening tag and a closing tag.

### **_Example:_**
    <p>This is a paragraph.</p>
    
* `<p>` → opening tag
* `</p>` → closing tag
* "This is a paragraph." → content

## **_What is an HTML Element?_**
An element includes:
* The opening tag
* The content
* The closing tag

### **_Example:_**
    <h1>Welcome</h1>
This whole line is an HTML element.

## **_Self-Closing Tags (Void Elements):_**
These tags do not need closing tags.

### **_Example:_**
    <img src="image.jpg" alt="Image">
    <br>
    <hr>
    <input type="text">

## **_Common HTML Tags and Elements:_**
| Tag             | Purpose                           | Example                                   |
| --------------- | --------------------------------- | ----------------------------------------- |
| `<h1>`–`<h6>`   | Headings from largest to smallest | `<h1>Main Title</h1>`                     |
| `<p>`           | Paragraph                         | `<p>This is a paragraph.</p>`             |
| `<a>`           | Hyperlink                         | `<a href="https://example.com">Visit</a>` |
| `<img>`         | Image                             | `<img src="pic.jpg" alt="pic">`           |
| `<ul>` / `<ol>` | Unordered / Ordered list          | `<ul><li>Item</li></ul>`                  |
| `<div>`         | Division or container             | `<div>Content</div>`                      |
| `<span>`        | Inline container                  | `<span>Text</span>`                       |
| `<strong>`      | Bold importance                   | `<strong>Important</strong>`              |
| `<em>`          | Emphasis (italic)                 | `<em>Note</em>`                           |
| `<br>`          | Line break                        | `Line1<br>Line2`                          |
| `<input>`       | Input field                       | `<input type="text">`                     |

## **_Registration Form:_**
    <html>
        <head>
            <title>registration form</title>
            <style>
                body{
                   background-color:rgb(224, 223, 223);
                }
            </style>
        </head>
        <body>
            <form>
                <h1>Registration form</h1>
                <table  cellpadding="15px"  cellspacing="0">
                    <tr>
                        <td> First Name</td>
                        <th>
                        </th>
                        <th>:
                        </th>
                        <th>
                        </th>
                        <td colspan="2">
                            <input type="name" name="F.Name" required>
                        </td>
                    </tr>
                    <tr>
                        <td>Last Name</td>
                        <th>
                        </th>
                        <th>:
                        </th>
                        <th>
                        </th>
                        <td colspan="2">
                            <input type="name" name="L.Name">
                        </td>
                    </tr>
                    <tr>
                        <td>email</td>
                        <th>
                        </th>
                        <th>:
                        </th>
                        <th>
                        </th>
                        <td colspan="2">
                            <input type="email" name="Email" required>
                        </td>
                    </tr>
                    <tr>
                        <td>Password</td>
                        <th>
                        </th>
                        <th>:
                        </th>
                        <th>
                        </th>
                        <td colspan="2">
                            <input type="password" name="Password" required>
                        </td>
                    </tr>
                    <tr>
                        <td>DOB</td>
                        <th>
                        </th>
                        <th>:
                        </th>
                        <th>
                        </th>
                        <td colspan="2">
                            <input type="numbers" name="DOB" placeholder="dd-mm-yy"required>
                        </td>
                    </tr>
                    <tr>
                        <td>Gender</td>
                        <th>
                        </th>
                        <th>:
                        </th>
                        <th>
                        </th>
                        <td>
                            <input type="radio" name="Gender" value=male required>Male
                            <input type="radio" name="Gender" value=female required>Female
                            <input type="radio" name="Gender" value=other required>Others
                        </td>
                    </tr>
                    <tr>
                        <td>Mobile</td>
                        <th>
                        </th>
                        <th>:
                        </th>
                        <th>
                        </th>
                        <td colspan="2">
                            <input type="numbers" name="Mobile"required>
                        </td>
                    </tr>
                    <tr> 
                        <td>Address</td>
                        <th>
                        </th>
                        <th>:
                        </th>
                        <th>
                        </th>
                        <td colspan="2">
                        <input type="text" name="Address"required>
                        </td>
                    </tr>
                    <tr>
                        <td>
                        </td>
                        <td>
                        </td>
                        <th>
                        </th>
                        <th>
                        </th>
                        <th colspan="2">
                            <button>SUBMIT</button>
                            <input type="reset" value="RESET">
                       </th>
                    </tr>
                    </table>
            </form>
        </body>
    </html>

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2205e57b-4fab-448c-a4f3-c59de3eac6d3" />
