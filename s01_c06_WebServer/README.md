# Web Server

Create New Directory
--------------------

```
mkdir Web
cd Web/
subl web.js
```

Web Requests
------------

After the server is running, visit http://localhost:3000 in a web browser

`BeginningNode/Web/`[web.js](BeginningNode/Web/web.js)

```
$ node web.js
Server running at http://localhost:3000
GET /
GET /about
GET /team.html
GET /product/24
```

HINT: CTRL + C to stop browser after changes

Dynamic Requests
----------------

`BeginningNode/Web/`[web02.js](BeginningNode/Web/web02.js)

```
$ node web02.js
GET /product/24
GET /
GET /about
```