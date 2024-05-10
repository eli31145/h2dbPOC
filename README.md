"# h2dbPOC" 
POC to test out H2 DB. 
Changes of note are found in application.properties file

Some pointers to note:
1) By default, Spring Boot configures the application to connect to an in-memory store with the username: sa and an empty password. 
Here, we set username as: username, password as: password (NOT RECOMMENDED FOR PROD)
2) If you want to save the db file in your machine, need to specify file:"path"
3) After starting SpringBoot app, to access console of h2, use this url: http://localhost:xxxx/h2-console
4) The endpoint “/h2-console” is done by default, you can customize in applications.properties if desired
5) Make sure the details of Console are filled in correctly as per application.properties file before connect, once connected SQL commands can be run if you have done any CRUD using POSTMAN to see results
