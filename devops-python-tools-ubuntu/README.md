# [KhulnaSoft, Ltd - DevOps Python Tools](https://github.com/BuildScale/DevOps-Python-tools)

[![Docker Build (Ubuntu)](https://github.com/BuildScale/DevOps-Python-tools/actions/workflows/docker_pytools_ubuntu.yaml/badge.svg)](https://github.com/BuildScale/DevOps-Python-tools/actions/workflows/docker_pytools_ubuntu.yaml)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/40a82d53f3394f4b99aa6eccb08e3c8d)](https://www.codacy.com/gh/BuildScale/DevOps-Python-tools/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=BuildScale/DevOps-Python-tools&amp;utm_campaign=Badge_Grade)
[![GitHub stars](https://img.shields.io/github/stars/buildscale/devops-python-tools.svg)](https://github.com/BuildScale/DevOps-Python-tools/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/buildscale/devops-python-tools.svg)](https://github.com/BuildScale/DevOps-Python-tools/network)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20OS%20X-blue.svg)](https://github.com/BuildScale/DevOps-Python-tools#hari-sekhon-pytools)
[![DockerHub](https://img.shields.io/badge/docker-available-blue.svg)](https://hub.docker.com/r/buildscale/pytools/)
[![DockerHub Pulls](https://img.shields.io/docker/pulls/buildscale/pytools?label=DockerHub%20pulls&logo=docker&logoColor=white)](https://hub.docker.com/r/buildscale/pytools)

### Hadoop, Spark / PySpark, HBase, Pig, Ambari, IPython and Linux Tools ###

A few of the Hadoop, Spark & Linux tools I've written over the years.

See a list of included programs with descriptions on the [GitHub project page](https://github.com/BuildScale/DevOps-Python-tools#pytools).

Running the docker container without arguments will show just the list of programs:

```
docker run buildscale/pytools
```

Run any given program:

```
docker run buildscale/pytools <program> <args>
```

All programs have `--help` to list the available options.

For many more tools see the [Tools](https://github.com/BuildScale/DevOps-Perl-tools) and [Advanced Nagios Plugins Collection](https://github.com/BuildScale/Nagios-Plugins) repos which contains many Hadoop, NoSQL, Web and infrastructure tools and Nagios plugins which have docker builds in the adjacent directories.

KhulnaSoft, Ltd

Cloud & Big Data Contractor, United Kingdom

https://www.linkedin.com/company/khulnasoft

Related Docker images can be found for many Open Source, Big Data and NoSQL technologies on [my DockerHub profile](https://hub.docker.com/r/buildscale). The source for them all can be found in the [master Dockerfiles GitHub repo](https://github.com/BuildScale/Dockerfiles/).
