
# Project:Yolomy Micro-service
- Hey its Robin Adhola here with a new IP that i have been working on recently as part of the Moringa school content as when it comes to Devops Engineering.

- Feel free to clone this project first:'https://github.com/Vinge1718/yolo"(If you want the whole practice experience for yourself).

## 🚀 Getting Started

### 🔧 Prerequisites

- With Docker & Docker Compose installed
- Including Git, we should be set for what the project has to offer.

### 📦 Clone the Project
- But first, we should:
```bash
git clone https://github.com/Rjamez/yolo#
cd yolo
```

### 🐳 Run with Docker Compose

You can either **build locally** or **pull images from my DockerHub**.

#### Option A: Build locally
```bash
docker-compose up --build
```
-I think this option is more recommended since the project is already given to you.

#### Option B: Use my prebuilt images from DockerHub(r0bii)

Replace the `build:` keys in `docker-compose.yaml` with:

```yaml
image: r0bii/yolo_frontend:v1.0.0
image: r0bii/yolo_backend:v1.0.0
```

Then run:
```bash
docker-compose up
```

---

### 🌐 Access the App

Frontend: http://localhost:3000

Backend API: http://localhost:5000

MongoDB: runs internally at mongo:27017


## 🧪 Features

-Add and manage products from the frontend dashboard
![Alt text](/image.png)
![Alt text](/IMG.png)
![Alt text](/image2.png)
-Persistent data storage using Docker Volumes
-Real-time interaction between containers via internal Docker networking
-DockerHub image versioning using semver (v1.0.0) or (latest)


## ✅ Tasks Covered (Rubric Alignment)

-  Containerized backend, frontend, and DB via docker compose build
-  Orchestrated services via Docker Compose
-  Persistent volumes and bridge network
-  Image tagging & push to DockerHub
-  Git workflow with commits and structure:

   "commit 1f3cd99880fd0e78e08fe51ae343d023f95e6623
   Author: Rjamez
   Message: created a new yaml file so as to not have complex code...

   commit 4724786e3083aeaa7b769593e4d736ffced86853
   Author: Rjamez
   Message: ..."

-  Screenshot proof of deployment
   ![Alt text](/IMG2.png)


Email: 'robin.adhola@student.moringaschool.com'  
Feel free to checkout my GitHub for more work  in the future: [@r0bii](https://github.com/r0bii)

---
