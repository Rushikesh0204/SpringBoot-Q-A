# SpringBoot-Q-A

1)what is spring boot:
Spring boot is a java framework that makes it easier to create and run java applications
It simplifies the configuration and setup process, allowing devlopers to focus more on 
writing code for their application
Spring Boot ,a module of the spring framework facilatated Rapid apllication Devlopment(RAD) 
capabilityes (reduce boilerplate code 
* Spring Boot solve many developer problem 
  a) Configurations :
  b) Dependency Management : all transitive dependency dwunlode
  c)Embedded Server:

Q2) WHy Spring Boot over Spring ?
1.many advantages : like simplifies the devlopment ,make it easier to create stand-alone application
 a) Easy to use: remove boilerplate code
 b)Production Ready Application : 
 c) Rapid Development: Opiniated approach and auto-configuration enable developers to quickly apps
 d)Starter Dependency Management : SB provide and easy to add common features to oure application
 e)Autoconfiguration: in Spring we have to config with java based or xml based ,we have to 
 explicitly define which bean to create and how to create and where to create -->in spring boot automaticaly config by annotation
 d)Embedded server: provide tomcat server by default

 **Feature           ***  Spring Boot ** Spring Framwork
   Opinionated       -->   yes           no
   Auto-configuration -->  yes           no
   Starter dependencies->  yes           no
   embedded server    ---> yes           no
   Flexibility        -->  less          more
   (flexibility --in spring boot most of the thing done by spring so less,
   in spring framework work done by programer so more)

Q3) Working of Spring Boot
1.Spring boot start by scanning the starter dependencies in pom.xml--->then download and auto-configure 
the modules as you included in pom.xml(web dependency) download-->meven build, auto-config-->run 
spring-boot-starter-web-->downloads all dependency(build time) required for web and 
configure(run-auto-scanning) the things like spring mvc







What is a Spring configuration file?
-A Spring configuration file defines the relationship between different classes in the Spring application.
it defines application behavior by allowing you to declare configurations such as Beans and Bean life cycles.
@Configuration annotation are very similar to questions about the Spring configuration file.







What is the Spring IoC (Inversion of Control) Container?


