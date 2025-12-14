# FitPlanHub - Full Stack Social Fitness Platform 🏋️‍♂️

### **Project Overview**
FitPlanHub is a dynamic full-stack web application designed to connect fitness trainers with health enthusiasts in a simulated marketplace environment. The platform bridges the gap between social networking and e-commerce, allowing trainers to publish digital workout products and users to curate a personalized fitness feed.

Built on a **RESTful architecture**, the application uses **Python (Flask)** for the backend and **Vanilla JavaScript** with **Bootstrap 5** for a modern, responsive frontend. It features a robust **SQLite** database that manages complex relationships, specifically the many-to-many associations required for a social graph (Users following Trainers) and transactional logic (Users subscribing to Plans).

### **Key Features**
* **Role-Based Access Control (RBAC):** Secure authentication distinguishing between "Trainers" (Creators) and "Users" (Consumers) using **JWT (JSON Web Tokens)**.
* **Dynamic Trainer Dashboard:** A dedicated interface for trainers to create, price, and publish workout plans. Data creates an instant API endpoint consumed by the feed.
* **Smart Social Feed:** A personalized feed algorithm that only displays content from trainers the user follows.
* **Discovery Engine:** A "Find Trainers" feature allowing users to browse professionals and manage their social graph.
* **Interactive UI:** Built with Bootstrap 5 for mobile responsiveness, featuring glass-morphism login effects and asynchronous data fetching for a smooth user experience.

### **Tech Stack**
* **Backend:** Python, Flask, Flask-SQLAlchemy, Flask-JWT-Extended.
* **Frontend:** HTML5, CSS3, JavaScript (ES6+), Bootstrap 5.
* **Database:** SQLite.
* **Version Control:** Git & GitHub.

---

### **🚀 How to Run Locally**

**1. Clone the Repository**
```bash
git clone [https://github.com/YOUR_USERNAME/fit-plan-hub.git](https://github.com/YOUR_USERNAME/fit-plan-hub.git)
cd fit-plan-hub