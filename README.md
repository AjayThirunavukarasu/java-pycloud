# spring-boot-user-registration-and-Login

What we have to build?

We have build two main functionalities:

Register user (stored data into MySQL database). 
Login Authentication - validate user login credentials with database email and password. 
We will secure the Registered Users Page with role-based Spring Security.

for local server:
create databse webapp;

ALTER USER 'root'@'localhost' IDENTIFIED BY 'root';
FLUSH PRIVILEGES;

RUN Java Background:

nohup java -jar registration-login-0.0.1-SNAPSHOT.jar > app.log 2>&1 &
