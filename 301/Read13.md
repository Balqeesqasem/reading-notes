# Sending form data 

- Client/server architecture:
client (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol. The server answers the request using the same protocol.

 - On the client side: defining how to send the data:

    * The action attribute : The action attribute defines where the data gets sent.
    * The method attribute : The method attribute defines how data is sent.
       - The GET method :
           is the method used by the browser to ask the server to send back a given resource.

       - The POST method:
            the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request.

    * Viewing HTTP requests :
         1. Open the developer tools.
         2. Select "Network"
         3. Select "All"
         4. Select "foo.com" in the "Name" tab
         5. Select "Headers"            
