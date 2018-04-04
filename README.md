
[Klar](https://github.com/optiopay/klar) is a CLI for performing a [Clair](https://github.com/coreos/clair) security analysis.

This repository simply uses a multi-stage Dockerfile to build the Klar container image. You need to run docker build against docker daemon version 17.05 or greater. 

Adds the AWS CLI to allow login to ECR.

## To build klar docker image:

```
docker build -t klar .
```

## To use the image

See [Klar Usage](https://github.com/optiopay/klar#usage)

