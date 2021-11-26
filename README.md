# RESTful Service Spring Boot

This service is a simple RESTful Service built using Spring Boot.

How to Run:
- Run using Grandle.
```
.\gradlew bootRun
```

- Run using JAR file.
```
.\gradlew build

THEN

java -jar .\build\libs\restService-0.0.1-SNAPSHOT.jar
```

- Request
```
http://localhost:8080/greeting

OR 

http://localhost:8080/greeting?name=Martin
```

Expected Results:
```
{
    "id": 2,
    "content": "Hello, World!"
}

OR

{
    "id": 1,
    "content": "Hello, Martin!"
}
```