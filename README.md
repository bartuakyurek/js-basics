# js-basics
Here is my attempt to learn javascript







### Miscellenous
- To integrate Javascript code, we need a script element and it can be added to either head or body section of the html file. 
- The best practice is to add the script element at the end of the **body** section, after all the elements: ``<script> </script>``
- Add the attributes inside the brackets, e.g. for source attribute: ``<script src='index.js' > </script>``, *not* between the tags.
- Node is a runtime environment for executing Javascript code. Head over terminal and type ``node index.js`` (assuming you have index.js) to execute the script.

### Coding Tips
- You can check a variable type with ``typeof`` e.g. ``console.log(typeof some_variable)``
- Use curly brackets to declare an *object literal*, e.g. ``let person = { name: 'bartu', age: 26 };``
- Create an array literal with empty square brackets, e.g. ``let some_array = [];``
### Tool Tips
- Inside VSCode, if you type "!" and press tab on an html file, it fills the boilerplate.
- Install Live Server in VSCode and right click on an html file, select "open with live server"