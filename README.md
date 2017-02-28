# QPKG Gitlab

QNAP Dockerized Gitlab

## Build it

```
$ docker run -it --rm -v ${PWD}:/src dorowu/qdk2-build
Creating archive with data files...
tar:   30kB 0:00:00 [58.2MB/s] [====================================================>        ] 87%            
Creating archive with control files...
Creating QPKG package...
-rw-r--r-- 1 1000 1000 27363 Feb 28 17:10 gitlab_8.13.3.qpkg
```

You will find `*.qpkg` in the current folder or [download here](http://qnap-ubuntu.dorowu.com/qpkg/gitlab_8.16.6.qpkg)
