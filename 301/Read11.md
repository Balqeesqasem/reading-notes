# EJS (Embedded JavaScript templating)
     
     EJS is a simple templating language that lets you generate HTML markup with plain JavaScript.


* Features:

     - Fast compilation and rendering
     - Simple template tags: <% %>
     - Custom delimiters (e.g., use <? ?> instead of <% %>)
       Includes
     - Both server JS and browser support
     - Static caching of intermediate JavaScript
     - Static caching of templates
     - Complies with the Express view system

* How to Install ?

     - npm install ejs

* How to use ?
     
     - let ejs = require('ejs'),
       people = ['geddy', 'neil', 'alex'],
       html = ejs.render('<%= people.join(", "); %>', {people: people});

   
