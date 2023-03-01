# Creating a container for a Spring boot app

1. Clone the Repository and cd to the project root folder
2. To build the image: $ docker build -t backend/dockerdemo .
3. To create the container: $ docker run --rm -d -p 8080:8080 --name dockerdemo backend/dockerdemo:latest
