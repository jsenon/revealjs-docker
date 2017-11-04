# revealjs-docker

A dockerized version of the [Reveal JS](https://github.com/hakimel/reveal.js)

## Build

```sh
docker build . -t jsenon/revealjs:0.1
```

## Launch

```sh
docker run  --name revealjs -d -p 8000:8000 -v $PWD/index.html:/reveal.js/index.html  jsenon/revealjs:0.1
```

### TIPS

Automatically build on dockerhub
