# docker-meta
MeTA in a Docker container

This docker scripts is to create a working environment for the Coursera class [Text Retrieval and Search Engines](https://class.coursera.org/textretrieval-001).

## Requirements

* Docker 1.5+ (Should work fine with older versions. Haven't tried it myself.)

## Building the image

To build the docker image it should be sufficient to call

```sh
sudo ./build.sh
```

## Starting into an interactive shell

```sh
sudo ./docker-meta.sh
```

The compiled meta packages is located in /home/developer/git/meta.
