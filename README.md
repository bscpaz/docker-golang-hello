<h1 align="center">"Hello-world" with Go and Docker</h1>
<p align="center">This is the first challenger of FullCycle course - Docker module</p>

### Objective:
<p>Create a docker image less than 2Mb of size that prints "FullCycle Rocks" using Go language.</p>

#### How to use the image:
```console
bscpaz@2am:/$ docker run --rm --name fullcycle-rocks bscpaz/hello-world-go:prod 
```

#### How to compile Go project:
```console
bscpaz@2am:/$ go build -o bin/hello
```

#### Building the image:
```console
bscpaz@2am:/$ docker build -t bscpaz/hello-world-go:prod . -f Dockerfile.prod
```
