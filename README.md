# SpringBootFX
Simple example for Spring Boot and JavaFX application 

Contains profiles:**default**,**nmi** and**aper**

Active profile **nmi** sets in *application.yml*
```
spring:
    main:
        web-application-type:none
        banner-mode: off
    profiles:
        active: nmi
logging: 
    level:
    org:
        springframework: info
```
