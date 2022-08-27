# simple-docker-test

## build

```sh
docker build -t (basename $PWD) .
```

## run

```sh
docker run -p 3000:3000 (basename $PWD)
```
