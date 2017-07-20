# Embedded Engine with Cockpit and Tasklist app

Example woh to build a web application for tomcat with an embedded process engine. Process models can be added.

## Access the REST api

The REST api is included, too. As it is in the Cockpit included, the url is http://localhost:8080/camunda-webapp-standalone-customized/api/engine/engine/default/task

To log in, you have to call 

```
POST http://localhost:8080/camunda-webapp-standalone-customized/api/admin/auth/user/default/login/cockpit 
```
Header: Content-Type=application/x-www-form-urlencoded Accept=application/json 
Body: username=demo password=demo

and keep the Cookie.

