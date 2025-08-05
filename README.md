# DevOps Internship - Task 2

## 📌 Task Description

The objective of this task is to implement a basic CI/CD pipeline using Jenkins. This includes setting up Jenkins locally, creating a Jenkins pipeline, and automating the build, test, and deploy steps using a `Jenkinsfile`.

---

## 📁 Project Structure

Devops-Task-2/
├── Jenkinsfile
├── app.py
└── README.md

---

## ⚙️ Technologies Used

- Jenkins (Local setup)
- GitHub
- Python 3.13.5
- Windows 10 (Command prompt/PowerShell)

---

## 🚀 Jenkins Setup Steps

1. **Install Java JDK**  
   Required to run Jenkins.

2. **Download Jenkins WAR File**  
   Run using:
   ```bash
   java -jar jenkins.war --httpPort=9090

---

   Access Jenkins Portal
Open: http://localhost:9090

Install Suggested Plugins
During setup.

Create a Freestyle or Pipeline Project

Connect to GitHub Repo
Use this repo: https://github.com/satheesh-dev/Devops-Task-2

---

 2

🧪 Pipeline Stages (Defined in Jenkinsfile)
1. Build Stage
Echoes a message

Validates environment

2. Test Stage
Prints Python version

Executes app.py script

3. Deploy Stage
Simulates deployment with a message

---

Output
✅ Successfully connected Jenkins to GitHub repo.

✅ Pipeline triggers on commits.

✅ All three stages (Build, Test, Deploy) ran without errors.


<img width="766" height="738" alt="Screenshot 2025-08-05 130759" src="https://github.com/user-attachments/assets/6d4d802d-5fc6-4b36-9db3-116cf0ac682b" />

