# Part One: Solidify Terminology»

### In your own terms, define the following terms:
### What is HTTP?
HTTP or the "hypertext transfer protocol" is a protocol, or set of guidelines, for sending requests (including data) over the web. All requests made with HTTP are sent as text.
### What is a URL?
Universal Resource Locator.
URL is comprised of a few things: protocol, subdomain/domain/hostname, port number, resource /, and query for additional data passed.

### What is DNS?
The system connecting the hostname to the server/IP.

### What is a query string?
Something we can pass in our HTTP request, and a way to pass arguments to a server. They are key/value pairs.

### What are two HTTP verbs and how are they different?
GET - makes requests which don't change any data on the server.

POST - Requests which make a change on the server.

GET is infinitely repeatable (as it yields the same result every time). Each individual POST request makes a change.

### What is an HTTP request?
HTTP requests are how we request data from web servers. They contain data such as: the method (GET or POST), http version, resource URL, additional headers with metadata such as language date and so on.

### What is an HTTP response?
What a server sends back after a request.
Every response includes:
-the http version
-the response code or status code
-headers (meta-data)
-The body of the response -- the information to return and/or display

### What is an HTTP header? Give a couple examples of request and response headers you have seen.
HTTP headers include metadata such as content type, date/time, cookies, caching info, browser language setting, and hostname that it is going to/coming form.


### What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
A request gets made with the http protocol from the browser. The browser uses DNS to send the request via the hostname to the intended server. The Server sends a response based on the requested resource.
