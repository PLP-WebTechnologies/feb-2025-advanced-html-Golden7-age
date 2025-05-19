# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨



<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Implementation of HTML5 images, lists, tables, forms and input types.</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        label {
            font-color: #811e1e;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <h1>Implementation of HTML5 images, lists, tables, forms and input types.</h1>
    <h2>Classes</h2>
    <ol type="I">
        <li>Golden</li>
        <li>Silver</li>
        <li>Bronze</li>
        <li>Platinum</li>
        <li>Diamond</li>
        <li>Emerald</li>
    </ol>
    <a href="https://www.pexels.com/photo/set-of-colorful-semiprecious-stones-placed-chaotically-on-gray-tabletop-in-jewelry-store-4040599/">
        <img src="Images of certain precious stones.jpg" alt="semiprecious stones" width="300" height="200"><br><br>
        <!-- Form of precious stones -->
    <form>
        <label for="name">Name:</label>
        <input type="text" name="name"><br><br>
        <label for ="email">Email:</label>
        <input type="email" name="email"><br><br>
        <label for="phone">Phone:</label>
        <input type="tel" name="phone"><br><br>  
        <label for="url">Password:</label>
        <input type="password" name="password"><br><br>
        <label for="date">Date:</label>
        <input type="date" name="date"><br><br>
        <label for="country">Country:</label>
        <select name="country" type="country">
            <option value="Nigeria">Nigeria</option>
            <option value="USA">USA</option>
            <option value="Canada">Canada</option>
            <option value="Mexico">Mexico</option>
            <option value="UK">UK</option>
            <option value="Germany">Germany</option>
            <option value="France">France</option>
            <option value="Italy">Italy</option>
            <option value="Spain">Spain</option>
            <option value="Japan">Japan</option>    
        </select>
        <br><br>
        <label for="gender">Gender:</label>
  <label>
    <input type="radio" name="gender" value="male" required> Male
  </label>
  <label>
    <input type="radio" name="gender" value="female"> Female
  </label>
  <label>
    <input type="radio" name="gender" value="non-binary"> Non-binary
  </label><br><br>
  <label for="fruit">Fruits loved:</label>
    <label>
        <input type="checkbox" name="fruit" value="apple"> Apple
    </label>
    <label>
        <input type="checkbox" name="fruit" value="banana"> Banana
    </label>
    <label>
        <input type="checkbox" name="fruit" value="orange"> Orange
    </label>
    <label>
        <input type="checkbox" name="fruit" value="grape"> Grape
    </label>
    <label>
        <input type="checkbox" name="fruit" value="mango"> Mango<br><br><br>
    <button type="submit">Submit response</button>
</form><br><br>
<!-- Table of Preciouse stone and stating several things -->
<table>
    <table border="1" cellpadding="5" cellspacing="0">
    <thead>
        <tr>
            <th colspan="4">Precious Stones</th>
        </tr>
    </thead>
    <tr>
        <th>Name</th>
        <th>Address</th>
        <th>Mobile</th>
        <th>E-mail</th>
    </tr>
    <tr>
        <td>Diamond</td>
        <td>123 Diamond St.</td>
        <td>555-1234</td>
        <td>Diamond27@gmail.com</td>
    </tr>
    <tr>
        <td>Ruby</td>
        <td>456 Ruby Ave.</td>
        <td>555-5678</td>
        <td>Ruby@hotmail.org</td>
    </tr>
    <tr>
        <td>Emerald</td>
        <td>789 Emerald Blvd.</td>
        <td>555-9012</td>
        <td>Emeradine45@yahoo.com</td>  
    </tr>
    <tr>
        <td>Topaz</td>
        <td>101 Topaz Rd.</td>
        <td>555-3456</td>
        <td>Topaz55@outlook.org</td>
    </tr>
    <tr>
        <td>Sapphire</td>
        <td>202 Sapphire Ln.</td>
        <td>555-7890</td>
        <td>Safya16@gmail.com</td>
    </tr>
    </table>
</body>
</html>
