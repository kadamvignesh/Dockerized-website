# Dockerized-website

This project demonstrates how to deploy a staic website with NGINX server using Docker.

Prerequisites
Before you begin, ensure you have the following installed on your system:
* Docker

Getting started

1. Clone the repository
   git clone https://github.com/your-username/Dockerized-website.git
   
   cd Dockerized-website

2.Build the Docker Image

  docker build -t my-nginx:latest .

3. Run the Container
   
   docker run -d -p 80:80 my-nginx:latest
   
4. View the Website

   Open your web browser and navigate to http://localhost to see the deployed website.
