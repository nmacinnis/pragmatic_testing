# pragmatic_testing
lightning talks on the topic of pragmatic testing, hosted on [github pages](http://nmacinnis.github.io/pragmatic_testing/).


if you are reading this probably just go there instead eh


## running with jekyll and docker

This seems to work:

```
docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll:pages jekyll serve
```
