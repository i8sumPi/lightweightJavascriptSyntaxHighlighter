# Lightweight Javascript Syntax Highlighter
This is a lightweight javascript syntax highlighter, with under 150 lines of code! This makes it really easy to highlight javascript syntax without installing a big library. Also, you can look at the code for inspiration for your own syntax highlighting program!

## How to add
Adding Lightweight Javascript Syntax Highlighter is really easy! Just include
```html
<script src="http://kiraprograms.com/syntaxHighlighter.js"></script>
```

This makes any `<code>` block highlighted to JavaScript.
```html
This is an example:
<code>
  function myFunction(param,otherParam){
    return param*otherParam;
  }
  document.getElementById("myButton").onclick = function(){
    console.log(myFunction(200,14));
  }
</code>
And also another one
<code>
  //hello world
  alert("hello world");
</code>
```
