# Simple Docker Redirect

This container will redirect all requests to an second domain name.

Example
```
docker run -e PROTOCOL=http -e REDIRECT_TO="github.com/GrahamDigital/simple-docker-redirect" grahamdigital/simple-redirect
```
