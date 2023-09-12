# Link Extractor: Stage 1

A basic page scraping script that prints out all the hyper references of the given web page.

## Changes from the previous stage

* Adds a `Dockerfile` to fix various issues describe in the previous stage

## Try it out

```shell
docker image build -t linkextractor:stage1 .
docker container run -it --rm linkextractor:stage1 http://example.com/
docker container run -it --rm linkextractor:stage1 http://odu.edu/
```
