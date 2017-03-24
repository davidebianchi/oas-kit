# Options documentation

Parameter|Type|Input/Output|Description
|---|---|---|
components|Boolean|Input|Command-line flag to indicate unresolve information should be displayed
context|Array|Output|The context stack of associated with errors in a validation step
debug|Boolean|Input|Flag to enable debug mode, adds specification-extensions
encoding|String|Input|Encoding to use when reading/writing files
expectFailure|Boolean|Input|Flag to invert the status of a validation step
externals|Array|Output|Information required to unresolve a resolved definition back into its component parts
fail|Boolean|Input|Command-line flag used by `testRunner`
file|String|Input|Used to pass filename back to `testRunner`
help|Boolean|Reserved|Command-line flag to display help
openapi|Object|Output|The OpenApi 3.x definition returned from a conversion step
origin|String|Input|The URL of the definition, set by convertUrl method
original|Object|Input|Used by `testRunner` to round-trip the original definition
outfile|String|Input|The output file to write to
patch|Boolean|Input|Flag to fix-up minor errors in the source definition before conversion
quiet|Boolean|Input|Command-line flag used by `testRunner`
resolve|Boolean|Input|Flag to enable resolution of external `$ref`s.
stop|Boolean|Input|Command-line flag used by `testRunner`
source|String|Output|
sourceYaml|Boolean|Output|Flag set if the source string, URL or stream contained a YAML formatted definition
url|String|Input|URL of the original definition, used when reading a file to create `x-origin` extension 
valid|Boolean|Output|The result of a validation step
verbose|Boolean|Input|Increase verbosity, e.g. show HTTP GET requests
version|Boolean|Input|Command-line flag to show version information
yaml|Boolean|Input|Flag to read and write YAML, default JSON