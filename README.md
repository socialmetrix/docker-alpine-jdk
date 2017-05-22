This is the configuration of Dockerfile for  Alpine Linux 3.5 with the stable version of glibc and jdk oracle. Inside of the folder be find the  Dockerfile whith the version of jdk  according to name of the folder. For example, jdk7 have the version of Oracle jdk7.


If you use these  Dockerfile, you are accept the license of Oracle JDK http://www.oracle.com/technetwork/java/javase/terms/license/index.html


Docker Hub of Alpine Linux https://hub.docker.com/_/alpine/
Repository of glibc https://github.com/sgerrand/alpine-pkg-glibc
Oracle JDK http://www.oracle.com/technetwork/java/javase/overview/index.html



<strong>Usage</strong>


**~#git clone** https://github.com/socialmetrix/docker-alpine-jdk.git

**~#cd docker-apline-jdk**

For use jdk7:

**~# cd jdk7**
**~# docker build . socialmetrix/docker-alpine-jdk:version
~# docker run -it -rm socialmetrix/docker-alpine-jdk:version
**


~
