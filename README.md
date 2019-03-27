### Dockerfiles for opensuse/leap

This repo contains dockerfiles written using the opensuse/leap as base image.
This repo is for practicing docker.

#### Ideas for new docker images for opensuse/s390x

- Write the ruby on rails dockerfile (We already have a hello-nodejs so this would be a good addition)
- Write the Chef Dockerfile (using the Ruby base image). We already have an Ansible image and chef seems to be the other most popular DevOps tool so it would be nice to have it.
- Write the ZeroMQ dockerfile (would be a good addition alongside rabbitmq and memcached already). This existing image can be used as a reference for porting it.
- Write a CockroachDB dockerfile. We already support couchDB and it would be another good addition to have cockroachDB since it is one of the most fastest growing SQL DB
