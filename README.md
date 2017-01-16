# Simple Docker Redirect
[![](https://images.microbadger.com/badges/image/grahamdigital/simple-redirect.svg)](https://microbadger.com/images/grahamdigital/simple-redirect "Get your own image badge on microbadger.com")
[![CircleCI](https://circleci.com/gh/GrahamDigital/simple-docker-redirect/tree/master.svg?style=svg)](https://circleci.com/gh/GrahamDigital/simple-docker-redirect/tree/master)

This container will redirect all requests to an second domain name.

Example
```
docker run -d \
    -e PROTOCOL=http \
    -e REDIRECT_TO="github.com" \
    grahamdigital/simple-redirect
```
