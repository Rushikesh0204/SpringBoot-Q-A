# SpringBoot-Q-A

1)what is spring boot:
Spring boot is a java framework that makes it easier to create and run java applications
It simplifies the configuration and setup process, allowing devlopers to focus more on 
writing code for their application
Spring Boot ,a module of the spring framework facilatated Rapid apllication Devlopment(RAD) 
capabilityes (reduce boilerplate code 
* Spring Boot solve many developer problem *
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

 
<pre> 
 **Feature            ***  Spring Boot  ** Spring Framwork
   Opinionated       -->   yes           no
   
   Auto-configuration -->  yes           no
   Starter dependencies->  yes           no
   embedded server    ---> yes           no
   Flexibility        -->  less          more
   </pre>

   
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
( xml file which is contains the infrmation of classes and describe how those classes configured linked each other )

Q) What is spring Bean ?
- also called object -->creation manage and destroy by spring container calledd as spring IOC
- created by the help of configuration file --which is supply by use to ioc container

Q) Difference between Constructor and Setter Injection?
<pre>
  constructor                  Setter 
  -partial injection not       partial injection yes
  possible
  -new instance will be        Not created but 
  created , modification        modification done
  not be possible 
  -bean have many property     some few property
  
</pre>

Q) what are the Bean Scope Spring Provided?
- Scope-> how long object present in application
- 1)Singleton:only one object application
- 2) Prototype:every time new object is created when you access 
  3) Request:
  4) Session: container create object when login user and destroy on log out
 
Q) Whate Bean Wiring?
(injecting dependancy in bean )
beans are combined together inside the Spring Container that called 
linkking two object  -- how in xml file 
spring container should know what beans are needed and how the beans are dependent each other while wiring beans

Q) What is Autowiring in Spring and what are the different modes it have?
Spring framework can inject dependency Automatically

  






What is the Spring IoC (Inversion of Control) Container?
- spring container use--managing application comonents by creating object wiring them together along with cofiguring and managing their overall life
cycles
-spring container to do task will provided either by xml configuration ,annotation of java code This whole process called as inversion of control


Q) What are the type of DI ?
Mainly there are 5 type of dependency injectjection 
a)constructor injection : object are creating aby parameterise cunstructor and valuse are injecter
b) Setter Injection : object created by default constructor and value set by setter methods 
c) Field Injection(@Autowired):
d) circular : using setter
e)Lookup method injection: two object are connected 1st is singletone and 2nd is proto 



