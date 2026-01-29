# HTTP Request

**Description:** Trigger when an HTTP request is received matching the path and method of the trigger.

**Inputs:**

* Type (GET or POST)
* Store request in variable
* Store response in variable
* Store request body in variable (shown if type is POST)
* Query Parameters list (each with Name and Store text in variable)
* Headers list (each with Name and Store text in variable)

**Variable Types:**&#x20;

* HTTP Request
* HTTP Response
* Text
* JSON

**Behaviour:** Stores request and response objects, extracts query parameters and headers into specified variables, optionally stores POST request body. Then continues with the next actions.
