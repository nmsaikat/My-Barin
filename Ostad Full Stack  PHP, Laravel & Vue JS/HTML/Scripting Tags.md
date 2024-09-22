- ###### The ``<script>`` tag in the ``<head>`` Section contains JavaScript code directly within it. This script declares a function named ``displayData()`` that writes the current date and time to an HTML element with the ID ``date``

 - ###### A ``<button>`` element in the body uses the ``onclick`` attribute to call the ``displayDate()`` function when clicked.

- ###### Another ``<script>`` tag at the end of the body is used to link an external JavaScript file  ``(myScript.js)``. This file would contain JavaScript code that the page can use. The ``src`` attribute specifies the path to the external script file.

- ###### The ``<noscript>`` tag provides an alternative content for users who have JavaScript disabled in their browser. This is important for accessibility and ensuring that essential information or functionality is still available without JavaScript.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Scripting Tags Example</title>
    <script>
      // JavaScript code can be written directly within this script tag
      function displayDate() {
        document.getElementById("date").innerHTML = Date();
      }
    </script>
  </head>
  <body>
    <h1>Welcome to My Web Page</h1>
    <button type="button" onclick="displayDate()">
      Click me to display Date and Time.
    </button>
    <p id="date"></p>
    <!-- External JavaScript file can be linked here -->
    <script src="myScript.js"></script>
    <!-- The noscript tag is for users who have JavaScript disabled -->
    <noscript
      >Your browser does not support JavaScript or it is disabled.
    </noscript>
  </body>
</html>

```