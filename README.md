# JvServe

JvServe is project intended for learning more nitty gritty details of how web servers work. It places special focus on not utilizing any external web based libraries, as well as the management of multi-threading. The project is intended to be A lightweight Web Server that is easy to implement but handles the web-sockets and multi-threading.

## Goals

### Initial Goals

- Server can listen on a port for incoming requests.
- Server can process those requests on their own thread.
- Server can respond to any HTTP GET requests with an html file.

### Stretch Goals

- Server can respond to any HTTP RESTful request appropriately.
  - GET requests
  - POST requests
  - PUT requests
  - DELETE requests
- Server can be implemented as a library in other projects.
  - Port can be set dynamically
  - Endpoints can be set dynamically
  - Responses for each endpoint can be set dynamically

### Goals in a Galaxy Far Far Away

- Server utilizes annotations for implementation on other projects
- Server allows for varied levels of security depending on dynamic settings

## Authors

- Conner Steele
- Michael Zide
