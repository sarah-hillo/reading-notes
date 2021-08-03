
### API Design Best Practices
- What does REST stand for? representational state transfer
- REST APIs are designed around a web service.
- What is an identifer of a resource? Give an example. URLhttps://adventure-works.com/orders/1
- What are the most common HTTP verbs?The most common operations are GET, POST, PUT, PATCH, and DELETE.
- What should the URIs be based on? is a unique sequence of characters that identifies a logical or physical resource used by web technologies. URIs may be used to identify anything, including real-world objects, such as people and places, concepts, or information resources such as web pages and books.

- Give an example of a good URI.
 Search engines index dynamic URIs (e.g. index.php?page=about) just fine. Using ID numbers in URLs is much easier/faster for grabbing the content from the database. Search Engines prefer unique URLs, so it's best to avoid having parts of the URL with no bearing on what is displayed if possible. Use rel="canonical" if you can't avoid possible duplicates. example.com/1234/my-page in theory should be different to example.com/1234/my-pgae but for most practical purposes they end up returning the same content, like on this site.

- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource

- What status code does a successful GET request return?
A successful GET method typically returns HTTP status code 200 (OK)

- What status code does an unsuccessful GET request return?If the resource cannot be found, the method should return 404 (Not Found).

- What status code does a successful POST request return?
If a POST method creates a new resource, it returns HTTP status code 201 (Created). 
- What status code does a successful DELETE request return?
If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content), 
## Things I want to know more about