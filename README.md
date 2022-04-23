# Simple User Admin Service
_no Auth, demonstration purposes only..._
Small Web Service running in Go.  To start the service use command `go run cmd/simple-service/main.go` from the root project directory.

Open Postman or similar, and cURL to `http://localhost:8000/` to perform the following CRUD operations:
```shell
POST: "/users"
GET: "/users/:id"
PUT: "/users/:id"
DELETE: "/users/:id"
```