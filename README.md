# Docker/Proftpd

Dockerfile to create a simple proftpd server.

## Instant Usage

~~~
docker pull theoraculo/docker-proftpd
docker run -p 21:21 -p 20:20 -e USERNAME=user -e PASSWORD=pass -v `pwd`/ftp:/ftp -it -d theoraculo/docker-proftpd
~~~

Note: if you use boot2docker on Mac OSX, be sure to connect to the VM when testing like,

`ftp -p $(boot2docker ip) 21`.

# References

* [Docker Homepage](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)
* [Docker Userguide](https://docs.docker.com/userguide/)
* [ProFTP Homepage](http://www.proftpd.org/)


