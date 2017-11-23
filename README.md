# go-simple-web-server
A simple web server written in Go

### Build and run

```
$ go build
$ ./go-simple-web-server
```

### Usage

When the server runs, it listens to port 5000. You can perform requests and the server will happily return 200 OK:

```
$ curl -I localhost:5000

HTTP/1.1 200 OK
Date: Thu, 23 Nov 2017 09:32:22 GMT
Content-Length: 33
Content-Type: text/plain; charset=utf-8
```
