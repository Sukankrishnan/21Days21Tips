Understand the status code response from the server. Sometimes, the status code and the status message are not relevant. Follow API documentation (Actual result vary from the documentation - an example is given below) or ask for help when it is unclear.

The status code indicates the response code along with the response sent by the web server. It is a three-digit code that indicates various information.

1. **1xx – Informational** – It indicates that the server has received the request and is in the process of sending the response. (100- Continue, 101- Switching protocols)
2. **2xx – Success** – It indicates the request was successfully received and accepted. (200 – OK, 201 – Created)
3. **3xx – Redirection** – It indicates the URL has been moved and shows the redirection. (301 – Moved permanently, 302 – Found, 307 – Temporary redirect)
4. **4xx – Client error** – It indicates the client has made an error while sending a request. (404- not found, 400 – bad request)
5. **5xx – Server error** – It indicates the server finds the error while processing the request. (500 – internal server error, 502 – bad gateway, 503 – service
unavailable)

Let us take an example of Swagger PetStore API on how the API documentation and the actual result varies of status code and message.

URL: https://petstore.swagger.io/#/store/deleteOrder

![image](https://github.com/user-attachments/assets/8fbfe368-c349-4183-a7e4-8ed6edd9902c)
