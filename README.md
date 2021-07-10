# Spring Boot Employee Manager

<p><span style="color: rgb(0, 0, 0); font-family: Ubuntu; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; display: inline !important; float: none;">Technology:&nbsp;</span></p>
<p><span style="color: rgb(0, 0, 0); font-family: Ubuntu; font-size: 14px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; display: inline !important; float: none;">Java, TypeScript, Angular, Spring Boot and Spring Rest, MySQL Database, Postman, REST API</span> </p>

<p>SpringBoot Backend :&nbsp;<a href="https://github.com/debrupofficial365/spring-boot-employee-manager">https://github.com/debrupofficial365/spring-boot-ecommerce-backend</a></p>
<p>Angular Frontend : <a href="https://github.com/debrupofficial365/angular-ecommerce-website-frontend">https://github.com/debrupofficial365/angular-employee-manager</a></p>


<br/>
#######################################################
<br/>


[![Build Status](https://travis-ci.org/codecentric/springboot-sample-app.svg?branch=master)](https://travis-ci.org/codecentric/springboot-sample-app)
[![Coverage Status](https://coveralls.io/repos/github/codecentric/springboot-sample-app/badge.svg?branch=master)](https://coveralls.io/github/codecentric/springboot-sample-app?branch=master)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

Minimal [Spring Boot](http://projects.spring.io/spring-boot/) sample app.

## Requirements

For building and running the application you need:

- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

## Running the application locally

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `de.codecentric.springbootsample.Application` class from your IDE.

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn spring-boot:run
```

## Deploying the application to OpenShift

The easiest way to deploy the sample application to OpenShift is to use the [OpenShift CLI](https://docs.openshift.org/latest/cli_reference/index.html):

```shell
oc new-app codecentric/springboot-maven3-centos~https://github.com/codecentric/springboot-sample-app
```

This will create:

* An ImageStream called "springboot-maven3-centos"
* An ImageStream called "springboot-sample-app"
* A BuildConfig called "springboot-sample-app"
* DeploymentConfig called "springboot-sample-app"
* Service called "springboot-sample-app"

If you want to access the app from outside your OpenShift installation, you have to expose the springboot-sample-app service:

```shell
oc expose springboot-sample-app --hostname=www.example.com
```

## Copyright

Released under the Apache License 2.0. See the [LICENSE](https://github.com/codecentric/springboot-sample-app/blob/master/LICENSE) file.

<br/>
#######################################################
<br/>

---><br/> Single page website to store, update, delete employee information from the database.

---><br/> Here for the frontend, I use Angular, and Spring Boot as the backend and MySQL for the database.

---><br/> In my backend API, I have a model or entity to hold the employee attributes. Have a repository to access the database, extended by JpaRepository. And, service to implements all the business logic to manage the employee operations. A controller to maps requests and handles them and calls the service if needed.
For the database, MySQL database has been used and connected with the backend through the application.properties.

---><br/> I have checked the HTTP requests on this API with Postman.

---><br/> In the Angular part, also have a model which holds the employee attributes. Have service to connect the angular app with backend controller, here I use HttpClientModule and Observable. And the component for the business logic and handle the user requests by the UI.

---><br/> Here I learned about the Cross-origin concept.



![WhatsApp Image 2021-06-21 at 10 14 52 PM](https://user-images.githubusercontent.com/57451228/125170523-05654400-e1cd-11eb-8fce-2f1502b836a7.jpeg)
![ecom](https://user-images.githubusercontent.com/57451228/125170525-06967100-e1cd-11eb-83d8-b0b097c84658.png)



