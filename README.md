# simple-rest-service-swagger

Simple Rest service using Spring MVC and Boot 

Configuration added to have swagger generated automatically ( Refer SwaggerConfig )

Once started up docs are available in 
http://localhost:8080/v2/api-docs

Tip : 
look at startup to confirm if swagger config is picked up
e.g
2017-10-25 15:36:28.631  INFO 90536 --- [           main] pertySourcedRequestMappingHandlerMapping : Mapped URL path [/v2/api-docs] onto method [public org.springframework.http.ResponseEntity<springfox.documentation.spring.web.json.Json> springfox.documentation.swagger2.web.Swagger2Controller.getDocumentation(java.lang.String,javax.servlet.http.HttpServletRequest)]




Compile as maven project 

mvn clean install 

Execute from

Application.java


GET call http://localhost:8080/person

POST call http://localhost:8080/person

payload

{
  "firstName": "Jason",
  "lastName": "Bourne",
  "phone": "000-000-000",
  "email": "secret@gmail.com"
}