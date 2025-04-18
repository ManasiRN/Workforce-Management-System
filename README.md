# Workforce Management System

A robust and scalable web-based platform designed to optimize task management and enhance employee performance tracking. Built using modern technologies like **React**, **Tailwind CSS**, and **Vite**, this project ensures high performance, seamless user experience, and streamlined operations.

## 🚀 Features

- 📋 **Task Management**: Organize, assign, and track tasks across teams with ease.
- 📈 **Employee Performance Tracking**: Monitor productivity metrics and employee activity.
- ⚙️ **CI/CD Integration**: Automated testing and deployment pipelines powered by **Jenkins**.
- 📦 **Containerization with Docker**: Ensures consistent deployments across environments.
- 💾 **Local Storage Integration**: Enables fast and efficient data handling on the client side.
- 🎨 **Modern UI**: Clean and responsive design with **Tailwind CSS**.

## 🛠️ Tech Stack

- **Frontend**: React, Vite, Tailwind CSS
- **DevOps**: Jenkins, Docker
- **Storage**: Local Storage (Browser)
  
## 📦 Deployment

The app is containerized using Docker and supports CI/CD pipelines for smooth deployment. To get started locally:

```bash
# Clone the repository
git clone https://github.com/yourusername/workforce-management-system.git
cd workforce-management-system

# Install dependencies
npm install

# Run the app
npm run dev

# Build Docker image
docker build -t workforce-management-system .

# Run Docker container
docker run -p 3000:3000 workforce-management-system
