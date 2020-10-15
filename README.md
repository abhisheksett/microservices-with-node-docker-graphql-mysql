# Microservices with docker, mysql, node, GraphQL and React

This is a sample application to demonstrate microservices using docker, mysql, node, graphql and React

### Instructions

- To run the application, first run
    ```
    docker-compose up
    ```

- Once the containers are built, on a separate terminal run
    ```
    docker ps
    ```
    This will show list of built containers
    <br />
- Check the container id of any listing container and login to that by following command
    ```
    docker exec -it <container-id> bash
    ```
    Once logged in, run the migrations with following
    ```
    yarn db:migrate
    ```