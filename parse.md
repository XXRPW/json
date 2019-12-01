 common use of JSON is when exchanging data to/from a web server
Datas are always string when receiving data from a web server.
using JSON.parse(), the data becomes a JavaScript object.

## Example - Parsing JSON

Imagine receving this text from a web server:
>'{ "name":"John", "age":30, "city":"New York"}'

Using the Javascript function JSON.parse() it can convert this text to a Javascript Object

var obj= = JSON.parse('{"name":"John", "age":30,"city":"New York"}');

## JSON From the Server
you can request JSON from the server by using an AJAX request

