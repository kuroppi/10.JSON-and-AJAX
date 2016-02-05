Using the jQuery .load() Shorthand method

Using jQuery .load() to:

- Open index.html.
- Within the script tag, replace the existing comment with a document ready function.
- Write the necessary event handlers to handle the click event for each of the 3 links within the index.html page.
- When each link is clicked, the corresponding section within the solutions.html page should be loaded into the div tag uniquely identified as solution.

Part 2 - Using the jQuery .get() Shorthand Method

Using the jQuery .get() shorthand method to programmatically load XML data into a web page using a server-side script such as a PHP file as an intermediary. This example will connect directly to an XML file and retrieve its contents.

- Open index.html.
- Within the <script> tag, replace the existing comment with a document ready function.
- Use the $.get() method to point to the team.xml file. Upon successful load, it will call a function to execute some code.
- Within the function, use method chaining to iterate through each of the child nodes in the management node.
- Within the .each() method, append the contents of the name, title, and bio nodes to the div element uniquely identified as team. Don’t forget to concatenate some simple HTML markup to help format the text on the web page.

Part 3 - Using the jQuery .getJSON() Shorthand Method

Using the jQuery .getJSON() shorthand method to programmatically load JSON data into a web page.

- Created a JSON file with each object having 5 or more items. Each item has at least 2 sets of key/value pairs.
- Open index.html.
- Within the <script> tag, replace the existing comment with a document ready function.
- Use the $.getJSON() method to point to the JSON file that you just created. 
- Use a set of nested .each() methods to iterate through the object and then the key/value pairs too.  Display the values of each pair within the div element uniquely identified as result.

Part 4 - Using the jQuery .ajax() Shorthand Method

Using the jQuery .ajax() shorthand method to programmatically load XML or JSON data into a web page using the .ajax() shorthand method using the following options:

- type
- url
- timeout
- datatype
- beforeSend: display a loading message on the page
- error: display a jQuery UI dialog box with an error message inside
- success: this is where you’ll process the data returned




