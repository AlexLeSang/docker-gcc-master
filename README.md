![Docker Image CI](https://github.com/AlexLeSang/docker-gcc-master/workflows/Docker%20Image%20CI/badge.svg?branch=master)

# What is this?
`Dockerfile` for latest gcc (from 'master')

# For whom is this usefull?
For people who want to get latest gcc compiler suite (gcc, g++, gfortran, go) without installing them into your system.

# Docker image
[GCC master docker hub](https://hub.docker.com/repository/docker/alexlesang/gcc-master) 

# References and sources
[GCC docker hub](https://hub.docker.com/_/gcc/) 

## Versioning
Version of the image comes from the following command:
```
docker run --rm -ti -w /usr/src/gcc gcc-trunk gcc --version | head -n1 | awk '{print $3,$4}' | tr ' ' '-'
```


