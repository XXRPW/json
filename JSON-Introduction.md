JSON is shorten for JavaScript Object Notation
JSON is a syntax for sorting and exchanging data
JSON is text, written with JavaScript object notation

### Exchanging Data
If you have data stored into a javascript Object you can change it to JSON and send it to a server

var myObj = {name: "John", age : 31, city:"New York"};
var myJSON = JSON.stringify(myObj);
window.location = "demo_json.php?x=" + myJSON;

### Receiving Data
When you receive a JSON format, you can convert it to a Javascript object

var myJSON = '{"name":"John", "age":31, "city":"New York"}';
var myObj = JSON.parse(myJSON);
document.getElementById("demo").innerHTML = myObj.name;

### Storing Data
The data needs to be in certain format to store data, and text is one of the legal formats.
