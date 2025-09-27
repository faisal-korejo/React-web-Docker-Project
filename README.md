# 🚀 React ToDo App - Dockerized Deployment

This is a **React-based ToDo application** that I explored from [Piyush Sachdeva’s GitHub](https://github.com/piyushsachdeva).  
I have successfully **containerized** this project using **Docker** and deployed it on an **Ubuntu (EC2) server**.  

---

## 📌 Features
- Add, update, and delete tasks  
- Simple and clean React UI  
- Containerized using **Docker** for portability  
- Available on **Docker Hub**  

---

## 🛠️ Tech Stack
- **Frontend:** React.js  
- **Containerization:** Docker  
- **Deployment Environment:** Ubuntu (AWS EC2)  

---

## 📂 Project Setup (Without Docker)

If you want to run the project locally without Docker:

```bash
# Clone this repository
git clone https://github.com/<your-username>/todoapp-docker.git
cd todoapp-docker

# Install dependencies
npm install

# Start development server
npm start
```

The app will run on `http://localhost:3000`.

---

## 🐳 Run with Docker

### 1️⃣ Build Docker Image
```bash
sudo docker build -t faisalzama0786/dockerproject:latest .
```

### 2️⃣ Run Docker Container
```bash
sudo docker run -dp 3000:80 faisalzama0786/dockerproject:latest
```

Now visit: 👉 `http://<your-server-ip>:3000`

---

## 📤 Docker Hub

I also pushed the image to **Docker Hub**, so you can directly pull and run:

```bash
docker pull faisalzama0786/dockerproject:latest
docker run -dp 3000:80 faisalzama0786/dockerproject:latest
```

---

## 📸 Screenshots
(Add some screenshots of your running app and Docker Hub repo here)

---

## 📚 Learnings
Through this project I learned:
- Writing a custom **Dockerfile** for a React project  
- Building and tagging Docker images  
- Running containers and exposing ports  
- Publishing images to **Docker Hub**  
- Deploying a React app on **Ubuntu (AWS EC2)** with Docker  

---

## 🤝 Acknowledgments
- Thanks to **[Piyush Sachdeva](https://github.com/piyushsachdeva)** for the original React project.  
- Inspired by open-source learning and community contributions.  

---

## 🔖 License
This project is for **learning purposes only**. Original code belongs to the respective author.
# React-web-Docker-Project
