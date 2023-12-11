## HTTP Methods:

HTTP defines several methods, or verbs, that indicate the desired action to be performed on a resource.  
Common methods include:  
 - **GET**: Retrieve data from a specified resource.  
 - **POST**: Submit data to be processed to a specified resource.  
 - **PUT**: Update a resource or create a new resource if it does not exist.  
 - **DELETE**: Request the removal of a resource.  
 - **HEAD**: Retrieve only the headers of a resource, without the actual data.  
 - **OPTIONS**: Request information about the communication options available for the target resource.

## Status Codes:
HTTP responses include status codes that indicate the outcome of the request. Common status codes include:  
- **1xx (Informational Response)(100-199):**  
    They are informational, and are not as commonly encountered as other status code categories. 

    | Status Code | Message |  
    |-------------|---------|  
    |    100      | Continue|    
    |    101      | Switching Protocal        |    
    |    102         |     Processing    |  

 - **2xx (Successful)(200-299):**   
 The request was successfully received, understood, and accepted.

    | Status Code | Message |
    |-------------|---------|
    |    200      |  OK       |  
    |    201      |  Created  | 
    |    202      |  Accepted
    |    203      | Non-Authoritative Information
    |    204      |  No Content|
    |    205      |  Reset Content


 - **3xx (Redirection)(300-399)**:   
 Further action needs to be taken to complete the request.  
    
 - **4xx (Client Error)(400-499)**:   
 The request contains bad syntax or cannot be fulfilled.   
    | Status Code | Message |
    |-------------|---------|
    |    400      |  Bad Request      |  
    |    401      |  Unauthorized | 
    |    403      |  Forbidden
    |    404      | Not Found
    |    405     |  Method Not Allowed|
    |    408      |  Request Timeout
 - **5xx (Server Error)(500-599)**:  
 The server failed to fulfill a valid request.  
    | Status Code | Message |
    |-------------|---------|
    |    500      |  Internal Server Error     |  
    |    501      |  Not Implemented | 
    |    502      |  Bad Gateway
    |    503      | Service Unavailable
    |    504      | Gateway Timeout|
    |    505      |  HTTP Version Not Supported


