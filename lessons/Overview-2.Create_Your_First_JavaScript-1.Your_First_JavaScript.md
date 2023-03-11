## Your First JavaScript

Let's start with adding JavaScript to a webpage.  
JavaScript on the web lives inside de **HTML** document.  
In HTML, JavaScript code must be inserted between **\<scritp>** and **\</scritp>** tags: 
> ###### |HTML|
>\<script><br/>...<br/>\</script>  

JavaScipt can be placed in the HTML page's **\<body>** and **\<head>** sections.  
In the example below, we placed it within the **\<body>** tag.  

```
<html>

    <head>
    </head>

    <body>
        <script>

        </script>
    </body>

</html>
```
>:information_source:
Remember that the script, which is placed in the head section, will be executed before the \<body> is rendered. If you want to get elements in the body, it's a good idea to place your script at the end of the body tag.

>:question:
What tag contains the JavaScript code?  
:white_circle: style  
:white_circle: body  
:white_circle: code  
:radio_button: **script**