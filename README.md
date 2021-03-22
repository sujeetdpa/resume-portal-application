
# Resume-Portal-Application
A dynamic website where user can register and create their resume and get a public link of the resume which can be shared.

# How to run the project
1.Require Java 8 or above, MySQl Server installed.
2.Open the project in suitable IDE like Eclipse IDE for Java EE or Intellij Idea so that it download all the required jars.
3.Create a databse with name "resume_portal" in MySQL databse.
4.You can either create a jar of the project and run it or run from the IDE and it will create all the required tables in the database;
5.You need to manually insert a record for admin like(insert into user_login values(0,'Admin','Admin','<BCrypted password>','ROLE_ADMIN','<username>')).
6.In the web Browser open http://localhost:8080/

# Technology Used
1.Frontend- HTML5,Bootstrap.
2.Backend- Java
3.Framework-Spring Boot, Spring Security, Spring Data JPA
4.Databse- MySQL

# Project Related images.
1.Homepage.
![Capture](https://user-images.githubusercontent.com/60792923/112015124-8979ba00-8b51-11eb-9016-8118896439b7.PNG)
2.Register.
![Capture2](https://user-images.githubusercontent.com/60792923/112015440-d362a000-8b51-11eb-921c-29d46b5b1ad2.PNG)
3.Login page.
![Capture3](https://user-images.githubusercontent.com/60792923/112015457-d8275400-8b51-11eb-9087-2b9e360c8e87.PNG)
4.Update User Details.
![Capture5](https://user-images.githubusercontent.com/60792923/112017188-65b77380-8b53-11eb-81b7-04f6dbb410c3.PNG)
5.Admin can VIEW,DELETE and ADD any user.
![Capture6](https://user-images.githubusercontent.com/60792923/112017201-694afa80-8b53-11eb-9214-de0152fcef5d.PNG)
6.Sample Resume tempelate with public link.
![Capture7](https://user-images.githubusercontent.com/60792923/112017223-6d771800-8b53-11eb-945b-8daad9ffc985.PNG)
