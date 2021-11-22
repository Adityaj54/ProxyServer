# Reverse_Proxy_Server
## DNS
  Apache will listen on a user-specified socket for HTTP requests and return a properly-formatted response with the preferred IP by calculating the Round trip time(ping)
## WEB PROXY

 Internal network proxy server
 Used the HTTP Protocol (RFC 2616) to build application using Java which allows the Secure Sockets HTTP transactions by hiding the original IP.
 Dealt with the Packets at the byte level in java using the Network Byte order (RFC 1700)
 
### Sample input 
GET /index.html HTTP/1.1<br>
Host: www.berkeley.edu<br>
User-Agent: Mozilla/5.0<br>
Accept: text/xml,application/xml,application/xhtml+xml,text/html*/*<br>
Accept-Language: en-us Accept-Charset: ISO-8859-1,utf-8<br>
Connection: keep-alive 


### Sample looging

DNS LOOKUP: www.berkeley.edu<br>
Preferred IP: 22.33.44.55

### Output
  HTML
