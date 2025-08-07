# XOps Static Web App
 
This is a simple static website that displays a "Hello from XOps" message. The project is containerized using Docker and runs on your local machine.
 
---
 
## Steps to Run
 
### 1. Clone the Repository
 
### 2. Build the Docker Image
 
 --> docker build -t xops-app .
 
### 3. Run the Docker Image
 
 --> docker run -d -p 8080:80 xops-app