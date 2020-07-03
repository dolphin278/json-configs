`example-config.js12` is a JSON-based config file.
Try to open it and change field types, both VSC and WebStorm will give you a suggestion on type errors and editing `field3` will give you a
nice suggestion of possible options (since schema for configuration file has an `enum` for that field).

`.js12` extension was chosed arbitrarily to show that files can have
arbitrary extensions and both VSC and WebStorm support mapping JSON schemas to them.

### Links

* [Mapping JSON Schemas to various files in WebStorm](https://www.jetbrains.com/help/idea/json.html#ws_json_schema_add_custom)
* [Mapping JSON Schemas to various files in VS Code](https://code.visualstudio.com/docs/languages/json#_json-schemas-and-settings)
