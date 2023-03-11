## The \<script> Tag

The \<script> tag can take two attributes, **language** and **type**, which specify the script's type:

>###### |HTML|  
>\<script **language**="javascript" **type**="text/javascript"><br/>
\</script>

:information_source:
The **language** attribute is deprecated, and should not be used.  

In the example below, we created an alert box inside the script tag, using the **alert()** function.  

>###### |js|
><html>
   <head>
     <title></title>
     <script type="text/javascript">
       alert("This is ab alert box!");
     </script>
   </head>
</html>

**Result:**

![imagem]()

:information_source:
The **type** attribute: <script type="text/javascript"> is also no longer required, as JavaScript is the default HTML scripting language.