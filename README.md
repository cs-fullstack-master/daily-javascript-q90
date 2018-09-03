# daily-javascript-q90

You have the following code: 
```html
<!DOCTYPE html> 
<html> 
<head> 
      <title>Intro to JavaScript</title> 
          	<meta charset="utf-8" /> 
      <style> 
           .format-output { 
                width: 300px; 
                height: 100px; 
                border: 1px solid blue; 
                font: bold 20px "courier new"; 
                text-align: center; 
           } 
      </style> 
</head> 
<body> 
      <div id="result1" class="format-output"></div> 
      <div id="result2" class="format-output"></div> 
      <script> 
           document.getElementById("result1").innerHTML = "<b>Hello World</b>"; 
           document.getElementById("result2").innerText = "<b>Hello World</b>"; 
      </script> 
</body> 
</html> 
```
What will be displayed in the div with id result1 and the div with id result2?

Choose the correct answer

1) The first div displays "Hello World" in bold, and the second div displays ```<b>Hello World</b>```.
2) They both display ```<b>Hello World</b>```.
3) They both display "Hello World" in bold.
4) The first div displays ```<b>Hello World</b>```, and the second div displays "Hello World" in bold.
