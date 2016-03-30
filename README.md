# HTTP Response Codes
The is a simple interface that lists all possible HTTP Response codes thus eliminating the need to hardcode magic numbers. 

## Usage
Nothing can be simplier
```php
return new Response("Server error", HTTPResponseCodes::REQUEST_URI_TOO_LONG)
```