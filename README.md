# 🎯 Action Repository

A repository designed to perform Git operations that trigger **GitHub webhook events** (Push, Pull Request, Merge), which are sent to the `webhook-repo` Flask app for real-time processing and display. This project demonstrates seamless GitHub webhook integration using Flask and MongoDB.

---

## ✨ Features

- **Webhook Event Triggering:** Perform Git operations to initiate **Push**, **Pull Request**, and **Merge** events.
- **Integration with webhook-repo:** Events are forwarded to a Flask-based server and saved to MongoDB.
- **Formatted Event Display:** View events in a user-friendly UI with timestamps and operation summaries.
- **Simple Setup:** Quick integration using GitHub’s built-in webhook system.

---

## 🛠️ Technologies Used

- **Platform:** GitHub  
- **Version Control:** Git, Bash  
- **Integration:** GitHub Webhooks  
- **Backend:** Flask (in `webhook-repo`)  
- **Database:** MongoDB (via `webhook-repo`)  
- **Event Types:** Push, Pull Request, Merge  

---

## 🚀 Demo Video

### 🔴 Webhook Event Demonstration  
[![Webhook Demo](https://img.youtube.com/vi/fwxRZ6P5mdA/0.jpg)](https://youtu.be/fwxRZ6P5mdA)

---

## 🔧 Installation & Setup

### 📦 Requirements

- GitHub account  
- Git installed locally  
- Access to [`webhook-repo`](https://github.com/Harshverma893/webhook-repo) Flask app  
- A tool like **ngrok** to expose the local Flask server  
- MongoDB instance for event storage  

---

### 📁 Clone the Repository

```bash
git clone https://github.com/Harshverma893/action-repo.git
cd action-repo
