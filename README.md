# CloudInfra Project

## Prerequisites
- JDK 11
- Maven 3
- MySQL 8

## Technologies
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch

## Database Setup
Here, we use a MySQL DB.
SQL dump file: `/src/main/resources/db_backup.sql`

To set up the database, import this dump file to your MySQL database server:
```bash
mysql -u <user_name> -p accounts < src/main/resources/db_backup.sql
```
