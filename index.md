![HTML First](https://user-images.githubusercontent.com/94478022/143102590-1f00b386-4adc-491a-8d27-dc732583cde8.png)

# Lesson 1 Part 1 -  HTML 101

 HTML is short for Hypertext Markup Languge.
 It is used for creating web pages. 
 It uses text instead of blocks.
 We will also learn CSS (Castcading Stylesheets).


  We are finally in the basics, open [texteditor.co](https://texteditor.co/) on your computer
  to start. 
 Now write:
 
 ```
 <!DOCTYPE html>
 <!--the doctype html will start the code-->
 <html>
 <head>
 <!---head, title, html, and body are tags-->
  <title>
  My HTML Page
  </title>
  <meta charset="UTF-8">
 </head>
 <body>
 </body>
 </html>
 ```
 This is the basic html code.

# Lesson 1 Part 2 - Text

Now Write in between ``` <body> ``` and ``` </body> ```:

```
<h1>This is a heading</h1>
<p>Write anything in here</p>

```

Your code should look like this:

```

<!DOCTYPE html>
 <!--the doctype html will start the code-->
 <html>
 <head>
 <!---head, title, html, and body are tags-->
  <title>
  My HTML Page
  </title>
  <meta charset="UTF-8">
 </head>
 <body>
 <h1>This is a heading</h1>
<p>Write anything in here</p> </body>
 </html>
 
 ```
 good job!
 
 # Lesson 2 Part 1 - Advanced HTML
 

 Open a new file on your computer and write:
 
 ```
 <!DOCTYPE html>
 
 <html>
 <head>
  <title>
  My HTML Page 2
  </title>
  <meta charset="UTF-8">
 </head>
 <body>
 <!--table-->
 <table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
<hr>
<!--hyperlink-->
<a href="https://google.com">Google</a>

<p>hello world!</p>
</body>
 </html>
 
  
 ```
 
A table and a link should be on your browser



# Lesson 2 Part 2 - CSS

Now we are at CSS.

Write inside the body tag:


```
<!--start CSS-->
<style>
p { 
font-family: Monospace;
}
</style>


```

Your code should be like this:

```

<!DOCTYPE html>
 
 <html>
 <head>
  <title>
  My HTML Page 2
  </title>
  <meta charset="UTF-8">
 </head>
 <body>
 <!--start CSS-->
<style>
p { 
font-family: Monospace;
}

</style> 
<!--table-->
 <table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
<hr>
<!--hyperlink-->
<a href="https://google.com">Google</a>

<p>hello world!</p>
</body>
 </html>
 
```

# Mini Lesson 1 - Bold and itailc

Write in a new file:

```
<!DOCTYPE html>
 
 <html>
 <head>
  <title>
  My HTML Page 3
  </title>
  <meta charset="UTF-8">
 </head>
 <body>


<b>Bold text</b>
</body>
 </html>

```

Does it look **bold?**
