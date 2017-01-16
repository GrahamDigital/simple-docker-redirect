# Simple Docker Redirect

This container will redirect all requests to an second domain name.

Example
```
docker run -d -e PROTOCOL=http -e REDIRECT_TO="github.com" grahamdigital/simple-redirect
```
