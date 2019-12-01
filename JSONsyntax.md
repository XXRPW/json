### JSON Syntax rules

JSON syntax follows the JavaScript Object Notation syntax
>Data is in name/value pairs
>Data is seperated by commas
>Curly braces hold objects
>Square brackets hold arrays

## JSON Data - A Name and a Value

JSON data is written in name/value paris

"name":"John"

and each seperated with double quotes

JSON names requier double quotes but JavaScript names don't

## JSON - Evaluates to JavaScript Objects
in JSON, keys MUST be in doulbe quotes represented as a string
but in JavaScript, quotes may be in strings, numbers, or identifier names

## JSON values
in JSON, values must be one of the following data types:<br>
a string<br>
a number<br>
an object<br>
an array<br>
a boolean<br>
null<br>

but in JavaScript values can be all of the followings above and JavaScript expression.

## JSON uses JavaScript Syntax 
In within JavaScript you can create an object an object and assign data to it like this

>var person = {name : "John", age:31, city: "New York"};

and get the data out like this

>person.name;

it can be also accessed like this:
person["name"];

Data can be modified like this

>person.name = "Gilbert";

it can also be modified like this

>person["name"] = "Gilbert";

tip

> The file ttype just be in .json
>The MIME type for JSON text is "application/json"

"
