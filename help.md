Strongly recommended
Do not use the JSON-min.js, the library has wireless recursive errors

Now parse.js directly in the function Parse (str) functions in str.parseJson, replace this:
```
var obj = null;
try
{
obj = JSON.parse(str);
}
```
