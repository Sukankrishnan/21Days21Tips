Some considerations when checking the API responses

1) **Status code** - Returns the proper response code (1xx, 2xx, 3xx, 4xx, 5xx) and verify the API document for valid status codes.
2) **Status message** - Reflects the status of the response with simple and understandable language.
3) **Response body** - Validate response payloads from the server for structure, data types and content type such as JSON, XML.
4) **Response Headers** - Headers such as Content-Type, Content-Length, server would return the requested format.
6) **Response Time** - Helps to make sure the server does not take too much time to respond the request. Focus on average response time, peak response time and error rate.
7) **Error messages** - Generic information should be in the error message and ensure it does not include any sensitive data.
