apache
======
URL- Uniform Resource Locator
-----------------------------
protocol (e.g. http) + a server name (e.g. www.host.com) + a URL path (e.g. /path/to/page.html) + possibly a query string (e.g. ?arg=value)

a client (e.g. web browser) contents to a server (e.g. your Apache HTTP server), with the specified protocol, and makes a request for a resource using the URL-path.

URL-path may represent a file (e.g. some.html) or some kind of program file (e.g. some.php)

The server will send a response consisting of a status code and, optionally a response body. The status indicate whether the request was successful or an error.

HTTP Status Codes
------------------
1xx - Informational
-------------------
2xx - Successful
-------------------  
  200 - OK

  201 - Created

3xx - Redirection
-------------------
4xx - Client Error
-------------------
  400 - Bad request

  403 - forbidden

  404 - page not found

5xx - Server Error
-------------------
  500 - internal server error

  503 - service is not available

  502 - bad gateway

TEST RALO
END OF PROJECT
