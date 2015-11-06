# Ruby 2.2, Node 2.4, httpd 2.4

## Sources
This Docker image is cobbled together from the
[ruby 2.2](https://github.com/docker-library/ruby/blob/0cdec78d89e33750a4b796bd2c748f0d5a1ae654/2.2/Dockerfile) Dockerfile, the
[node 4.2](https://github.com/nodejs/docker-node/blob/9992908b275546d9dc1b6063a4d0b7bc500e8b3b/4.2/Dockerfile) Dockerfile, the
[httpd 2.4](https://github.com/docker-library/httpd/blob/5b81416f52f626f087a4a08b50adaa65271ee69c/2.4/Dockerfile) Dockerfile and
a few other assorted bits such as grunt-cli, bower and compass.  This image is custom tailored to run a specific web application.

## Build
This Docker image is built in Travis CI:
<https://travis-ci.org/steasdal/ruby-node>

## Docker Hub
... and deployed to Docker Hub:
<https://hub.docker.com/r/steasdal/ruby-node/>
