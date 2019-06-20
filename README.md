echosrv
=====

A simple HTTP echo server. Mostly useful as a placeholder service.

## Endpoints


```
$ http localhost:2222/
HTTP/1.1 200 OK
Content-Length: 19
Content-Type: text/plain; charset=utf-8
Date: Thu, 20 Jun 2019 16:15:12 GMT

Hello from echosrv!

$ http localhost:2222/liveness
HTTP/1.1 200 OK
Content-Length: 0
Date: Thu, 20 Jun 2019 16:15:36 GMT

$ http localhost:2222/readiness
HTTP/1.1 200 OK
Content-Length: 0
Date: Thu, 20 Jun 2019 16:15:39 GMT
```
