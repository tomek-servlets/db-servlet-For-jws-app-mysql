# db-servlet-For-jws-app-mysql

An example of a simple application working with the 

`JBoss Web Server 3.1 Apache Tomcat 8 + MySQL (with https)`

on OpenShift.

We create here manualy the database connection.

See the settings in 

`src/lu/lllc/DBInfo.java`

We do not use the root user beacuse it is not well configured. We use:

`user = "user";`

`password = "password";`


They must be created during the instalation of 

`JBoss Web Server 3.1 Apache Tomcat 8 + MySQL (with https)`

Remember also to leave empty the 

`Git Reference`

and the 

`Context Directory`

when configuring 

`JBoss Web Server 3.1 Apache Tomcat 8 + MySQL (with https)`

The database name is `lllc`

The SQL file you can find in

`SQL/lllc.sql`

You can use PhpMyAdmin from

https://github.com/tomek-servlets/PhpMyAdminFor-jws-app-mysql
