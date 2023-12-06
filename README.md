# Day1-Task

HTTP1-VS-HTTP2
HTTP - HyperText Transfer Protocol
IT is an application protocol standardized by WWW- World Wide Web since its invention in 1989. It is needed to transfer data among the networks using different methods and procedures. Version 1.1 was developed by Timothy Berners-Lee in 1989 to exchange information between a client computer and a client computer. Here are some features and differences between the versions of HTTP.

Differences between HTTP/1 and HTTP/2
There should be less network delay to load a web page faster. There is one important concept that an increase in network bandwidth helps improve page load time. We can understand the difference and performance efficiency between the two versions of HTTP depending on different factors. Modern wi-fi networks use high bandwidth signals, so page load time has been increased many times more than the older dial-up networks which take more page load time.

HTTP1
HTTP1.0 is established in 1991 and 1.1 version in 1997.

Earlier, in the 1.0 version, there is only one request and one response was handled for every TCP connection.

In version 1.1, connection reuse is done to enable multiple requests and responses at the same connection.

Pipelining to request several resources at a time is difficult in this type of connection.

Version1.1 provides faster web traffic delivery in comparing to version 1.0.

It is relatively slower than HTTP2.

Loads a single request for every TCP connection.

Header compression has to be requested specially.

Only two connections can be added to a single host.

The binary code-based protocol needs to be converted back when getting downloaded.

SSL security is not required but recommended because of its digest Authentication.

HTTP 1.0 defines 16 status codes and the error prompt is not specific enough relatively to version 2.

HTTP 1.1 defines 24 status codes at a time and also includes a warning header field to carry extra information about the status of a message.

Authentication is encoded using base 64 and there is a threat due to this in version 1.0. But Digest Authentication and NTLM Authentication methods are implemented in version 1.1 which is relatively secured.

Cache-control conditional headers and entity tags support caching techniques efficiently. Adoption of HTTP/2 is done by modern browsers by default.

HTTP2
HTTP2 is established in 2015.

Much faster than HTTP1 because of its high Page Load speed.

Avoids network delay because of its multiplexing feature where requests and responses can be implemented at a time.

Performance Optimization provides support to deliver the pages faster than in first version.

It is supported and loaded fast in all the major browsers including Chrome, Edge, Firefox, and all others.

Six connections can be added to a single host.

Header compression is included by default in HTTP2 as it uses HPACK.

Uses SSL/TL security encryption for communications with minimum key size TLS 1.2.

Headers and status codes work the same as in HTTP 1.1.

TLS authentication features help in connection errors and improper security reasons.

The cache maintenance feature is enhanced with the server push mechanism which helps to cancel the pushed stream if it already exists in the local cache.

Objects and its internal representation in Javascript
Object
An object is a stand-alone entity or element, which contains different properties and belongs to a single type. It can also be defined as an unordered collection of related data of primitive or reference types. Every data item is an object in Javascript which can be strings, numbers, booleans, dates, null, undefined, and math expressions as well. The context of an object would be in the form of Key-value pairs where keys can be variables or functions and also called properties and methods. Functions that receive properties and return values are objects themselves.

For instance, we can code student details in an object named ‘Student’ with the properties of student name, email-id, course-name, duration, and fees-amount. We can say this as an unordered set of name/value pairs. In Javascript, the object is an important data type and works as the building block for modern code.

Internal Representation
An object begins with ’{‘ left brace and ends with ‘}’ right brace. In this object, the name is followed by a ‘:’ colon and value. Each name/value pairs are separated by a ‘,’ comma. Usually, we do not create an object inside an object, instead, we use literal syntax {}. In this, we can again have keys and properties. A string representation of an object is called Object Object! All the objects are stored on a heap of memory.

In Javascript, an object is a reference data type. Variables that are assigned a reference value are given a pointer to that value. That pointer references the location in the memory where the objects are stored. So, the variables do not actually store the value. Keys can be variables or functions and are called properties and methods.

Objects can also be created using constructors in Javascript, which creates a prototype pattern. It creates an object wrapper for the given values. The ‘new’ keyword allows initializing new objects. In Object-Oriented Programming languages, Constructors provide a template for creating objects. The object definition helps to define a set of properties and methods that would be common to all objects. Having more than one function in a class with the name of the constructor gives an error. Objects can also be created using the prototyping method.
