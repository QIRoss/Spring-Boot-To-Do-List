# Spring Boot To Do List Backend

I'll leave it right here so I can remember to never code in Java again.
See ya!

## How to Use:

* Package the application:
    ```
    mvn clean package
    ```

* Build and start the containers:
    ```
    docker-compose up --build
    ```

* Create a TODO:
    ```
    curl -X POST -H "Content-Type: application/json" -d '{"title":"Learn Spring Boot","completed":false}' http://localhost:8080/api/todos
    ```

* Get all TODOs:
    ```
    curl http://localhost:8080/api/todos
    ```