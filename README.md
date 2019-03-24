# easy-notes

This application is developed by using Spring Boot, My SQL, JPA, Restful WebServices.
This is a simple webservice for taking the notes and fetching it from DB.


Step 1 : Click Switch to full version on http://start.spring.io page.

Step 2 : Enter the details as follows -

Group : com.example
Artifact : easy-notes
Name : easy-notes
Description : Rest API for a Simple Note Taking Application
Package Name : com.example.easynotes
Packaging : jar (This is the default value)
Java Version : 1.8 (Default)
Dependencies : Web, JPA, MySQL, DevTools

For More info please visit: https://www.callicoder.com/spring-boot-rest-api-tutorial-with-mysql-jpa-hibernate/

In the above page they have used application.properties ,but here application.yml .

Postman can be used for accessing the webservices.

localhost:8080/api/notes/
POST:
{"title":"My Second Note", "content":"Spring Boot is Colorful"}
GET:
localhost:8080/api/notes/2
Sample Output:
{
    "id": 2,
    "title": "My Second Note",
    "content": "Spring Boot is Colorful",
    "createdAt": "2019-03-24T04:23:01.000+0000",
    "updatedAt": "2019-03-24T04:23:01.000+0000"
}
