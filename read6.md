# JavaScript & jQuery
### JavaScript is a programming language commonly used in web development. It was originally developed by Netscape as a means to add dynamic and interactive elements to websites.
 

## JAVASCRIPT :
1.	Create a folder to put the example in called cOl, then start up your favorite code editor, and enter the text to the right. A JavaScript file is just a text file (like HTML and CSS files are) but it has a . j s file extension, so save this file with the name add-content . j s
2.	Get the CSS and images for this example from the website that accompanies the book: www.javascriptbook (Links to an external site.). com To keep the files organized, in the same way that CSS files often live in a folder called styles or css, your JavaScript files can live in a folder called scripts,javascript,orjs. In this case, save your file in a folder called j s
3.	In your code editor, enter the HTML shown on the left. Save this file with the name add-content.html The HTML <script> element is used to load the JavaScript file into the page. It has an attribute called src, whose value is the path to the script you created. This tells the browser to find and load the script file (just like the src attribute on an tag)
•	Open the HTML file in your browser. You should see that the JavaScript has added a greeting (in this case, Good Afternoon!) to the page. (These greetings are coming from the JavaScript file; they are not in the HTML file.)
•	Java script example
1.	 <html>  
<head>  
<script type="text/javascript">  
function msg(){  
 alert("Hello Javatpoint");  
}  
</script>  
</head>  
<body>  
<p>Welcome to JavaScript</p>  
<form>  
<input type="button" value="click" onclick="msg()"/>  
</form>  
</body>  
</html>  
