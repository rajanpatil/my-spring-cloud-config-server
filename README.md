# my-spring-cloud-config-server
This is example of sping cloud config server.

### Pre-requisite
* Java 8
* Maven 3
* Git
* `my-config` repo with `<app name>-<environment>.yml` and update the path in `application.properties`

### How to run
you can run it locally using command `mvn spring-boot:run`

### How to test
To manually test config you can hit below url
[http://localhost:8888/myapp/dev](http://localhost:8888/myapp/dev)

Here `myapp` is application name in `my-config` and `dev` is environment name.

