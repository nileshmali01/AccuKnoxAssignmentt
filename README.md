# Cow wisdom web server

# MyFirstApp Docker Image

This repository provides a Docker image for running MyFirstApp.

## Prerequisites

- Docker : Ensure that Docker is installed on your machine. You can download Docker from the official website: [https://www.docker.com](https://www.docker.com)

## How to Run

1. Pull the Docker image from Docker Hub:

```  shell
   docker pull kpk00700/myfirstapp:latest
```
   
 1. Run the Docker container with port mapping:
 ``` docker run -p 4499:4499 kpk00700/myfirstapp:latest ```
 This command maps port 4499 of the container to port 4499 on the host machine.

2. Access the application:

Once the container is running, you can access the application by opening a web browser and navigating to ** http://localhost:4499 **.

3. Stop the container:

To stop the running container, use the following command:

``` docker stop <container_id>```

Replace <container_id> with the ID or name of the running container. You can get the container ID or name by running docker ps.

## Customization
If you want to use a different host port, you can modify the port mapping in the ** docker run ** command. For example, to map port 4499 of the container to port 8080 on the host, use the following command:

``` docker run -p 8080:4499 kpk00700/myfirstapp:latest ```

Make sure to update the URL accordingly when accessing the application.


## License
This project is licensed under the MIT License.

``` 
Feel free to customize and enhance this README file based on the specific details of your MyFirstApp Docker image and any additional instructions you'd like to provide.
 ```

## What to expect?
![cow wisdom](https://user-images.githubusercontent.com/9133227/225524281-e81a6673-5550-4db0-9bd0-63f9bbc7c2bc.png)
