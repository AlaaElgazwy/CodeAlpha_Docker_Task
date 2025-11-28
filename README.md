# DevOps Internship Task 4: Web Server using Docker

This repository contains the solution for **Task 4** of the CodeAlpha DevOps Internship.
The goal is to deploy and manage a web server inside a Docker container.

## 📋 Project Overview
- **Tool Used:** Docker
- **Base Image:** Nginx (Alpine)
- **Objective:** To create a custom Docker image serving a static HTML page and manage its lifecycle.

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/AlaaElgazwy/CodeAlpha_Docker_Task.git](https://github.com/AlaaElgazwy/CodeAlpha_Docker_Task.git)
   cd codeAlpha_Docker_Task 

2. **Build the Docker Image:**

docker build -t codealpha-web .

3. **Run the Container:**

docker run -d -p 8081:80 --name codealpha-container codealpa-web

4. **Access the Web Server:**

Open your browser and visit: http://localhost:8081

5. **:**
🛠 Commands Used for Monitoring

To verify the container health and logs:

docker ps
docker logs codealpha-container
docker stats codealpha-container --no-stream


📸 Screenshots
### 1. docker logs 

![docker logs](/home/alaa/Pictures/Screenshots/Screenshot from 2025-11-27 21-39-50.png)