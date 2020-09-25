# GameAuth REST API

How to start the GameAuth application
---

1. Run `mvn clean install` to build your application
2. Start application with `java -jar target/gameauth-0.0.1-SNAPSHOT.jar server config.yml`
3. To check that your application is running enter the url `http://localhost:8080/gameusers` and enter user login information


# User Roles
1. Default roles able to login are admin and user
2. Both roles have the same "password" login
3. Admin role is capable of viewing entire list of current active users on server

Health Check
---

To see your applications health enter the url `http://localhost:8081/healthcheck`
