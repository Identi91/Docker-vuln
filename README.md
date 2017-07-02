
[Klar](https://github.com/optiopay/klar) is an intergration of CoreOS [Clair](https://github.com/coreos/clair) and Docker Registry.

This repository simply uses a multi-stage Dockerfile to build the Klar container image. You need to run docker build against docker daemon version 17.05 or greater. 

## To build klar docker imag:

```
docker build -t klar .
```

## To use the image

See [Klar Usage](https://github.com/optiopay/klar#usage)

