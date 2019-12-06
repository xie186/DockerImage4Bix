


```

#only [a-z0-9-_.] are allowed for -t 
sudo docker build -t xie186/rbam2bigwig:v0.1 .

sudo docker run -it xie186/rbam2bigwig:v0.1 /bin/bash
sudo docker run -it xie186/rbam2bigwig:v0.1 bash

```

## List images

```
$ sudo docker  images
[sudo] password for xie186:
REPOSITORY           TAG                 IMAGE ID            CREATED              VIRTUAL SIZE
v0.1                 latest              c468c2a0d726        2 days ago           1.113 GB
xie186/rbam2bigwig   latest              c468c2a0d726        2 days ago           1.113 GB
xie186/rbam2bigwig   v0.1                c468c2a0d726        2 days ago           1.113 GB
rocker/rstudio       latest              951b7b4dd26c        5 days ago           1.357 GB
rocker/tidyverse     latest              29c6dba64587        7 days ago           2.101 GB
ubuntu               16.04               404f7485ee49        9 days ago           122.6 MB
hello-world          latest              9f5834b25059        11 months ago        1.84 kB
bmpvieira/guix       latest              8b55e28e3811        3.583688 years ago   402.2 MB
```

## Build Images

```
sudo docker push xie186/rbam2bigwig:v0.1

$ sudo docker push xie186/rbam2bigwig:v0.1
The push refers to a repository [xie186/rbam2bigwig] (len: 1)
c468c2a0d726: Image already exists
a7127aa58da1: Image successfully pushed
67cfafc860dd: Image successfully pushed
1adc77a4e36b: Buffering to Disk
1adc77a4e36b: Image successfully pushed
14eabb270418: Image successfully pushed
12ae297bbd92: Image successfully pushed
f2349fada49c: Image successfully pushed
ad170d2875d9: Image successfully pushed
c4be2aec2466: Image successfully pushed

```
