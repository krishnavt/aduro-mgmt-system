# Aduro Management System Spring Boot, Inmem, JPA, Hibernate Rest API Tutorial

Build Restful CRUD API for a simple Note-Taking application using Spring Boot, Mysql, JPA and Hibernate.

## Requirements

1. Java - 1.8.x

2. Maven - 3.x.x

3. Mysql/Inmem H2 - 5.x.x

## Steps to Setup

**1. Clone the application**

```bash
git clone https://github.com/krishnavt/sprint-rest-crud.git
```


**2. Change inmem username and password as per your installation**

+ open `src/main/resources/application.properties`

+ change `spring.datasource.username` and `spring.datasource.password` as per your mysql installation

**3. Build and run the app using maven**

Run the app without packaging it using -

```bash
mvn spring-boot:run
```

The app will start running at <http://localhost:8080>.

## Explore Rest APIs

The app defines following CRUD APIs.

    POST /api/create-employees
    
    GET /api/list-employees
    
    GET /api/get-employee/{id}
    
    PUT /api/update-employee/{id}
    
    DELETE /api/delete-employee/{id}

You can test them using postman or any other rest client.

## Screenshots

    POST create-employees

![alt text](https://github.com/krishnavt/image-in-readme/blob/main/Screen%20Shot%202021-05-23%20at%209.25.10%20AM.png)

    GET list-employees
    
![alt text](https://github.com/krishnavt/image-in-readme/blob/main/Screen%20Shot%202021-05-23%20at%209.25.22%20AM.png)
    
    GET get-employee
![alt text](https://github.com/krishnavt/image-in-readme/blob/main/Screen%20Shot%202021-05-23%20at%209.25.32%20AM.png)
    
    PUT update-employee

![alt text](https://github.com/krishnavt/image-in-readme/blob/main/Screen%20Shot%202021-05-23%20at%209.25.44%20AM.png)

    DELETE delete-employee
![alt text](https://github.com/krishnavt/image-in-readme/blob/main/Screen%20Shot%202021-05-23%20at%209.25.55%20AM.png) 
