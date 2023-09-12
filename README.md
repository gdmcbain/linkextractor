# Link Extractor: stage 2

A basic page scraping script that prints out all the hyper references and anchor texts of the given web page.

## Changes from the previous stage

* Paths are normalized to full URLs
* Reporting both links and anchor texts
* Usable as a module in other scripts

## Try it out

```shell
docker image build -t linkextractor:stage2 .
docker container run -it --rm linkextractor:stage2 http://example.com/
docker container run -it --rm linkextractor:stage2 http://odu.edu/
```
