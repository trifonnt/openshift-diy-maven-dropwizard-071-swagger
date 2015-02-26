Dropwizard-0.7.1 with Swagger on OpenShift-diy cartridge
==================================

Steps to build and start
=====
+01) Build

```shell
$ mvn clean install
```


+02) Start
```shell
$ java -jar ./target/d3soft.dropwizard.example-0.0.1-SNAPSHOT.jar server example.yml
```


Test URLs - http://localhost
============================
 + [http://localhost:8080/app/api](http://localhost:8080/app/api) -- Blog
 + [http://localhost:8080/app/api/hello-world?name=Successful+Dropwizard+User](http://localhost:8080/app/api/hello-world?name=Successful+Dropwizard+User)
 + [http://localhost:8080/app/api/hello-world2/Successful%20Dropwizard%20User](http://localhost:8080/app/api/hello-world2/Successful%20Dropwizard%20User)
   [http://localhost:8080/app/api/hello-world2/Successful Dropwizard User](http://localhost:8080/app/api/hello-world2/Successful Dropwizard User)
 - [http://localhost:8080/app/api/hello-world3](http://localhost:8080/app/api/hello-world3)

Test URLs - http://app-domain.rhcloud.com
=========================================
 + [http://dev-trifon.rhcloud.com/app/api](http://dev-trifon.rhcloud.com/app/api/) -- Blog
 + [http://dev-trifon.rhcloud.com/app/api/hello-world?name=Successful+Dropwizard+User](http://dev-trifon.rhcloud.com/app/api/hello-world?name=Successful+Dropwizard+User)
 + [http://dev-trifon.rhcloud.com/app/api/hello-world2/Successful%20Dropwizard%20User](http://dev-trifon.rhcloud.com/app/api/hello-world2/Successful%20Dropwizard%20User)
   [http://dev-trifon.rhcloud.com/app/api/hello-world2/Successful Dropwizard User](http://dev-trifon.rhcloud.com/app/api/hello-world2/Successful Dropwizard User)
 - [http://dev-trifon.rhcloud.com/app/api/hello-world3](http://dev-trifon.rhcloud.com/app/api/hello-world3)


Admin port
==========
 - [http://localhost:8080/admin/](http://localhost:8080/admin/)

...OR... - depending on .yml configuration

 - [http://localhost:8081/](http://localhost:8081/)