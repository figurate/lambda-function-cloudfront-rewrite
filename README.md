# lambda-function-nodejs-template
A template repository for NodeJS Lambda functions

## Example:

URL encode '+' characters:

    curl -XPOST "http://localhost:9000/2015-03-31/functions/function/invocations" -d '{"Records": [{"cf":{"request":{"uri":"https://example.com/this+is+a+test"}}}]}'

    {"uri":"https://example.com/this%2Bis%2Ba%2Btest"}
