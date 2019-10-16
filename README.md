# csv-json
A handy tool to convert CSV data to JSON data.

## Example Usage

```javascript
var data = `Title,Description
Thing One, Thing One Description.`;

// Convert the CSV to JSON string
var convertedJson = csvjson.convert(data);

// Convert the CSV to JSON object
var parsedJson = csvjson.parsedConvert(data);

```