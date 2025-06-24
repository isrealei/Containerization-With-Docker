# leaflite

### V2

### Project Brief: **Deploying a Scalable Satic Web Application with NGINX Reverse Proxy and Load Balancing**

#### **Objective:**
Expand upon the student's previous project of deploying a simple website using NGINX by introducing scalability and load balancing. The goal is to deploy three instances of a web application on the server and configure NGINX as a reverse proxy and load balancer. NGINX will direct external traffic to the backend application instances to ensure better performance, fault tolerance, and scalability.

---

#### **Project Scope:**
1. **Web Application Instances:**
   - Deploy three instances of the same web application, each running in its own Docker container.
   - The web application will be a basic HTML-based website (or a simple dynamic application if the student wishes to extend functionality).

2. **NGINX Reverse Proxy and Load Balancing:**
   - Configure NGINX to run either as a service on the host machine or as a Docker container.
   - Set up NGINX as a reverse proxy to forward external HTTP requests to the backend web application instances.
   - Implement load balancing to distribute incoming traffic evenly across the three backend instances.

3. **Networking:**
   - Use Docker networks to enable communication between the NGINX container (if used) and the application containers.
   - Expose the NGINX service on the host machine to handle external traffic.

4. **Documentation and Testing:**
   - Document the deployment process, including steps to configure and test the setup.
   - Demonstrate the load balancing functionality by accessing the application through NGINX and observing the traffic distribution among backend instances.

---

#### **Deliverables:**
1. A fully functional setup with:
   - Three running instances of the web application.
   - NGINX configured as a reverse proxy and load balancer.
2. Docker Compose or individual Docker commands used for deployment.
3. Configuration files, including:
   - NGINX configuration file (`nginx.conf` or equivalent).
   - Any necessary Docker Compose YAML files.
4. Documentation covering:
   - Deployment steps.
   - Testing procedures (e.g., how to test load balancing behavior).

---

#### **Requirements for the Student:**

1. **Knowledge and Tools:**
   - Familiarity with Docker and Docker Compose.
   - Understanding of NGINX configuration for reverse proxy and load balancing.
   - Basic networking concepts, including how Docker manages container networking.

2. **Environment Setup:**
   - A Linux server or a local machine with Docker and Docker Compose installed.
   - Text editor or IDE to modify and create configuration files.
   - Access to a web browser or tools like `curl` to test the application.

3. **Development Steps:**
   - Create a Dockerfile for the web application (if necessary).
   - Deploy three instances of the web application using Docker.
   - Configure NGINX to act as a reverse proxy and load balancer:
     - Define upstream servers for the backend instances.
     - Configure load balancing in NGINX (e.g., round-robin or least connections).
   - Test the setup by accessing the application via NGINX and verifying load balancing.

4. **Testing Scenarios:**
   - Simulate external traffic by sending multiple HTTP requests and observe backend traffic distribution.
   - Temporarily stop one backend instance and ensure NGINX continues routing traffic to the other instances.

---

#### **Expected Outcome:**
By the end of this project, the student will have a clear understanding of:
- How to deploy multiple instances of an application in Docker.
- The role of NGINX as a reverse proxy and load balancer.
- The importance of load balancing for scalability and fault tolerance.

This project serves as an excellent stepping stone towards advanced topics in containerization, microservices architecture, and system scalability.
