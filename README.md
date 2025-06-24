# leaflite

### Project Description: Simple Website Deployment on a Virtual Machine (EC2 Instance) using Docker (V1)

This project involves deploying a simple static website to a Virtual Machine (Amazon EC2 instance, DigitalOcean Droplet, Linode, etc.) using Docker. The website consists of HTML, CSS, and JavaScript files, and it is served using the Nginx web server. The process includes creating the website content or downloading already-made website files, writing a Dockerfile to containerize the application, building the Docker image, and running the container on a virtual server.

---

## 📘 What You Will Learn

- What is a container?
- Why do we need containers?
- What is Docker?
- How to create an image and run a container.

---

## 🛠️ Key Steps

### 1. Create Website Content or Download from Tooplate
- Develop the HTML, CSS, and JavaScript files to form the static website.
- Or download ready-made website files from [Tooplate](https://www.tooplate.com/).

### 2. Dockerize the Application
- Write a `Dockerfile` using the official Nginx image.
- Copy the website files into the appropriate directory for Nginx to serve.

### 3. Build the Docker Image
- Build the Docker image locally to package the website and Nginx server.

### 4. Deploy to EC2 Instance
- Launch an Amazon EC2 instance or any virtual machine of your choice.
- Install Docker on the EC2 instance:  
  - [Install Docker on Ubuntu](https://docs.docker.com/engine/install/ubuntu/)  
  - [Install Docker on CentOS](https://docs.docker.com/engine/install/centos/)
- Transfer the Docker image to the EC2 instance or build it directly on the instance.
- Run the Docker container to serve the website.

### 5. Access the Website
- Configure security groups and firewall rules to allow HTTP traffic.
- Access the site via the EC2 instance's public IP address or domain name.

---

## ✅ Benefits

- **Portability:** Easily deploy the same container anywhere.
- **Simplicity:** Use of Docker and Nginx streamlines the web server setup.
- **Scalability:** Easily scale by running more containers or using orchestration tools.

---

> 🔀 **Next Version:** The next version of this project, including enhancements and additional features, is available in the [`v2` branch](https://github.com/isrealei/leaflite/tree/v2) of this repository.

