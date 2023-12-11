# **HTTP**
    HTTP stands for Hyper Text Transfer Protocal. It is responsible to establish communication between web servers and clients. Every request is different from one another.  
    HTTP is stateless protocal, which means the server does not retain information about the client's previous requests. The previous or the next request made by the users are independent. This simplifies communication between the client and server but requires additional mechanisms, such as cookies or sessions, to maintain state or context between requests.
### Working Mechanism of HTTP
    The working mechanism of HTTP (Hypertext Transfer Protocol) involves a series of steps in a request-response cycle between a client (usually a web browser) and a server. Here is a detailed breakdown of the key components in the working of HTTP:
1.  Request-Response Model:  
    Communication in HTTP revolves around the request-response model. A client sends an HTTP request to a server, and the server responds with the requested data or an acknowledgment of the action taken.
    
2. URL (Uniform Resource Locator):  
    HTTP requests include a URL that specifies the resource to be retrieved or acted upon. The URL typically consists of the protocol (HTTP), domain name, path, and optional query parameters.
3. Headers:  
    Both HTTP requests and responses include headers, which provide additional information about the request or response. Headers can convey details such as content type, content length, cookies, caching directives, and more.

4. State Management:
    HTTP is stateless, but applications often require maintaining state. Techniques like cookies and sessions are used to store information on the client or server side to create a sense of continuity between requests.
5. Server Processing:
    The server receives the HTTP request and processes it based on the provided method, URL, and headers. The server performs the necessary actions, such as retrieving data, updating resources, or generating dynamic content.

# **HTTPS**
    HTTPS (Hypertext Transfer Protocol Secure) is an extension of HTTP that uses encryption protocols (such as TLS/SSL) to secure the communication between the client and server.  It adds a layer of security to the data exchange between a client (such as a web browser) and a server, protecting the confidentiality and integrity of the transmitted information


In summary, HTTP is a protocol that facilitates communication between clients and servers on the World Wide Web.  It adds a layer of security to the data exchange between a client (such as a web browser) and a server, protecting the confidentiality and integrity of the transmitted information.It outlines the format of messages, defines methods for interacting with resources, and establishes a set of rules for reliable data exchange, forming the backbone of web-based communication.

### If you want to know further about HTTP methods and Status follow this link. [More about HTTP](./RequestMethodAndStatusCode/readme.md)