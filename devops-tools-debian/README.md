# KhulnaSoft, Ltd - DevOps Tools

[![DockerHub Tools](https://img.shields.io/badge/DockerHub-buildscale%2Ftools-blue)](https://hub.docker.com/repository/docker/buildscale/tools)

Hundreds of DevOps related programs from my main DevOps tools repos on [my Github](https://github.com/buildscale), including:

- [DevOps Python Tools](https://github.com/BuildScale/DevOps-Python-tools)
- [DevOps Perl Tools](https://github.com/BuildScale/DevOps-Perl-tools)
- [DevOps Bash Tools](https://github.com/BuildScale/DevOps-Scripts)

Running the docker container without arguments will show just the list of programs:

```
docker run buildscale/tools:debian
```

Run any given program:

```
docker run buildscale/tools:debian <program> <args>
```

All programs have `--help` to list the available options.

KhulnaSoft, Ltd

Cloud Big Data Contractor, United Kingdom

https://www.linkedin.com/company/khulnasoft

Related Docker images can be found for many Open Source, Big Data and NoSQL technologies on [my DockerHub profile](https://hub.docker.com/r/buildscale). The source for them all can be found in the [master Dockerfiles GitHub repo](https://github.com/BuildScale/Dockerfiles/).
