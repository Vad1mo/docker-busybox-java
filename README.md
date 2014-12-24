## Minimal Docker image with Java

Basic [Docker](https://www.docker.com/) image to run [Java](https://www.java.com/) applications.
This is based off [Busybox](http://www.busybox.net/) to keep the size minimal (about 25% of an ubuntu-based image).

### Tags

* `latest` or `8`: Oracle Java 8 (Server JRE)
* `7`: Oracle Java 7 (Server JRE)
* `jdk8`: Oracle Java 8 (JDK)
* `jre8u5`: Oracle Java 8 update 5 build 13 (Server JRE)
* `jdk7`: Oracle Java 7 (JDK)

### Usage

Example: 

    docker run -it --rm jeanblanchard/busybox-java:8 java -version
